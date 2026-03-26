# Machine_Learning_Tutorial
# Neural Network Architecture: Depth vs Width (MLP)

## Overview
This project explores how the architecture of a neural network affects its performance. Specifically, it focuses on the impact of **depth (number of layers)** and **width (number of neurons per layer)** in a Multilayer Perceptron (MLP).

The tutorial demonstrates how different configurations influence:
- Model accuracy
- Decision boundaries
- Training behaviour
- Overfitting and underfitting

---

## Objectives
- Understand the structure of a Multilayer Perceptron (MLP)
- Compare shallow, medium, and deep neural networks
- Visualise how models learn using decision boundaries
- Analyse the trade-offs between model complexity and performance

---

## Dataset
This project uses a synthetic dataset generated using `make_moons` from Scikit-learn.

- Non-linear dataset
- Ideal for testing neural networks
- Helps visualise decision boundaries clearly

---

## Models Implemented

| Model Type | Architecture |
|------------|-------------|
| Shallow    | 1 hidden layer (10 neurons) |
| Medium     | 2 hidden layers (20, 20) |
| Deep       | 4 hidden layers (50, 50, 50, 50) |

---

## Results

The experiment shows:

- **Shallow networks** struggle with complex patterns (underfitting)
- **Medium networks** provide the best balance between accuracy and generalisation
- **Deep networks** can learn complex patterns but may overfit

Decision boundary plots and accuracy comparisons are included in the notebook.

---

## 📂 Project Structure
