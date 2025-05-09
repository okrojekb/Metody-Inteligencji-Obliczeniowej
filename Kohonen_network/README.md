# Kohonen Self-Organizing Map (SOM) Laboratory Exercises

## Introduction

This laboratory focuses on the implementation of the **Kohonen Self-Organizing Map (SOM)** and applying it to two datasets: **MNIST** and **notMNIST** (datasets without labels). The goal is to observe how the SOM organizes the data and how effectively it can group the data into clusters, despite the lack of labels during training.

The main objective is to determine whether the Kohonen network can assign data to specific neurons, with each neuron representing a different class. Initially, the classes are unknown and can only be validated once the network has been trained.

---

## Topics to be Covered

### **KOH1: Basic Kohonen Network (2 weeks, 4 points)**

- **Objective**: Implement a Kohonen network with neurons arranged in a rectangular grid **M×N**, which works for vectors of the same length.
- **Tasks**:
  - Implement two neighborhood functions:
    - Gaussian function
    - Negative second derivative of the Gaussian function
  - Add the ability to adjust the neighborhood width by scaling the argument of the function.
  - Use an exponential decay function for the learning rate:
    \[
    \alpha(t) = e^{-t/\lambda}
    \]
- **Testing**: 
  - Test the network on the following simple datasets:
    - **Hexagon (2D)** – Data clustered at the vertices of a hexagon.
    - **Cube (3D)** – Data clustered at the vertices of a cube.

- **Analysis**:
  - Does the network find the correct number of clusters in the data?
  - Does each neuron represent only one class?
  - What are the positions of the neurons in the data space?

---

### **KOH2: Kohonen Network on a Hexagonal Grid (2 points)**

- **Objective**: Extend the previous implementation by adding the option to arrange neurons in a **hexagonal grid topology**.
- **Tasks**:
  - Apply both neighborhood functions and topologies to datasets:
    - **MNIST**
    - **Human Activity Recognition Using Smartphones** (Run the SOM without labels)
  
- **Analysis**:
  - How well do the clusters found by the network correspond to the actual classes in the data?
  - Analyze the resulting mappings, considering the actual labels in the datasets.
