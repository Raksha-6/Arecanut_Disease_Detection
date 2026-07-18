# Arecanut Disease Detection using YOLOv8

This project is a part of our major project Phase 1. The aim is to detect Koleroga (fruit rot) disease in arecanut plantations using the YOLOv8 object detection model. The detected diseased area is then used to find the centroid, which can later help an autonomous drone spray pesticide only on the affected region.

## What we did
- Collected and annotated the dataset using Roboflow.
- Trained a custom YOLOv8 model on Google Colab.
- Performed real-time disease detection.
- Calculated centroid coordinates for precise targeting.
- Tested the model using images and live webcam feed.

## Tools Used
- Python
- YOLOv8
- Roboflow
- OpenCV
- Google Colab
- Visual Studio Code

## Files
- `Arecanut_Disease_Detection.ipynb` - Google Colab training notebook
- `Phase1_Presentation.pdf` - Phase 1 presentation
- `Demo_Video.mp4` - Project demonstration

## Note
This repository contains the Phase 1 work of our major project. Hardware integration with the drone, Raspberry Pi, Pixhawk and ROS will be carried out in the next phase.
