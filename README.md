# optimizer-showdown

## Overview
This project aims to compare the performance of various optimization algorithms in training a neural network on the MNIST dataset. The optimizers compared include:

- **SGD (Stochastic Gradient Descent)**
- **AdaGrad**
- **RMSProp**
- **Adam**
- **AdaDelta**

The project is implemented in two ways:
1. **From Scratch**: Custom implementations of the neural network and optimizers using NumPy.
2. **Using Keras**: Leveraging TensorFlow/Keras to build and train the model with built-in optimizers.

## Usage

### From Scratch Implementation

The `Custom_Neural_Network_Optimizers_From_Scratch.ipynb` notebook contains the custom implementation of the neural network and optimizers. It includes:

- Loading and preprocessing the MNIST dataset.
- Implementing the neural network from scratch with ReLU and Softmax activations.
- Custom implementations of SGD, AdaGrad, RMSProp, Adam, and AdaDelta optimizers.
- Training the model and comparing the performance of each optimizer.

## Results

The project provides a detailed comparison of the optimizers in terms of:

- **Training Loss**: How quickly each optimizer reduces the loss during training.
- **Final Loss**: The final loss achieved by each optimizer after training.
- **Convergence Speed**: How fast each optimizer converges to a solution.

### Loss Comparison Plots

The loss curves for each optimizer are visualized using Plotly, providing an interactive way to compare their performance.

### Final Loss Comparison

A bar chart comparing the final loss achieved by each optimizer is also provided, giving a clear overview of their performance.
