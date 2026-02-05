# 🧠 Deep Learning Homework 2: Multi-Layer Perceptron from Scratch

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Deep Learning](https://img.shields.io/badge/Deep%20Learning-MLP-green.svg)](https://en.wikipedia.org/wiki/Multilayer_perceptron)

## 📖 Overview

This project implements a **Multi-Layer Perceptron (MLP)** neural network from scratch for binary classification tasks. The implementation demonstrates fundamental deep learning concepts including forward propagation, backpropagation, and gradient descent optimization without relying on high-level frameworks.

## 🎯 Project Goals

### Question 1: Analytical Weight Determination
- Analytically derive weights for an MLP to solve the "A" pattern classification problem
- Determine the minimum number of hidden units required in each layer
- Explore single vs. multi-layer architectures for the same problem

### Question 2: Training & Data Augmentation
Implement two versions of the model:
- **Version 1**: Baseline model with non-augmented data
- **Version 2**: Enhanced model with augmented training data and optimized training procedures

## 📁 Project Structure

```
DL-HW2/
├── Code.ipynb                          # Main implementation notebook
├── Code.zip                            # Compressed code archive
├── README.md                           # Project documentation
├── Q1_DLHW2.jpg                       # Problem statement visualization
├── nn.png                              # Neural network architecture diagram
├── Picture_of_A.png                    # "A" pattern visualization
└── Desmos_approx_weights to find.png  # Weight approximation visualization
```

## ✨ Features

- **From-Scratch Implementation**: Pure Python/NumPy implementation of MLP
- **Binary Classification**: Specialized for two-class problems
- **Data Augmentation**: Techniques to improve model generalization
- **Training Optimization**: Accelerated training procedures
- **Visualization**: Learning curves and decision boundaries
- **Analytical Solutions**: Mathematical approach to weight determination

## 🚀 Getting Started

### Prerequisites

```bash
pip install numpy matplotlib jupyter
```

Required:
- Python 3.x
- Jupyter Notebook
- NumPy
- Matplotlib (for visualizations)

### Running the Code

1. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook Code.ipynb
   ```

2. **Execute cells sequentially** to:
   - Load and preprocess data
   - Train the MLP models (Version 1 and 2)
   - Visualize learning curves
   - Compare model performance

## 📊 Key Results

The project demonstrates:
- **Learning curves** comparing baseline vs. optimized training
- **Sample space visualizations** showing the impact of data augmentation
- **Performance metrics** for both model versions
- **Analysis** of solution uniqueness and parameter optimization

## 🔍 Implementation Details

### Network Architecture
The MLP implementation includes:
- Configurable hidden layer sizes
- Sigmoid/ReLU activation functions
- Forward and backward propagation
- Gradient descent with momentum (Version 2)

### Data Augmentation Strategy
Version 2 enhances training through:
- Treating provided points as distribution means
- Generating additional synthetic samples
- Improved generalization capabilities

## 📚 References

- Course textbook, Section 6.5.4: Backpropagation in MLPs (Deep Learning textbook)
- Original problem statement: `Q1_DLHW2.jpg`

## 💡 Discussion Points

- Is there a unique solution for exact class separation?
- What's the minimum network complexity needed?
- How does data augmentation affect convergence?
- Trade-offs between analytical and learned solutions

## 📝 Report Requirements

- ✅ Version 1 model implementation
- ✅ Version 2 model with augmentation
- ✅ Sample space visualizations for both versions
- ✅ Learning curve comparisons
- ✅ Experience description and analysis
- ✅ Discussion of solution uniqueness

---

**Author**: Patrick J. Craig  
**Course**: Deep Learning  
**Assignment**: Homework 2
