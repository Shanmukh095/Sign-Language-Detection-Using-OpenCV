Hand Gesture Recognition using MediaPipe
📌 Overview

This project implements a real-time Hand Gesture Recognition System using MediaPipe and OpenCV.
It detects hand landmarks from live webcam feed, extracts 3D keypoints (x, y, z), and prepares structured sequence data for gesture classification.

The system is designed for gesture-based interaction and can be extended to deep learning models like LSTM for dynamic gesture recognition.

🚀 Features

Real-time hand detection using MediaPipe Hands

Extraction of 21 hand landmarks (x, y, z coordinates)

Keypoint preprocessing and flattening for ML model input

Structured dataset generation (Sequences × Frames format)

Landmark visualization using OpenCV

Easily extendable for gesture classification using deep learning

🛠️ Tech Stack

Python

OpenCV

MediaPipe

NumPy