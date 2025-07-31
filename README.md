# Perceptron and Adaline from Scratch

This repository contains an implementation of two classic machine learning algorithms—**Perceptron** and **Adaline (Adaptive Linear Neuron)**—built from scratch using Python and NumPy.

## 🚀 What’s Inside

- `Perceptron`: A binary classifier that learns using a simple update rule based on misclassifications.
- `Adaline`: A linear classifier that minimizes the squared error cost function using gradient descent.
- Comparison of **learning rates** for Adaline and their impact on convergence using loss plots.

## 🧠 Algorithms

### Perceptron

- Initialized with a learning rate, number of iterations, and random seed
- Updates weights based on classification errors
- Tracks errors over each epoch

### Adaline (Gradient Descent)

- Uses continuous output (net input) rather than binary step function
- Implements batch gradient descent
- Tracks **mean squared error** per epoch
- Plotted convergence for different learning rates

## 📊 Visualization

Loss was plotted for two Adaline models with different learning rates:
- `ada1` with learning rate `0.1`
- `ada2` with learning rate `0.001`

This helps visualize how learning rate affects convergence.

## 📦 Dependencies

- `numpy`
- `matplotlib`

You can install them using:

```bash
pip install numpy matplotlib
