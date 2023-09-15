# Neural-Network-MNIST

A basic Introduction to learning deep learning, by building my Fist ANN model.

The model is trained and tested on MNIST dataset, a dataset of handwritten digits. The models is used for classification, where it receives as input 784 features (gray scale of pixels values), and returns the predict digit in the range of  [0-9].

ANN used is a simple Neural Network, that was build using PyTorch.


# Neural Network for MNIST Digit Classification

## Introduction

This project provides a beginner's introduction to deep learning by building a basic Artificial Neural Network (ANN) model. The model is trained and evaluated using the MNIST dataset, which consists of handwritten digits. The primary objective is to perform digit classification, where the model takes a 28x28 grayscale image as input (784 features) and predicts the digit it represents, ranging from 0 to 9.

The ANN architecture is implemented using PyTorch, a popular deep learning framework.

## Getting Started


### Code Overview
- **`ANNModel`**: This class defines the architecture of our neural network. It consists of an input layer, two fully connected hidden layers, and an output layer. Each hidden layer uses the ReLU (Rectified Linear Unit) activation function.
- **Training Loop**: The code includes a training loop that uses the Stochastic Gradient Descent (SGD) optimizer and the Cross-Entropy Loss function to train the neural network.
- **Data Preprocessing**: The pixel values of the input images are normalized to the range [0, 1], and the data is moved to the GPU (if available) for faster processing.

## Usage

1. **Training**: To train the ANN model, simply run the code. You can adjust hyperparameters: epochs, batch size and learning rate.

## Conclusion

This project serves as a practical introduction to deep learning and neural networks, using PyTorch as the framework to build my first Deep Learning Model. 