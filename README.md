# Simple MNIST Digit Recognizer – Neural Network from Scratch (NumPy)

This project demonstrates how to build and train a basic two-layer neural network **from scratch** using only **NumPy**. The model is trained on the classic **MNIST dataset** to recognize handwritten digits (0–9).

##  Overview

- Implemented **forward and backward propagation** manually.
- Used **ReLU** and **Softmax** activation functions.
- Built entirely with **pure Python and NumPy** — no TensorFlow or PyTorch.
- Trained on **28x28 pixel** grayscale digit images.
- Ideal for understanding neural network fundamentals and learning how they work under the hood.

## Architecture

- **Input Layer**: 784 units (flattened 28x28 image)
- **Hidden Layer**: 10 units with ReLU activation
- **Output Layer**: 10 units with Softmax activation

## Training Details

- **Loss Function**: Cross-Entropy Loss
- **Optimizer**: Manual Gradient Descent
- **Epochs**: Configurable
- **Dataset**: [Kaggle Digit Recognizer Competition](https://www.kaggle.com/competitions/digit-recognizer)

## Features

- Manual weight initialization
- Matrix-vectorized operations for performance
- Clear and concise implementation with comments
- Great educational resource for beginners

