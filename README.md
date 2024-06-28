# Full body detection 
 # Overview
This project demonstrates how to perform full body detection in a video using OpenCV, a popular computer vision library. The method employed here utilizes Haar Cascades, which are effective for detecting objects in images or video frames.

# Requirements
Python (3.5+ recommended)
OpenCV library (opencv-python)
Pre-trained Haar Cascade XML file for full body detection
# Installation
Install OpenCV:
Copy code
pip install opencv-python
# How it Works
Haar Cascade Classifier:
Haar Cascade is a machine learning-based approach where a cascade function is trained from a lot of positive and negative images to detect objects. In this case, we use a pre-trained Haar Cascade XML file specifically trained for full body detection.

# Video Processing:

The video is processed frame by frame.
Each frame is converted to grayscale to reduce computational load and facilitate easier detection.
The Haar Cascade classifier is applied to each frame to detect full bodies.
Drawing Detected Bodies:

Detected bodies are outlined with rectangles on the original frame.
Optionally, you can perform additional actions such as displaying the frame with detections or saving the processed video. 

RUN in VS code: RUN without Debugging
