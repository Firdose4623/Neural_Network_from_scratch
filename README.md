# MNIST Neural Network from Scratch (NumPy)

This project implements a **feedforward neural network** for handwritten digit classification on the [MNIST dataset](http://yann.lecun.com/exdb/mnist/)  **from scratch using NumPy**.  
The goal is to deepen understanding of how neural networks work under the hood without relying on high-level libraries like TensorFlow or PyTorch.

---

## 🚀 Project Overview
- **Dataset**: MNIST (42,000 grayscale images of digits 0–9, 28×28 pixels).  
- **Approach**: Built a neural network from scratch using only NumPy for matrix operations.  
- **Architecture**:  
  - Input layer: 784 neurons (flattened 28×28 image)  
  - Hidden layers: customizable (experimented with 1–2 layers)  
  - Output layer: 10 neurons (digits 0–9, softmax activation)  

---

## 🛠️ Implementation Details
The notebook is divided into the following sections:

### 1. Data Loading & Preprocessing
- Loaded MNIST dataset from CSV files.  
- Normalized pixel values to `[0,1]`.  
- Converted labels to one-hot encoded vectors.  

### 2. Parameter Initialization
- Weights initialized with small random values.  
- Biases initialized as zeros.  
- Stored in a Python dictionary for flexibility.  

### 3. Activation Functions
- Implemented **Sigmoid**, **ReLU**, and **Softmax** from scratch.  
- Also implemented their derivatives for backpropagation.  

### 4. Forward Propagation
- Linear → Activation steps computed layer by layer.  
- Final output: probability distribution over 10 classes using softmax.  

### 5. Loss Function
- Used **cross-entropy loss** to measure prediction error.  

### 6. Backward Propagation
- Derived gradients for each layer manually.  
- Implemented chain rule step by step.  

### 7. Gradient Descent Optimization
- Updated weights & biases using gradient descent.  
- Tuned learning rate for stability.  

### 8. Model Training
- Ran multiple epochs over the dataset.  
- Computed training accuracy and loss after each epoch.  

### 9. Evaluation
- To be done....

---

## 📊 Results
- Visualized training loss curve.  

---
