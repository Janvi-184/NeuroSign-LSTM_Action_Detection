# NeuroSign-LSTM_Action_Detection

## Overview
This project focuses on action detection using Mediapipe for extracting keypoints and an LSTM (Long Short-Term Memory) neural network for classifying actions in real-time.

## Features
* Uses Mediapipe Holistic to extract keypoints from the face, hands, and body.
* Collects training data for different actions.
* Preprocesses data and creates features and labels.
* Builds and trains an LSTM neural network using TensorFlow/Keras.
* Tests the model in real-time using OpenCV.

## Technologies Used
* Python
* OpenCV - For real-time video processing
* Mediapipe - For keypoint detection
* NumPy & Pandas - Data processing
* TensorFlow/Keras - Model training
* Matplotlib - Visualization

## Project Workflow
1. Import Libraries
2. Setup Folders for dataset collection.
3. Collect Keypoints using Mediapipe.
4. Preprocess Data and prepare features/labels.
5. Train an LSTM Model using TensorFlow.
6. Test the Model on real-time video input.

## Results
* The model successfully classifies predefined actions with high accuracy.
* Real-time predictions using a webcam are smooth and efficient.
