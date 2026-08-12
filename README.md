# FACE-EMOTION---CNN-
A CNN-based Emotion Detection project that classifies facial images into Happy and Sad categories. The project uses image preprocessing and a Convolutional Neural Network (CNN) for training and emotion classification, enabling automated recognition of basic human emotions from facial images.
# CNN Emotion Detection – Happy vs Sad

## Project Description

A Convolutional Neural Network (CNN) based image classification project that detects human emotions from facial images and classifies them into two categories: Happy and Sad.

## Objective

The objective of this project is to train a CNN model to automatically recognize facial emotions from input images and classify them as Happy or Sad.

## Dataset

The dataset contains facial images organized into two emotion classes:

- Happy
- Sad

## Technologies Used

- Python
- OpenCV
- NumPy
- Pandas
- Matplotlib
- TensorFlow
- Keras
- Scikit-learn

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Pandas
- Matplotlib
- TensorFlow
- Keras
- Scikit-learn
- Jupyter Notebook

## Methodology

1. Load the facial image dataset
2. Read and validate images
3. Convert images to grayscale
4. Resize images to a fixed dimension
5. Prepare image labels
6. Normalize pixel values
7. Split data into training and validation sets
8. Build CNN architecture
9. Train the CNN model
10. Evaluate model performance
11. Predict Happy or Sad emotion from new images

## CNN Architecture

- Conv2D
- MaxPooling2D
- Conv2D
- MaxPooling2D
- Flatten
- Dense
- Dropout
- Output Layer

## Model Training

The CNN model is trained using the prepared facial image dataset. Early Stopping is used during training to prevent unnecessary training and retain the best model weights.

## Output

The trained model predicts the emotion of an input facial image as:

- Happy
- Sad

## Future Enhancement

- Add more emotion classes such as Angry, Fear, Surprise, and Neutral
- Increase dataset size
- Improve model accuracy
- Deploy the model as a real-time emotion detection application
