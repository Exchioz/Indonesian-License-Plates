# Indonesian License Plates Recognition System
This repository contains the machine learning models and scripts used in the Smart Parking Gate project for recognizing Indonesian vehicle license plates. It leverages advanced detection algorithms and deep learning models to accurately identify and process license plates from images captured by the system's cameras.

## Overview
The Indonesian License Plates Recognition System is designed to support an automated parking management system by identifying vehicles through their license plates. This system uses machine learning models to detect and recognize license plates in real-time, helping to automate gate operations and ensure security in parking areas.

## Features
- **Real-Time Detection**: Utilizes the YOLO (You Only Look Once) model for fast and accurate license plate detection.
- **Character Recognition**: The system enhances character visibility by converting images to binary format, which sharpens the contrast between the characters and their backgrounds.
- **Contour Detection**: Employs sophisticated algorithms to identify and isolate individual characters based on their geometric shapes and outlines. This step is crucial for accurate character extraction before recognition.
- **CNN-Based Recognition**: Implements a TensorFlow-based Convolutional Neural Network (CNN) for precise recognition of characters on the plates.

## Requirements
- Python 3.7+
- Libraries: TensorFlow, numpy, OpenCV
- Hardware: Suitable for running deep learning models (GPU recommended for training)

## Instalation
1. Clone this repository
```bash
git clone https://github.com/Exchioz Indonesian-License-Plates.git
```
2. Install required Python libraries
```bash
pip install -r requirements.txt
```
