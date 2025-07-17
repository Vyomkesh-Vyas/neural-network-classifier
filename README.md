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

- Output vector: One-hot encoded (e.g., A = [1, 0, 0])
```

---

## 📊 Visualizations

The training script tracks and plots:

- Loss over epochs

- Classification accuracy

---

## 📁 Project Structure

```bash
character-recognition/
├── Neural Network from Scratch.ipynb      # Main script with model training   
└── README.md                              # Project documentation
```

---

## 🧪 Example Input Patterns

Each letter is defined using a 5×6 binary grid. For example:

Letter A
```bash
 011110
 100001
 111111
 100001
 100001
 ```
Flattened to:
[0, 1, 1, 1, 1, 0, ..., 1] (length: 30)

---

## 📄 License

MIT License – feel free to use, modify, and share.

---