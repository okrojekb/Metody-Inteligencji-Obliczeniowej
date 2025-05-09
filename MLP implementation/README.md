# Multilayer Perceptron (MLP) Lab Exercises

This folder contains a series of assignments (`NN1` to `NN6`) related to building, training, and analyzing multilayer perceptrons (MLPs) without the use of high-level machine learning libraries. The goal is to gain a deep understanding of neural network architecture, training dynamics, and the impact of hyperparameters.

## Objective

The main focus of these exercises is **not** just solving predictive tasks, but:
- Visualizing network structure and parameter evolution during training.
- Manually designing and testing architectures.
- Understanding the effects of different training strategies and components.
- Preparing an in-depth report summarizing experimental observations.

## Constraints

- **No pre-built ML libraries** (e.g., PyTorch, TensorFlow).
- Only basic libraries like `numpy` are allowed for matrix operations.
- Each week's exercise builds upon the previous one.
- Evaluation is based on implementation, experimentation, and insight.

## Weekly Tasks

### **NN1 – Basic MLP Implementation**
- Manually define architecture (layers, neurons, weights).
- Sigmoid activation + linear output.
- Regression task: `square-simple`, `steps-large`.

### **NN2 – Backpropagation**
- Implement backpropagation from scratch.
- Add visualizations of weight evolution.
- Compare full-batch vs mini-batch learning.

### **NN3 – Momentum & RMSProp**
- Implement:
  - Gradient descent with momentum.
  - RMSProp normalization.
- Compare convergence speed on regression tasks.

### **NN4 – Classification with Softmax**
- Implement softmax output layer.
- Modify training algorithm accordingly.
- Evaluate on datasets like `rings3-regular`, `easy`, `xor3`.

### **NN5 – Activation Functions**
- Add support for:
  - Sigmoid
  - Linear
  - Tanh
  - ReLU
- Compare performance for different architectures and functions.

### **NN6 – Overfitting & Regularization**
- Add weight regularization and early stopping.
- Evaluate methods to reduce overfitting on sparse/balanced datasets.

## Final Report

A summary report including:
- Observations from each lab.
- Parameter tuning impact.
- Visualizations and learning curves.
- Summary of key findings.
