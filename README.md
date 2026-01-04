## Overview

This project implements a convolutional neural network (CNN) using Keras to classify handwritten digits from the MNIST dataset. The goal is to learn hierarchical visual features from grayscale images and evaluate how well the model generalizes to unseen data.

## Model details

- Architecture: Convolutional Neural Network
- Framework: TensorFlow (Keras API)
- Input: 28×28 grayscale images
- Output: 10 digit classes (0–9)
- Loss function: categorical_crossentropy
- Optimizer: Adam

## Results

- Training accuracy: ~99.18%
- Validation accuracy: ~99.10%

The close alignment between training and validation performance indicates that the model generalizes well and avoids overfitting.

## Training behavior

Training and validation loss decrease smoothly and remain closely aligned throughout training, indicating stable convergence and effective regularization.

## Files

- `Deep Learning CNN for Handwritten Digits.ipynb` – Full implementation, training, and evaluation
