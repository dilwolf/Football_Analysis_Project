# Football Analysis Project

## Introduction
The aim of this project is to use YOLO, a leading AI object detection model, to identify and track players, referees, and footballs in video footage. We will enhance the model's performance through training. Additionally, we will categorize players into teams by analyzing the colors of their shirts using Kmeans for pixel segmentation and clustering. This will allow us to calculate each team's ball possession percentage during a match. To accurately track player movement, we will utilize optical flow to assess camera movement between frames. Moreover, we will apply perspective transformation to depict the scene's depth and perspective, enabling us to measure player movements in meters instead of pixels. Finally, we will determine a player's speed and the distance they cover. This project encompasses various concepts and solves real-world problems, making it suitable for both novice and experienced machine learning engineers.

![Sample](result_video.avi)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
- [Trained Yolo v5]()

## Sample video
-  [Sample input video]()

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas
