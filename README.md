# Real-Time Face Detection Application using C++ and OpenCV

This project implements a real-time face detection application using C++ and OpenCV's Haar Cascade classifier. The application captures video input from the webcam, processes each frame, and detects faces in real time.

## Features

- **Real-Time Face Detection:** The application uses the `VideoCapture` class to capture live video from the webcam and processes each frame to detect faces.
  
- **Visual Feedback:** Detected faces are highlighted by drawing bounding boxes around them. Customizable rectangle colors are used to emphasize the detected faces.
  
- **Face Count Overlay:** An overlay with transparent background displays the count of detected faces in each frame. This provides users with real-time information about the number of faces detected.

- **Interactive User Interface:** The application employs OpenCV's functions for window display (`imshow`) and keyboard input handling (`waitKey`). This ensures a responsive and interactive user experience.

## How to Use

1. Clone this repository to your local machine.
2. Make sure you have OpenCV installed.
3. Compile the source code using a C++ compiler.
