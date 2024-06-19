# MNIST Classification with PyTorch

This repository contains code for training a neural network to classify MNIST digits using PyTorch.

## Dataset

The MNIST dataset consists of 60,000 training images and 10,000 test images of handwritten digits (0-9). Each image is 28x28 pixels, and the digits are grayscale.

## Code Explanation

### Dependencies

The code requires the following dependencies:
- `torch`
- `torchvision`

## Data Loading

We use the torchvision.datasets.MNIST class to download and load the MNIST dataset. The images are transformed to tensors using torchvision.transforms.ToTensor.

## DataLoader

We use the DataLoader class to iterate through the dataset in batches.

## Model Definition

We define a simple neural network with three linear layers and ReLU activation functions.

## Training and Testing

We define functions for training and testing the model. The training function performs a forward pass, calculates the loss, and updates the model parameters using backpropagation. The testing function evaluates the model on the test data.

## Training the Model

We train the model for 15 epochs.

## Results

The model achieved the following performance on the test dataset:

Accuracy: Around 98.2%
Average Loss: Approximately 0.1
