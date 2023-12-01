# Autonomous Driving Car Object Detection using YOLO
GOAL: To implement car detection for autonomous driving using the very powerful YOLO model
![output](https://github.com/LateefAkinola/Autonomous-Driving-Car-Detection-using-YOLO-algorithm/assets/105966848/80e18d96-7786-4c75-a430-bad43ad79254)

## Self-Driving Car Object Detection using YOLO

### Overview
As part of a self-driving car project, the focus is on developing a robust car detection system. The data collection process involves mounting a camera to the front of the car, capturing periodic images of the road during driving sessions.

### Data Representation
For the task of recognizing 80 different classes in the object detection system, class labels ($c$) can be represented either as integers ranging from 1 to 80 or as an 80-dimensional vector. In the vector representation, one component is set to 1 to indicate the class, while the remaining elements are set to 0.

### Approach
This project explores the implementation of YOLO (You Only Look Once) for object detection, specifically applying it to the domain of car detection. YOLO is chosen for its efficiency and effectiveness, particularly in scenarios where computational resources for training are limited. The model utilizes pre-trained weights to streamline the object detection process.
