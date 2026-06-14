# mnist-digit-classifier

This project implements a simple neural network to classify handwritten digits using the MNIST dataset.

Overview

The goal is to train a model that can recognize digits (0–9) from grayscale images.

Model

A simple feedforward neural network is used:

- Input layer: 784 features (28×28 pixels)
- Hidden layer: 128 neurons with ReLU activation
- Output layer: 10 classes (digits 0–9)

Training

- Loss function: CrossEntropyLoss
- Optimizer: Adam
- Dataset: MNIST (via torchvision)

Results

The model learns to classify digits with reasonable accuracy after a few epochs.

Technologies Used

- Python
- PyTorch
- Matplotlib

How to Run

1. Open the notebook
2. Run all cells
3. Observe training loss and predictions
