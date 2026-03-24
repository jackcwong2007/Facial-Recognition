# Facial-Recognition

This script uses OpenCV, dlib, and imutils to perform real-time face detection and facial landmark tracking from a webcam feed. It starts by loading a pre-trained facial landmark predictor, then continuously captures video frames, converts them to grayscale, and detects faces in each frame. For every detected face, it draws a bounding box and overlays 68 facial landmark points (such as eyes, nose, and mouth), labeling each point with its index. The processed video is displayed live, and the program runs until the user presses the “q” key to exit.

A short demo can be found [here](https://youtu.be/ZJ9yiFgNTQg)
