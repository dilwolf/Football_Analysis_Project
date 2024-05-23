# Football Analysis Project

## Abstract
This project leverages advanced AI and computer vision techniques to analyze football match footage. By employing YOLO for object detection, Kmeans for team categorization, optical flow for motion tracking, and perspective transformation for real-world measurement, we provide comprehensive insights into player movements, team strategies, and game dynamics. The project aims to offer a valuable tool for both novice and experienced machine learning engineers to enhance their understanding and application of these technologies in sports analytics.


## Results
![output_video](https://github.com/dilwolf/Football_Analysis_Project/assets/107533581/e16c5451-6f12-4e63-85e8-6a447661775f)

## Introduction
The aim of this project is to leverage advanced AI techniques to perform comprehensive analysis of football matches. By utilizing YOLO, a leading AI object detection model, we can accurately identify and track players, referees, and footballs within video footage. Our project focuses on enhancing the model's performance through meticulous training, ensuring high precision and reliability.

A key aspect of our analysis involves categorizing players into their respective teams. This is achieved by analyzing the colors of their shirts using Kmeans for pixel segmentation and clustering. By distinguishing team colors, we can calculate each team's ball possession percentage throughout the match, providing valuable insights into team performance and strategy.

To accurately track player movements, we employ optical flow to assess camera movement between frames. This allows us to maintain consistency in tracking even with dynamic camera motions. Furthermore, we implement perspective transformation techniques to depict the depth and perspective of the scene. This enables us to convert player movements from pixels to real-world measurements in meters, offering a more intuitive understanding of their positions and distances covered on the field.

By combining these techniques, we can determine each player's speed and the distance they cover during the match. This comprehensive analysis encompasses various concepts in machine learning and computer vision, addressing real-world problems and providing a valuable tool for both novice and experienced machine learning engineers.


## Modules Used
The following modules are used in this project:
- **YOLO (You Only Look Once):** AI object detection model used to identify and track players, referees, and footballs in video footage.
- **Kmeans Clustering:** Pixel segmentation and clustering technique used to detect and categorize t-shirt colors, facilitating team identification.
- **Optical Flow:** Technique used to measure camera movement between frames, ensuring accurate player tracking despite dynamic camera angles.
- **Perspective Transformation:** Technique used to represent scene depth and perspective, converting pixel measurements to real-world distances in meters.
- **Player Speed and Distance Calculation:** Algorithms to determine the speed and distance covered by each player during the match, providing detailed performance metrics.



## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas
