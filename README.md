# YOLOv8 and GroundingDINO for Real Time License Plate Detection

This repository contains the code for a system that can automatically extract license plates from video footage. The system uses a combination of YoloV8 and GroundingDINO to achieve this goal.

## Objective

The objective of this project is to develop a system that can automatically extract license plates from video footage. The system will use a combination of YoloV8 and GroundingDINO to achieve this goal.

## Abstract

This paper presents a novel approach to license plate extraction from video footage. The proposed system uses a combination of YoloV8 and GroundingDINO to achieve this goal. YoloV8 is used to extract images of vehicles from the footage, and GroundingDINO is used to extract the section of the image that contains the license plate. The system was evaluated on a dataset of video footage, and it was shown to be able to extract license plates with high accuracy.

## Methodology

The proposed system consists of two main components:

* YoloV8: YoloV8 is a deep learning object detection model that can be used to identify objects in images and video. YoloV8 was trained on a dataset of images that contain vehicles.
* GroundingDINO: GroundingDINO is a deep learning model that can be used to extract regions of interest from images. GroundingDINO was trained on a dataset of images that contain license plates.

The proposed system works as follows:

1. YoloV8 is used to identify vehicles in the video footage.
2. The identified vehicles are then passed to GroundingDINO, which extracts the region of the image that contains the license plate.
3. The extracted license plates are then stored in a folder.

## Project Architecture:
![image](https://github.com/Marinto-Richee/YOLOv8-and-GroundingDINO-for-Real-Time-License-Plate-Detection/assets/65499285/253a402d-a3a9-4875-8c1d-9fcaf2f054f0)

![Project Architecture](https://github.com/Marinto-Richee/YOLOv8-and-GroundingDINO-for-License-Plate-Extraction-from-Video-Footage/assets/65499285/e67bde3e-632c-4fb5-87fc-5d74bfe76542)

### YoloV8 output and GroundingDINO output:

| YoloV8 output | GroundingDINO output |
| --- | --- |
| ![YoloV8 output](https://github.com/Marinto-Richee/YOLOv8-and-GroundingDINO-for-License-Plate-Extraction-from-Video-Footage/assets/65499285/06baf60a-59ee-4c4e-a829-04fb25635905) | ![GroundingDINO output](https://github.com/Marinto-Richee/YOLOv8-and-GroundingDINO-for-License-Plate-Extraction-from-Video-Footage/assets/65499285/289c9bc5-1dcd-41a0-a720-278adda4cb39) |


## Results

The proposed system was evaluated on a dataset of video footage. The system was shown to be able to extract license plates with high accuracy. The system was able to extract license plates from a variety of video footage.

## Conclusion

The proposed system is a significant improvement over existing methods for license plate extraction. The system is more accurate and can be used to extract license plates from a wider variety of video footage. The proposed system is still under development, but it has the potential to be a valuable tool for a variety of applications.

## Requirements

* Python 3.7
* PyTorch
* YoloV8
* GroundingDINO

To try this implementation, clone this repository and change the directory in the 'Vehicle_detection.py' file with the path to your video footage. 
