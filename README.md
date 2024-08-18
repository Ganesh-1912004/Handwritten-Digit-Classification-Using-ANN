# Handwritten Digit Classification

## Overview

This project focuses on classifying handwritten digits using an Artificial Neural Network (ANN) with multiple hidden layers. The MNIST dataset, which contains images of handwritten digits from 0 to 9, is used for this classification task. The goal is to build a model that can accurately predict the digit from a given image.

## Dataset

The dataset used is the MNIST dataset, which can be accessed [here](http://yann.lecun.com/exdb/mnist/) or downloaded directly via TensorFlow/Keras.

## Workflow

1. **Data Collection**: Utilize the MNIST dataset for training and testing the model.
2. **Data Preprocessing**: 
   - Load the dataset and normalize the images.
   - Convert labels to one-hot encoded format.
3. **Model Building**:
   - Construct an ANN with multiple hidden layers and activation functions.
   - Use ReLU (Rectified Linear Unit) activation functions for hidden layers and sigmoid for the output layer.
4. **Model Training**:
   - Train the ANN on the MNIST dataset.
   - Achieve an accuracy of **97%** on the test dataset.
5. **Prediction**:
   - Implement functionality to predict handwritten digits from new images using the trained model.

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/handwritten-digit-classification.git
cd handwritten-digit-classification
pip install -r requirements.txt
