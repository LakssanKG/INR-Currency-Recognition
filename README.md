#Overview
This is a deep learning project that detects Indian currency denominations from images using a Convolutional Neural Network (CNN) and spells the detected denomination through audio output.
This project is designed to assist visually impaired individuals and also to provide an automated way of recognizing Indian currency notes.

#Features
Detects Indian currency notes (e.g., ₹10, ₹20, ₹50, ₹100, ₹200, ₹500, ₹2000).

Uses a trained CNN model for classification.

Provides audio feedback of the detected denomination.

Lightweight and easy to deploy.

#Tech Stack
Python 3

TensorFlow 

OpenCV (for image preprocessing)

Pyttsx3 (for text-to-speech conversion)

NumPy

Matplotlib (for visualization)

#How It Works
Image Input: Capture or upload an image of the Indian currency note.

Preprocessing: Resize, normalize, and prepare the image for the CNN.

Prediction: The CNN model classifies the note into one of the known denominations.

Audio Output: The predicted denomination is converted into speech and played aloud.
