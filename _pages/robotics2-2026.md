---
layout: single
toc: true
toc_icon: "bookmark"
author_profile: true
permalink: /robotics2-2026
hidden: true
title: Robotics II
header:
  overlay_image: /assets/images/hexar.jpg
  overlay_color: "#ffffff"
  overlay_filter: linear-gradient(rgba(79, 45, 127, 0.9), rgba(129, 138, 143, 0.5))
excerpt: >
  <small>Lectures/Labs: Tue/Thu 10:50 a.m. - 1:30 p.m., LSCA 105</small>
---
# Robotics 2, Spring 2026

## Latest Updates

- 03/30: Updated A4 link and IMU code link.
- 03/08: Updated class 10 example code link.
- 02/24: Updated class 8, 9 slides and a3 link.
- 02/18: Updated class 7 and p2 links.

## Syllabus

[Syllabus](/_docs/robotics2-2026/syllabus.pdf)

## Classes

- 0113: Class 1 - ROS2 Installation

  - [ROS Jazzy Deb Packages Installation Guide](https://docs.ros.org/en/jazzy/Installation/Ubuntu-Install-Debs.html)
  - [ROS Environment Configuration](https://docs.ros.org/en/jazzy/Tutorials/Beginner-CLI-Tools/Configuring-ROS2-Environment.html)

- 0115: Class 2 - Serial Communication

  - [USB communication example](https://github.com/linzhangUCA/3421example-usb_communication)

- 0120: Class 3 - ROS2 Core Concepts

  - [Using `turtlesim`](https://docs.ros.org/en/jazzy/Tutorials/Beginner-CLI-Tools/Introducing-Turtlesim/Introducing-Turtlesim.html)
  - [Understanding Nodes](https://docs.ros.org/en/jazzy/Tutorials/Beginner-CLI-Tools/Understanding-ROS2-Nodes/Understanding-ROS2-Nodes.html)
  - [Understanding Topics](https://docs.ros.org/en/jazzy/Tutorials/Beginner-CLI-Tools/Understanding-ROS2-Topics/Understanding-ROS2-Topics.html)

- 0122: Class 4 - [Writing a simple publisher and subscriber (Python)](https://docs.ros.org/en/jazzy/Tutorials/Beginner-Client-Libraries/Writing-A-Simple-Py-Publisher-And-Subscriber.html)
  - [Minimal Publisher Example](https://github.com/ros2/examples/blob/jazzy/rclpy/topics/minimal_publisher/examples_rclpy_minimal_publisher/publisher_member_function.py)
  - [Minimal Subscriber Example](https://github.com/ros2/examples/blob/jazzy/rclpy/topics/minimal_subscriber/examples_rclpy_minimal_subscriber/subscriber_member_function.py)

- 0203: Class 5 - Managing ROS2 Packages
  - [Creating A Workspace](https://docs.ros.org/en/jazzy/Tutorials/Beginner-Client-Libraries/Creating-A-Workspace/Creating-A-Workspace.html)
  - [Creating A ROS2 Package](https://docs.ros.org/en/jazzy/Tutorials/Beginner-Client-Libraries/Creating-Your-First-ROS2-Package.html)
  - [Build Packages](https://docs.ros.org/en/jazzy/Tutorials/Beginner-Client-Libraries/Colcon-Tutorial.html)

- 0205: Class 6 - ROS2 Launch
  - [Launching Nodes](https://docs.ros.org/en/jazzy/Tutorials/Beginner-CLI-Tools/Launching-Multiple-Nodes/Launching-Multiple-Nodes.html)
  - [Launch Tutorials](https://docs.ros.org/en/jazzy/Tutorials/Intermediate/Launch/Launch-Main.html)

- 0217: Class 7 - Frame Transformations
  - [Introducing `tf2`](https://docs.ros.org/en/jazzy/Tutorials/Intermediate/Tf2/Introduction-To-Tf2.html)
  - [Proper way to publish static transforms](https://docs.ros.org/en/jazzy/Tutorials/Intermediate/Tf2/Writing-A-Tf2-Static-Broadcaster-Py.html#the-proper-way-to-publish-static-transforms)
  - [Writing a broadcaster](https://docs.ros.org/en/jazzy/Tutorials/Intermediate/Tf2/Writing-A-Tf2-Broadcaster-Py.html)

- 0219: Class 8 - Quaternion
  - [Quaternion and 3D Rotation Explained](https://www.youtube.com/watch?v=zjMuIxRvygQ)

- 0224: Class 9 - [LiDAR](/_docs/robotics2-2026/0224/lidar.pdf)

- 0226: Class 10 - IMU
  - [example code](https://github.com/linzhangUCA/homer_pico/blob/main/upython_scripts/perception/inertial_sensor.py)

- 0310: Class 11 - [Robotic Vision](/_docs/robotics2-2026/0310/vision.pdf)
  - [example code](https://github.com/linzhangUCA/homer_bringup/blob/main/homer_bringup/aruco_detector.py)

## Resources

- HomeR [documentation](https://linzhanguca.github.io/homer_docs).
- Read [The Linux command line for beginners](https://ubuntu.com/tutorials/command-line-for-beginners#1-overview) tutorial for basic usage of Linux commands.
- [ROS2 Cheat Sheet](https://github.com/ubuntu-robotics/ros2_cheats_sheet/blob/master/cli/cli_cheats_sheet.pdf)

## Assignments

1. [Chat with Pico](https://classroom.github.com/a/DDX-qQE9), **due: 03/01/26**
2. [Figure8 Turtle](https://classroom.github.com/a/a4Gqehwo), **due: 03/08/26**
3. [Figure8 HomeR](https://classroom.github.com/a/1dyzZm3y), **due: 03/29/26**
4. [ArUco Follower](https://classroom.github.com/a/zXXCue_b), **due: 05/1/26**

## Projects

1. [First ROS Package](https://classroom.github.com/a/Prk-OBLE). **Demo day: 02/12**
2. [ROS Rover](https://classroom.github.com/a/bB9iZ9df). **Demo due date: 03/19**
3. [The Odyssey](https://classroom.github.com/a/7KaPTW5f). **Demo day: 04/30**
