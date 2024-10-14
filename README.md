# Rock Paper Scissors Image Classification

This project implements an image classification model using TensorFlow to recognize images of rock, paper, and scissor with convolutional neural networks (CNN) and applies image augmentation techniques to improve model generalization.

## Dataset
The dataset used for this project is sourced from [Dicoding Academy's rockpaperscissors dataset](https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip), which contains images categorized into three classes: rock, paper, and scissors.

## Project Structure
The project consists of a single script that:
- Downloads and extracts the dataset
- Prepares and augments the training and validation sets
- Defines and trains a CNN model
- Saves the best-performing model
- Allows users to upload new images for classification

# Model Architecture
The CNN model architecture includes the following layers:
- Convolutional layers with ReLU activation
- Max pooling layers for downsampling
- A fully connected layer with Dropout for regularization
- Output layer with softmax activation for multi-class classification
