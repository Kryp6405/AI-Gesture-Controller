# Gesture Control System for Computer Interactions (v1.0)

## Overview
This project introduces a gesture control system that allows users to interact with their computers through simple hand gestures. Utilizing advanced computer vision techniques and machine learning, the system interprets specific hand gestures captured via webcam to perform actions such as adjusting system volume and screen brightness. Version 1.0 supports four distinct gestures:
- **Thumbs Up**: Increase brightness
- **Thumbs Down**: Decrease brightness
- **Index Finger Up**: Increase volume
- **Index Finger Down**: Decrease volume

## Dataset
The model was trained using a dataset comprising 2000 training images and 700 validation images. These images include diverse representations of the four gestures under different conditions to ensure robust recognition.

## Technology Stack
- **Data Collection**: OpenCV2
- **Data Augmentation**: Keras Image Processing
- **Model**: Transfer Learning with MobileNetV2
- **Gestures Classification**: Deep Learning Model to classify one of the four gestures

## Model Performance
The trained model achieved an impressive training accuracy of 95% and a validation accuracy of 82%.

## How to Use
'''bash
git clone https://github.com/Kryp6405/dog-breed-classification.git
'''

