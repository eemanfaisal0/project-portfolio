
# Socially Aware Navigation Robot

## Project Overview
Developed a socially aware robotic navigation system that combines YOLOv7-based human detection with LiDAR-based obstacle avoidance. The system differentiates between pedestrians and other obstacles to support safer, more context-aware robot navigation.

## Technologies Used
- Python
- YOLOv7 (Computer Vision)
- ROS (Robot Operating System)
- Jetson Nano
- DJI RoboMaster
- RPLidar A2M12
- Dynamic Window Approach (DWA)
- Google Gemini (Vision-Language Model Evaluation)

## Key Features and Contributions
- Developed a YOLOv7-based human detection pipeline to identify pedestrians using camera input.
- Converted detected bounding-box coordinates into angular positions to support navigation decisions.
- Implemented a Dynamic Window Approach (DWA) local planner in Python, integrating LiDAR obstacle detection through ROS with computer vision outputs.
- Designed differentiated obstacle-avoidance behavior for human and non-human obstacles.
- Evaluated Google's Gemini vision-language model for pedestrian-intent recognition.
- Identified inference latency and hardware limitations on edge devices and adopted a more computationally efficient weighted-cost DWA approach.

## Technical Approach
The system combines camera-based human detection and LiDAR-based obstacle sensing to inform a local navigation planner. YOLOv7 identifies pedestrians, while LiDAR provides obstacle information. A weighted-cost DWA planner uses these inputs to select navigation behavior that accounts for the presence of humans.

## Project Report
The complete project report is available in this folder, covering the system design, implementation, and evaluation.

## Source Code
Source code will be added when available.
  
