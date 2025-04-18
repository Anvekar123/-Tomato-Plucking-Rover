#  Tomato Plucking Rover
## Overview
This project presents a robotic system capable of identifying and harvesting tomatoes using advanced computer vision techniques and robotic control. By leveraging the YOLO object detection algorithm, real-time image processing, and precise robotic arm movements, this system aims to improve agricultural automation and efficiency.

## Features
Vision-Based Detection: Identifies ripe tomatoes using the YOLO object detection model.

Robotic Arm Control: Utilizes servo motors for precise and smooth movements.

Pixel-to-Centimeter Calibration: Ensures accurate positional mapping for robotic arm control.

Real-Time Feedback: Provides continuous updates during operation for seamless automation.

Applications: Can be adapted for various agricultural, industrial, and logistical scenarios.

## System Components
Hardware
Camera: High-resolution RGB or depth camera for image capture.

Robotic Arm: Servo motor-driven arm with grippers for picking and placing tomatoes.

Microcontroller: Arduino UNO for controlling robotic arm movements.

Power Supply: Provides adequate power for all components.

## Software
YOLO (You Only Look Once): Object detection algorithm for tomato identification.

OpenCV: Library for image processing and visualization.

Arduino IDE: For microcontroller programming and control logic.

Python: For integrating computer vision and control systems.

## System Workflow
Image Capture:A camera captures real-time video of the target area.

Tomato Detection: The YOLO model processes the video feed to identify ripe tomatoes.

Coordinate Calculation: The position of the tomato is mapped to the robotic arm's workspace.

Robotic Arm Control: Commands are sent to the robotic arm to pick and place the tomato in a predefined location.

Cycle Reset: The arm resets to its initial position and repeats the process.

![WhatsApp Image 2024-12-17 at 7 42 08 PM](https://github.com/user-attachments/assets/09c2b9a5-a32e-4159-9c33-1dbc94eff0c0)

![WhatsApp Image 2024-12-17 at 10 40 27 PM](https://github.com/user-attachments/assets/54edeb53-1120-482b-9082-95347a3fa14f)

https://github.com/user-attachments/assets/640560c8-3db8-4ce3-9f55-cd7e4487f101









