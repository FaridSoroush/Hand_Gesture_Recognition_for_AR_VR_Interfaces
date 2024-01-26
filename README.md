# Gesture Recognition Using TensorFlow and OpenCV

## Overview
This repository contains the code and documentation for a gesture recognition project developed using TensorFlow and OpenCV. The project aims to accurately identify hand gestures from static images, focusing on the classic gestures of rock, paper, and scissors. This application is a stepping stone towards more complex gesture recognition tasks in AR/VR environments.

## Features
- **Model Training:** Utilizes the TensorFlow framework to train a Convolutional Neural Network (CNN) on the 'rock_paper_scissors' dataset.
- **Image Preprocessing:** Implements image resizing and normalization to prepare data for model training and inference.
- **Gesture Prediction:** Employs the trained model to predict gestures from new images, demonstrating the model's applicability in real-world scenarios.

## Repository Structure
- `model_training.ipynb`: Jupyter notebook containing the code for loading the dataset, preprocessing, training the CNN model, and saving the trained model.
- `gesture_recognition.py`: Python script to load a trained model and perform gesture recognition on individual images.
- `requirements.txt`: Lists the necessary Python packages for running the project.
- `README.md`: Provides an overview of the project, instructions for setup and usage, and additional project information.

## Getting Started
To get started with this project:
1. Clone the repository.
2. Install the required packages using `pip install -r requirements.txt`.
3. Run the `model_training.ipynb` notebook in Google Colab to train and save the model.
4. Use the `gesture_recognition.py` script to predict gestures from new images.

## Usage
After training the model, use the gesture recognition script as follows:
```python
python gesture_recognition.py --image path_to_your_image.jpg
