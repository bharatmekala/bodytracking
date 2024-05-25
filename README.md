# Pose, Face, and Hand Tracking Project

## Description

This project provides three Python scripts for tracking full body poses, faces, and hands using computer vision techniques. These scripts utilize various libraries to process video input and detect specific body parts or features.

## Files

- `track_full_body.py`: Tracks full body poses.
- `track_face.py`: Tracks facial features.
- `track_hands.py`: Tracks hand movements.

## Installation


```bash
pip3 install opencv-python 
pip3 install mediapipe
pip3 install cvzone
```

## Usage

 - In each file set the ```cap = cv2.VideoCapture(1)``` to the approrite camera, 0 - webcam, 1 - iphone cam
 - then run the files a new window will pop up showing you and the selected mesh
 - To track certain points on the body use the guides below

## Guide

 - Face Mesh
   index into face[] (example shown on line 34/35
   

