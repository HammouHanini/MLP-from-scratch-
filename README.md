# MLP from Scratch in R

A multi-layer perceptron (MLP) neural network implementation from scratch using base R, with no deep learning frameworks.

## Overview

This project implements a simple MLP classifier for the Palmer Penguins dataset with:
- **Architecture**: Input layer → Hidden layer (50 neurons) → Output layer (3 classes)
- **Activations**: Tanh for hidden layer, Softmax for output
- **Loss**: Cross-entropy loss
- **Optimizer**: Gradient descent with backpropagation

## Key Components

- **Forward Propagation**: Computes predictions through the network
- **Backward Propagation**: Calculates gradients using chain rule
- **Parameter Updates**: Adjusts weights and biases via gradient descent
- **Training Loop**: 40,000 iterations with learning rate 0.002

## Dataset

Uses the Palmer Penguins dataset to classify penguin species (Adelie, Chinstrap, Gentoo) based on physical measurements and categorical features.

## Results

The model achieves high accuracy on both training and test sets, demonstrating effective learning of penguin species classification patterns.