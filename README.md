# Face-Angle-Detection
This project uses OpenCV and dlib to detect faces in real-time from a webcam feed, calculate the angle of the face based on key landmarks, and label the face with the detected angle. It confirms if it's a human face based on the detection and angles.

Face Angle Detection
This project is a real-time face detection and angle estimation system using OpenCV and dlib. The system captures video from a webcam, detects faces, and calculates the angle of the face based on key facial landmarks. It then labels the face with the detected angle and confirms if it's a human face based on the detection and angles.

Features
Real-time Face Detection: Uses dlib's pre-trained face detector to identify faces in the video feed.
Facial Landmark Prediction: Utilizes dlib's shape predictor to detect 68 facial landmarks.
Angle Calculation: Computes the angle between the eyes and nose to determine the orientation of the face.
Labeling: Labels the detected face with the calculated angle and a message indicating whether a human face is detected or if the face is angled.
Webcam Integration: Captures video from the webcam and processes each frame in real-time.

How It Works
Face Detection: The system converts each frame to grayscale and uses dlib's face detector to find faces.
Landmark Prediction: For each detected face, the system predicts 68 facial landmarks.
Angle Calculation: The system calculates the angle between the eyes and nose using the predicted landmarks.
Labeling: The system labels the face with the detected angle and a message indicating whether a human face is detected or if the face is angled.
Display: The processed frame is displayed with the labels.

Requirements
Python 3.x
OpenCV
dlib
numpy

Installation
Install the required packages:
Download the shape_predictor_68_face_landmarks.dat file from the dlib repository and extract it into the project directory.

Usage
Run the script to start the webcam feed and detect face angles:

License
This project is licensed under the MIT License. See the LICENSE file for details.
