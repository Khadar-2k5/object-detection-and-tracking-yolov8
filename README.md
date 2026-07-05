# Object Detection and Tracking using YOLOv8

A real-time Object Detection and Tracking system developed using **Python**, **OpenCV**, **Ultralytics YOLOv8**, and **ByteTrack**. The application captures live webcam video, detects multiple objects, assigns unique tracking IDs, and displays the processed video in real time.

This project was developed as part of **CodeAlpha – Task 4: Object Detection and Tracking**.

---

## Features

* Real-time webcam video capture
* Object detection using the pre-trained YOLOv8 Nano model
* Real-time multi-object tracking using ByteTrack
* Bounding boxes for detected objects
* Object class labels
* Confidence score display
* Persistent tracking IDs
* Live visualization with OpenCV

---

## Technologies Used

* Python 3.x
* OpenCV
* Ultralytics YOLOv8
* ByteTrack
* NumPy

---

## Project Structure

```text
Object-Detection-and-Tracking/
│
├── models/
├── output/
├── videos/
├── src/
│   ├── webcam_test.py
│   ├── object_detection.py
│   └── object_tracking.py
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
```

---

## Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/Object-Detection-and-Tracking.git
```

### Navigate to the project

```bash
cd Object-Detection-and-Tracking
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## Usage

### Test Webcam

```bash
python src/webcam_test.py
```

### Run Object Detection

```bash
python src/object_detection.py
```

### Run Object Detection with Tracking

```bash
python src/object_tracking.py
```

---

## Sample Output

The application displays:

* Live webcam feed
* Bounding boxes around detected objects
* Object names
* Confidence scores
* Tracking IDs that remain consistent while objects are visible

---

## Applications

* Smart Surveillance Systems
* Security Monitoring
* Traffic Monitoring
* Retail Analytics
* Smart Parking
* Crowd Monitoring
* Robotics
* Computer Vision Research

---

## Future Improvements

* Video file input
* Save processed output videos
* FPS counter
* Person counting
* Restricted zone monitoring
* Crowd density analysis
* Event logging
* Screenshot capture
* Smart surveillance dashboard

---


---

## Author

**Khadar Masthan SK**

B.Tech Information Technology

SASTRA Deemed University
