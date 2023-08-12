# Facial Expression Recognition with OpenCV and Keras

This project implements real-time facial expression recognition using OpenCV and Keras. It detects faces in a video stream and predicts the emotion associated with each detected face.

## Features

- Detects faces using the Haarcascade Frontal Face Classifier.
- Utilizes a pre-trained model for emotion recognition.
- Provides real-time video streaming with emotion predictions.

## Usage
1.Make sure you have a webcam connected to your system.
2.Run the Flask app:
'python app.py'
3.Open a web browser and navigate to http://localhost:5000 to see the live video stream with emotion predictions.


## Files
- app.py: Flask web application that serves the video stream and processes frames for emotion recognition.
- camera.py: Defines the VideoCamera class responsible for capturing frames from the webcam.
- model.py: Contains the FacialExpressionModel class for loading the pre-trained emotion recognition model.
- haarcascade_frontalface_default.xml: Haarcascade Frontal Face Classifier for face detection.
- model_weights.h5: Pre-trained model weights for emotion recognition.
- index.html: HTML template for the web interface.
- README.md: You are currently reading this file.
