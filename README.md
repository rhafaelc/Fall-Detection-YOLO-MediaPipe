# Elderly Fall Detection using YOLOv8 and MediaPipe

This project was developed as part of a Computer Vision class, aiming to detect falls in elderly individuals to reduce the risk of severe injuries. By leveraging YOLOv8 for object detection and MediaPipe for pose estimation, the system can classify postures as standing, falling, or lying down, and issue alerts for fall incidents.

## Project Overview

The primary goal of this project is to create a reliable system for detecting falls using video data. The system is designed to improve response times to fall incidents, thereby helping to minimize injury impacts among elderly individuals.

### Key Features

- **Data Preprocessing**: The dataset includes video clips of simulated falls captured from multiple camera angles. Only specific clips and angles are used for the experiments in this project.
- **Human Detection**: YOLOv8 is employed to accurately detect humans within the video frames, providing bounding boxes for further analysis.
- **Pose Estimation**: MediaPipe is utilized to estimate human poses by identifying key points on the body, focusing on the shoulders and hips to determine body angles.
- **Posture Classification**: Based on the calculated body angles, the system classifies the posture into three categories: standing, falling, or lying down.
- **Alert System**: The system issues an alert by displaying "FALL DETECTED" on the video frame when a fall is detected within a specified time threshold.
