Facial Expression Recognition with OpenCV and Keras

This repository contains code for a real-time facial expression recognition system using OpenCV and Keras. The system detects faces in a video stream, predicts the emotions of the detected faces, and overlays the predicted emotion label on the video frames.

Introduction

This project demonstrates the implementation of a real-time facial expression recognition system using OpenCV and Keras. The system utilizes a pre-trained convolutional neural network (CNN) to classify facial expressions such as happiness, sadness, anger, etc.

Prerequisites

Before you begin, ensure you have met the following requirements:

Python 3.6 or higher is installed.

Required libraries are installed. You can install them using pip:
pip install opencv-python numpy flask


Getting Started

To get started with this project, follow these steps:
1.Clone the repository:
git clone https://github.com/your-username/your-repo.git
cd your-repo

2.Download the required model weights and haarcascade XML file:

Download the model weights from the Coursera course materials and place them in the repository root.
Download the haarcascade XML file from the Coursera course materials and place it in the repository root.

3.Run the Flask app:
python app.py

4.Open a web browser and go to http://localhost:5000 to see the real-time facial expression recognition in action.

Project Structure

app.py: The main Flask application that serves the video stream and handles web requests.
model.py: Defines the FacialExpressionModel class for loading the Keras model and making predictions.
camera.py: Contains the VideoCamera class responsible for capturing frames from the webcam and performing facial expression recognition.
static/ and templates/: Directories containing static assets (CSS, images) and HTML templates for the web app.
Usage

The main page at / displays the real-time video stream with predicted emotion labels overlaid on detected faces.
You can access the video stream at /video_feed.
