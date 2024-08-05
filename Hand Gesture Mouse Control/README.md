Hand Gesture Controlled Mouse

Project Description
A Python application that uses hand gestures to control the mouse cursor. This project leverages OpenCV and Mediapipe for real-time hand tracking and PyAutoGUI for simulating mouse movements and clicks.

Table of Contents

1. Introduction
2. Technologies Used
3. Requirements
4. Installation Instructions
5. Usage Instructions
6. Features
7. Documentation
8. Visuals
9. Conclusion

Introduction
This project demonstrates how to control the mouse cursor using hand gestures. The application captures video from the webcam, detects hand landmarks, and maps these landmarks to mouse movements. A click action is triggered when the thumb and index finger come close together.

Technologies Used
Python
OpenCV
Mediapipe
PyAutoGUI

Requirements
Python 3.7+
OpenCV
Mediapipe
PyAutoGUI

Installation Instructions

1. Clone the repository:
git clone https://github.com/SamratChanda26/Computer-Vision.git
cd Hand-Gesture-Mouse-Control

2. Create a virtual environment and activate it:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. Install the required packages:
pip install opencv-python mediapipe pyautogui

Usage Instructions

1. Run the script:
python hand_gesture_mouse_control.py

2. Ensure your webcam is connected and accessible.
3. The application will open a window showing the video capture.
4. Use your hand to control the mouse cursor. Moving your index finger will move the cursor, and bringing your thumb and index finger together will perform a click.

Features
Real-time hand tracking
Mouse cursor control using hand gestures
Simulated mouse click when thumb and index finger are close

Documentation
cv2: OpenCV library for image and video processing.
mediapipe: Library for real-time face, hand, and body pose detection.
pyautogui: Module for programmatically controlling the mouse and keyboard.

Conclusion
This project provides a basic yet powerful example of how computer vision and gesture recognition can be applied to human-computer interaction. Further enhancements could include adding more gestures for additional mouse actions and improving the accuracy of hand tracking.