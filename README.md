# Simple Face Recognition System using OpenCV

This project is a basic real-time face recognition system built using Python and OpenCV. It uses Haar Cascade for face detection and a simple pixel-based difference method for recognition.

## Features

- Detects faces in real-time from webcam feed.
- Recognizes previously saved faces based on pixel difference.
- Allows saving new faces with a custom name.
- Stores and loads known faces using `pickle`.

## Requirements

- Python 3.x
- OpenCV (`cv2`)
- NumPy (optional, for better performance)
- Webcam

## Installation

1. Clone this repository or download the `.py` file.

```bash
git clone https://github.com/yourusername/face-recognition-opencv.git
cd face-recognition-opencv
