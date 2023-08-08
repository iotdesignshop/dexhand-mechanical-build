---
layout: post
title:  "BLE Firmware Released to GitHub"
date:   2023-08-08 7:00:00 -0700
categories: jekyll update
---

![Hand Tracker and Hand](https://github.com/iotdesignshop/dexhand-ble/assets/2821763/de311dc5-b41e-4f2f-b8e6-849a51983018)

We've just released a new project with Arduino Firmware and a Python Demo Application for getting started with DexHand builds.

Firmware Features:
- Tables for configuring servo layouts and ranges
- Simple command system for moving servos and testing the ranges of your build (super useful for adjusting tendons)
- Bluetooth Low Energy (BLE) service for connecting to the hand and sending commands, or streaming DOF angles

Demo App:
- Hand tracking using Google MediaPipe Hand Tracker
- Computes angles of all the DOF's in the hand and streams data across BLE over to the hand


[Check out the GitHub Repo here](https://github.com/iotdesignshop/dexhand-ble)


