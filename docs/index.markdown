---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
dexhand.org

# Welcome to DexHand.org


![Hand Tracker and Hand](https://github.com/iotdesignshop/dexhand-ble/assets/2821763/de311dc5-b41e-4f2f-b8e6-849a51983018)


The DexHand project is a low-cost, open source, dexterous hand designed for research and development on humanoid robots. 

Our goal is for the DexHand to be the best open source hand project available, and a great dexterous hand for your robotic research and development activities.

## Origins of the DexHand and This Project

|[<img src="RobotStudio-Logo.png" width="300px">](http://www.therobotstudio.com)|The DexHand was envisioned and released to Open Source by [Rob Knight of The Robot Studio](https://www.therobotstudio.com). This remarkable work is one of many amazing projects Rob has created in over 20 years in robotics.|
|[<img src="IOT_Logo.png" width="200px">](http://www.iotdesignshop.com)|This site and content is maintained by [Trent Shumay from IoT Design Shop](http://www.iotdesignshop.com). Trent has built and tuned a DexHand in the IoT Shop and made it a goal to document this process.|

For contact info and additional detail, [visit the About page](https://www.dexhand.org/about/). For open source license information, [visit the License page](https://www.dexhand.org/license/)

# FAQ's and Getting Started

Our recent response to the project from Social Media and YouTube has been really great to see! We're in the process of trying to get the project updated with additional tutorials, build guides, and resources that our community is contributing back to the project from their builds and learning process. These resources will be added to the web page as they become available. In the short term, we've pulled together some points of interest and commentary on common questions that come up when people first encounter the project.

- **Is there a complete build tutorial I can follow?** - Not yet, but we have a few people building hands and capturing their process in photos and videos along the way. The Quick Links section below contains our video playlist with build info, as well as the repositories and project assets. In the short term, referencing the OnShape CAD model in [The Robot Studio repository](https://github.com/TheRobotStudio/V1.0-Dexhand) is a great reference for a build along with the video files. 
- **Why are there different versions of things in The Robot Studio Repos and the IoT Design Shop Repos??** - We're working to consolidate things. The Robot Studio repos contain the original version of the DexHand files, and still probably have the best mechanical reference to the build assembly via the provided OnShape CAD models and BOM information. The IoT Design Shop repos have the electronics, firmware, and ROS layers that were added to the project since the original inception. Additionally, there are some mechanical "Quality of Life" improvements in the IoT Design Shop mechanical build repo that may be useful. We're working to get this smoothed out a bit, but want to present as much info as possible.
- **Which version of the electronics build and BOM should I follow?** - We'd recommend the IoT Design Shop version as there is a full package of Hardware (based on Arduino Nano RP2040 Connect), Firmware, Demos, and a ROS 2 layer that all work with this system. 

# Quick Links to Important Project Resources
The following links provide easy access to important components of the DexHand project:

- [**DexHand Assembly Videos**](https://github.com/iotdesignshop/dexhand-mechanical-build/wiki/Mechanical-%E2%80%90-3D-Printing,-BOM,-and-Assembling-the-Hand#video-links) - We try to keep this list updated with the latest videos whenever we release new content or instructional materials on YouTube.
- [**DexHand V1.0 GitHub Repository**](https://github.com/TheRobotStudio/V1.0-Dexhand) - Where it all began. The original repo from The Robot Studio with the original STL files, and links to the OnShape CAD models for the V1.0 DexHand. 
- [**DexHand-BLE Repository**](https://github.com/iotdesignshop/dexhand-ble) - Firmware for the Arduino Nano RP2040 Connect and a Python Demo that uses Google MediaPipe Hand Tracker to analyze hand positions and play them back on a DexHand via Bluetooth LE. Runs on PC/Mac/Linux. 
- [**DexHand-Mechanical-Build**](https://github.com/iotdesignshop/dexhand-mechanical-build) - Collection of materials, instructions, and a build Wiki from IoT Design Shop containing details of their V1.0 DexHand build and some mods for ease of assembly and durability.
- [**DexHand-ROS2-Meta**](https://github.com/iotdesignshop/dexhand_ros2_meta) - Home of the ROS 2 drivers and demonstration packages for the DexHand. We have a description package with URDF, a high-level gesture controller, and a new demonstration featuring ChatGPT using the DexHand as an output device. RVIZ2 simulations are available for testing the packages without a hardware hand.

# Resources To Dig Deeper on the DexHand and Humanoid Robots

## YouTube Channels
- [**The Robot Studio YouTube Channel**](https://www.youtube.com/@therobotstudio) - Home of Rob Knight's Robot Studio on YouTube. Rob has been designing humanoid robots for over 20 years and shares his latest work on YouTube. Check out the DexHand and his HOPE Robot Project on the channel. 
- [**IoT Design Shop YouTube Channel**](https://www.youtube.com/@iotdesignshop) - Home of the IoT Design Shop. Lots of progress videos on the build of the DexHand we did at the shop as well as the software and examples.

