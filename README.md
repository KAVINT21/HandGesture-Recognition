# HandGesture-Recognition

# Dependencies
tensorflow
keras
gradio

# Overview
This project implements Hand Gesture Recognition using a Convolutional Neural Network (CNN) built with TensorFlow and Keras. The model is trained on a dataset of hand gesture images to classify different gestures. Gradio is employed to create an interactive user interface for real-time hand gesture recognition.

# Project Components

# 1. Data Preparation
The dataset is organized in the train directory, and an ImageDataGenerator is used for data augmentation and preprocessing. The dataset is split into training and validation sets.

# 2. Model Definition and Training
A simple CNN model is defined using Keras with Conv2D, MaxPooling2D, Flatten, and Dense layers. The model is compiled with the Adam optimizer and categorical crossentropy loss. Training is performed on the training set for 10 epochs.

# 3. Model Saving
The trained model is saved for future predictions.

# 4. Gradio Interface
Gradio is used to create an interactive interface for hand gesture recognition. The Interface is defined with a function that preprocesses input images and performs predictions using the trained model.

![Screenshot 2024-01-24 102453](https://github.com/KAVINT21/HandGesture-Recognition/assets/95117554/14df3fa0-de93-4968-83c1-f299d4f5dc4c)


