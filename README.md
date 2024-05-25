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
   link to image showing what index is what point: https://storage.googleapis.com/mediapipe-assets/documentation/mediapipe_face_landmark_fullsize.png

- Hand Mesh
  index into lmList1[]/lmList2[]
  link to image showing what index is what points: https://ai.google.dev/static/edge/mediapipe/images/solutions/hand-landmarks.png

- Pose Mesh
  index into lmList[]\
  link to image showing what index is what: https://ai.google.dev/edge/mediapipe/solutions/vision/pose_landmarker

