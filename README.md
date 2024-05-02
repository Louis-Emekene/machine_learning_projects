# Handwritten Digits Classifier using MLP

This repository contains Python code to implement a handwritten digits classifier using a Multi-Layer Perceptron (MLP). The model is trained on the MNIST dataset, a standard benchmark dataset for handwritten digit classification tasks.

## Requirements

- Python (>=3.6)
- PyTorch (>=1.0)
- torchvision

You can install PyTorch and torchvision using pip:


## Usage

1. Clone the repository:


2. Run the training script:


The script will train the MLP model on the MNIST dataset for a default of 5 epochs. You can adjust the number of epochs and other hyperparameters directly in the `train.py` file.

3. After training, the script will print the accuracy of the trained model on the test set.

## Model Architecture

The MLP model architecture used in this project consists of:

- Input layer: Flattened input image of size 28x28 pixels
- Hidden layer 1: Fully connected layer with 128 neurons and ReLU activation function
- Hidden layer 2: Fully connected layer with 64 neurons and ReLU activation function
- Output layer: Fully connected layer with 10 neurons (one for each digit) and softmax activation function

## Files

- `train.py`: Python script to train the MLP model on the MNIST dataset.
- `README.md`: This file providing an overview and instructions.
- `LICENSE`: License information for the project.

## License

This project is open for anyone to copy and modify

