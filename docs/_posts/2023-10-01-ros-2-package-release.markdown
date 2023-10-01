---
layout: post
title:  "Initial Release of ROS 2 Support for DexHand "
date:   2023-10-01 7:00:00 -0700
categories: software firmware ros2 update
---

<img src="https://user-images.githubusercontent.com/2821763/271841812-7ada5897-f3f1-4629-a548-4b434183bc92.jpg"/>

We are extremely excited to announce the initial release of ROS 2 support for the DexHand!

Our initial release contains a number of packages to suport use of the DexHand with ROS 2:


* [**dexhand_description**](https://github.com/iotdesignshop/dexhand_description): URDF files, and RVIZ2 launch files for viewing the DexHand URDF in RVIZ2. 

* [**dexhand_gesture_controller**](https://github.com/iotdesignshop/dexhand_gesture_controller): High level animation interface, gesture controller, simulation driver, and hardware driver for high level control of a DexHand. This package lets you drive either simulated or hardware DexHand's into poses with an easy high level interface and is a good study on how to pose the hand or as a foundation for other types of controls (such as our LLM controller below).

* [**dexhand_usb_serial**](https://github.com/iotdesignshop/dexhand_usb_serial): Provides serial communication via USB between ROS 2 and the Arduino-based DexHand firmware running on the hand (available in the [dexhand-ble repo on GitHub](https://github.com/iotdesignshop/dexhand-ble)). This package is used by dexhand_gesture_controller to send gestures over to the hardware device, but provides general access to the serial command structure available on the hand.

* [**dexhand_llm_control**](https://github.com/iotdesignshop/dexhand_llm_control): Provides a bridge between ChatGPT (GPT-4) and the DexHand Gesture Controller to enable experiments where you use the DexHand as an output device. Ask it math questions, to do hand gestures, like the peace sign, or other questions and see how GPT-4 interprets and uses the hand as an output device. [Check out our demo video on YouTube](https://youtu.be/GWHLRgOuJLU).


All of these packages are combined by an easy-to-install metapackage which contains scripts for setting up a ROS 2 workspace with all of the dependencies and packages installed and ready for use.

[Get started with the DexHand ROS 2 Metapackage Here](https://github.com/iotdesignshop/dexhand_ros2_meta)



