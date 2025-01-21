# Gun-Detection
The Gun Detection Project is a real-time firearm detection system developed using Python and OpenCV. This project leverages Haar cascade classifiers to detect firearms in a live webcam feed and highlights them with bounding boxes. It's a proof-of-concept application that demonstrates the potential of computer vision for enhancing security .
# Gun Detection Project

This project implements a real-time gun detection system using OpenCV, Haar cascades, and Python. The system uses a webcam to detect firearms in a live video feed and highlights them with bounding boxes.

## Features
- Real-time gun detection using a pre-trained Haar cascade classifier.
- Highlights detected guns with a bounding box.
- Displays a timestamp on the video feed.
- Captures the detection frame for review.

## Requirements
Make sure you have the following installed:
- Python 3.x
- OpenCV
- Imutils
- Matplotlib
- A Haar cascade file for weapon detection (e.g., `Weapon_cascade.xml`).

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gun-detection-project.git
   cd gun-detection-project
