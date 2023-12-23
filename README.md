# Plant Leaf Disease Prediction
# Overview
This GitHub repository contains a project for predicting plant leaf diseases using deep learning. The project includes a training script for building a convolutional neural network (CNN) model and a Flask web application for making predictions on user-uploaded images.

# Project Structure
# Training Code (training.py):

Utilizes TensorFlow and Keras to create a CNN for plant leaf disease prediction.
Augments training images to improve model generalization.
Saves the trained model in JSON and H5 formats.

# Prediction Code (leaf.py):

Implements a Flask web application for user-friendly interaction.
Loads the pre-trained model to predict the class of the uploaded plant leaf image.
Displays the prediction result and the processed image on the web page.

# Web Templates (templates/):

Contains HTML templates for the web application.
# Static Files (static/):
Includes a folder for uploading and storing user images.

# Install Dependencies:
Install the required Python libraries using the following command:

pip install -r requirements.txt
python leaf.py

# Python version:
3.8.0v
