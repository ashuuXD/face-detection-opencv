# Real-Time Face Detection using OpenCV

## Project Overview

This project demonstrates a real-time face detection system using Computer Vision techniques. It uses OpenCV's pre-trained Haar Cascade classifier to detect human faces from a live webcam feed and draw bounding boxes around them.

The system is lightweight, efficient, and works in real time, making it suitable for basic surveillance and vision-based applications.

---

## Objective

The objective of this project is to implement a real-time face detection model using OpenCV and understand fundamental concepts of image processing and object detection.

---

## Technologies Used

* Python 3.x
* OpenCV (cv2)

---

## System Requirements

* OS: Windows/Linux/Mac
* Python >= 3.6
* Webcam (internal/external)

---

## Installation Steps

1. Clone the repository:

```
git clone https://github.com/ashuuXD/face-detection-opencv
cd face-detection-opencv
```

2. Install required dependencies:

```
pip install -r requirements.txt
```

---

## How to Run the Project

Run the following command in terminal:

```
python main.py
```

* Webcam will open automatically
* Faces will be detected and highlighted
* Press `ESC` to exit

---

## Methodology

1. Capture video stream using webcam
2. Convert each frame to grayscale
3. Apply Haar Cascade classifier
4. Detect faces
5. Draw rectangles around detected faces
6. Display output in real time

---

## Features

* Real-time face detection
* Lightweight and fast
* Easy to understand implementation
* Works with live webcam

---

## Limitations

* Poor performance in low lighting
* Less accurate than deep learning models
* Difficulty detecting tilted faces

---

## Future Improvements

* Use deep learning models (CNN, YOLO)
* Add face recognition
* Improve accuracy
* Build GUI interface

---

## Project Structure

```
face-detection-opencv/
│── main.py
│── requirements.txt
│── README.md
│── report.pdf
```

---

## Output

The system detects faces in real time and draws bounding boxes around them.

---

## Conclusion

This project provides a basic yet effective implementation of face detection using OpenCV and demonstrates how computer vision can be applied in real-world scenarios.
