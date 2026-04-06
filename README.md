# Autonomous-vision-robot
Autonomous terrain aware robot using Raspberry Pi and sensor fusion

# Vision-Based Autonomous Robotic System (Webots + YOLO)

## Overview
This project implements an autonomous robotic system using Webots simulation integrated with computer vision (YOLOv8) for real time object detection and intelligent navigation.

The system demonstrates a Vision-Language-Action (VLA) approach where visual input is processed to generate decisions and control robot movement.

## Problem Statement

Autonomous navigation in dynamic environments remains a challenging problem due to the need for real-time perception, decision-making, and control.

Traditional robotic systems rely heavily on predefined rules or simple sensor-based navigation, which limits their ability to understand complex surroundings and react intelligently to different objects.

This project aims to develop a vision-based autonomous robotic system that can:
- Perceive its environment using camera input
- Detect and classify objects in real-time using deep learning (YOLO)
- Make intelligent navigation decisions based on visual data
- Integrate perception with control for autonomous movement

The goal is to bridge the gap between perception (vision), decision-making (logic), and action (robot control) in a unified system.

## Key Features
- Real-time object detection using YOLOv8
- Autonomous and manual control modes
- Camera-based environment perception
- Obstacle aware navigation
- Hybrid control system (manual + AI)


## System Architecture
The robot captures real-time images through a camera sensor. These images are processed using a YOLO model to detect objects.

Based on detection results and environmental conditions, the system decides movement actions and controls motors accordingly.


## Technologies Used
- Python
- Webots Simulator
- OpenCV
- YOLO (Ultralytics)
- Embedded control logic


## Components
- Pioneer 3-AT robot (simulation)
- Camera sensor
- Motor control system
- Keyboard interface (manual mode)


## Working
1. Camera captures real-time frames
2. Frames are processed using YOLO for object detection
3. Detected objects influence navigation decisions
4. Robot switches between manual and autonomous modes
5. Motor velocities are updated accordingly


## Future Improvements
- Deploy the system on a real-world rover using Raspberry Pi or embedded microcontrollers for hardware validation  
- Integrate SLAM (Simultaneous Localization and Mapping) for real-time environment mapping and navigation  
- Enhance path planning using advanced algorithms for optimal and efficient movement  
- Implement edge AI optimization for faster real-time inference on low-power devices  
- Extend the system for autonomous exploration in challenging environments such as space rovers or planetary missions  
- Integrate multi-sensor fusion (LiDAR, ultrasonic, IMU) for improved perception accuracy  
- Enable remote monitoring and control using IoT and cloud-based dashboards  
- Adapt the system for applications in search & rescue, surveillance, and industrial automation  


## Key Learning Outcomes
- Integration of AI with robotics systems
- Real-time decision-making using vision data
- Embedded control logic for autonomous navigation
- Simulation-to-real-world system design thinking
