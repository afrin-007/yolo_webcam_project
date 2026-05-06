# YOLO Webcam Object Detection System

A real-time object detection system built using **YOLOv5** and **OpenCV** for detecting multiple objects through webcam, image, and video input.

---

## Overview

This project uses the **YOLO (You Only Look Once)** object detection algorithm to perform fast and efficient real-time detection on live webcam streams and media files.

---

## Features

* Real-time webcam object detection
* Supports image and video file input
* Bounding box visualization with confidence scores
* Multiple object class detection
* Fast inference using YOLOv5

---

## Tech Stack

* Python
* YOLOv5
* PyTorch
* OpenCV

---

## Project Structure

```plaintext
yolo_camera_project/
│── yolov5/
│── runs/
│── detect.py
│── train.py
│── requirements.txt
│── README.md
```

---

## Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/yolo-camera-project.git
cd yolo-camera-project
```

2. Create and activate virtual environment

```bash
python -m venv venv
venv\Scripts\activate
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## Usage

### Webcam Detection

```bash
python detect.py --weights yolov5s.pt --source 0
```

### Image Detection

```bash
python detect.py --weights yolov5s.pt --source image.jpg
```

### Video Detection

```bash
python detect.py --weights yolov5s.pt --source video.mp4
```

---

## Output

* Detected objects highlighted with bounding boxes
* Confidence scores displayed for each detection
* Results saved in the `runs/` directory

---

## Future Improvements

* Deploy as a web application
* Add object tracking functionality
* Train on custom datasets
* Integrate with mobile applications

---

## Author

**AFRIN A**

---

## Support

If you found this project useful, consider giving it a star on GitHub.

<img width="1910" height="1078" alt="image" src="https://github.com/user-attachments/assets/b48f1f89-3689-4cdc-831d-85de2d7aa289" />

