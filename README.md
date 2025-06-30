# HandWritten-Digit-Recognition-using-AI

***Overview***

This project implements a Convolutional Neural Network (CNN) for recognizing handwritten digits from the MNIST dataset and custom images. The system trains a deep learning model on 70,000 handwritten digit samples and can make predictions on new digit images.

***Key Features***

CNN Architecture: 3 convolutional layers with max pooling for feature extraction
Data Augmentation: Generates varied training samples to improve model robustness
MNIST Dataset: Uses the standard handwritten digits dataset
Custom Image Support: Processes and predicts digits from external image files
Model Evaluation: Provides loss and accuracy metrics on test data
Visualization: Displays processed images with predictions

***Technology Stack***

Python: Primary programming language
TensorFlow/Keras: Deep learning framework
OpenCV: Image processing
NumPy: Numerical computations
Matplotlib: Visualization

***Performance Metrics***

![image](https://github.com/user-attachments/assets/75bd2df4-9217-4e8d-bb07-b72621d4af1d)

***Installation***
   1. Prerequisites
   2. Python 3.7+
   3. pip package manager

# Setup Instructions

  ***1. Install required packages:***
  
       pip install tensorflow opencv-python matplotlib numpy

  ***2.Download the code:***


# Usage

 ***Training the Model***
 
     python digit_recognition.py

# Making Predictions on Custom Images
Place your digit images in the directory: 
/content/drive/MyDrive/HandWritten-Digits/

Ensure images are:
   Grayscale
   Centered digits
   White digit on black background

Run the script - it will automatically process all images in the directory
