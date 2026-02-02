# Introduction to Deep Learning Libraries: MNIST Classification

This repository contains a comprehensive Jupyter Notebook demonstrating how to implement a neural network for handwritten digit recognition using three major deep learning frameworks: **Keras**, **TensorFlow**, and **PyTorch**.

## 🎯 Objective
The primary goal of this project is to provide a side-by-side comparison of the syntax, API structure, and training workflows of the industry's most popular AI libraries. By solving the same problem (MNIST classification) across all three, we can observe the trade-offs between high-level abstraction and low-level control.

## 🛠️ Libraries & Frameworks
* **Keras:** Utilized for its high-level, user-friendly API which allows for rapid prototyping and simplified model building.
* **TensorFlow:** Leveraged as the underlying end-to-end platform, using the `tf.keras` module for seamless integration.
* **PyTorch:** Employed to demonstrate a more "Pythonic" and explicit approach, utilizing dynamic computational graphs and manual training loops.

## 🧠 Model Architecture
All implementations follow a consistent architecture to ensure a fair comparison:
* **Input Layer:** Flattened 28x28 pixel images (784 nodes).
* **Hidden Layer:** 128 units with **ReLU** activation.
* **Output Layer:** 10 units with **Softmax** activation for multi-class classification.
* **Optimizer:** Adam.
* **Loss Function:** Sparse Categorical Cross-Entropy (TensorFlow/Keras) and Cross-Entropy (PyTorch).



## 📊 Summary of Findings
| Feature | Keras / TensorFlow | PyTorch |
| :--- | :--- | :--- |
| **Abstraction Level** | High (Modular) | Medium (Explicit) |
| **Training Loop** | Automated via `.fit()` | Manual `for` loops |
| **Data Handling** | Built-in dataset loaders | `DataLoader` and `Transforms` |
| **Verbosity** | Concise | Detailed |

## 🚀 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yash-Bansal10/Deep-Learning.git
   ```
