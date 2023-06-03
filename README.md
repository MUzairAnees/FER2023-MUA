# FER2023-MUA
A Facial Emotion Recognition (FER) program built by Mohamed Uzair Anees. Ongoing development. 

# Project Description
This project is designed to identify and categorize emotions based on facial expressions. This is done by using a Convolutional Neural Network (CNN) implemented in TensorFlow and Keras.

# Data Augmentation
The model uses data augmentation to increase the diversity of data available for training, without collecting new data. Data augmentation techniques like image rotation, zooming, and horizontal flipping are used to train the model.

# Setup and Usage
## Dependencies

This project requires the following Python libraries:

TensorFlow (tested on version 2.5)
Keras (tested on version 2.4.3)

## Installation

Clone the repository to your local machine:
git clone https://github.com/MUzairAnees/FER2023-MUA.git

Navigate to the cloned directory:
cd your_project

Install the required packages:
pip install -r requirements.txt

## Usage

Load your data.
Preprocess your data, such as normalizing and reshaping the images.
Use the ImageDataGenerator class from Keras for data augmentation.
Split your data into training and validation sets.
Build your model architecture.
Compile your model.
Train your model using fit_generator() to implement the data augmentation.
Evaluate your model.
Check the Realtime Face Emotion Recog.ipynb Jupyter notebook for the complete code.

# Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
