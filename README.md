# neural-network-classifier
# Character Recognition with Neural Network (A, B, C)

This project implements a simple feedforward neural network from scratch (using NumPy) to classify binary pixel patterns representing the letters **A**, **B**, and **C**. Each character is represented as a **5×6 (30-pixel)** binary grid. The model is trained using custom **backpropagation logic** and optimized to minimize classification error.

## 🔍 Overview

- Binary image data of letters A, B, C (5x6 grid → 30 features)
- One hidden layer neural network (10 hidden units)
- Activation: Sigmoid
- Loss: Mean Squared Error (MSE)
- Optimizer: Manual gradient descent
- Visualization: Loss and accuracy over epochs using matplotlib

---

## 🧠 Architecture

```text
Input Layer (30)
        ↓
  Hidden Layer (10, Sigmoid)
        ↓
 Output Layer (3, Sigmoid)
