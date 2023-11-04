# MiniTorch

## Introduction

Welcome to MiniTorch, a minimalistic machine learning library inspired by the design and functionality of PyTorch. MiniTorch aims to provide enthusiasts and learners with a clearer understanding of the core principles behind neural networks and deep learning by offering a simplified version of a powerful ML library.

## Features

- **Tensor Operations**: Basic operations that mimic PyTorch's tensor functionality.
- **Autograd Mechanism**: A simple automatic differentiation engine for gradient descent.
- **Modular Design**: Easy-to-understand modules for building and training neural networks.
- **Educational Focus**: Extensive documentation explaining the underlying ML concepts.

## Installation

To get started with MiniTorch, clone the repository and install the required dependencies:

```bash
git clone https://github.com/LexiYin-mh/MiniTorch.git
cd MiniTorch
pip install -r requirements.txt
```

## Usage
Here's a quick start example of how to create a tensor, perform operations, and compute gradients:

```python
from minitorch import Tensor

# Initialize a tensor
x = Tensor([[1.0, 2.0], [3.0, 4.0]], requires_grad=True)

# Perform operations
y = x + x
z = y.mean()

# Compute gradients
z.backward()

print(x.grad)  # Outputs the gradient of z with respect to x
```

## Reference
This repository contains the course projects for the [Machine Learning Engineering](https://minitorch.github.io/) 
course, taught by Professor [Sasha Rush](https://rush-nlp.com/) at Cornell Tech. These projects were completed during the Fall 2023 semester as part of the Master's program curriculum. Each module within the repository corresponds to a specific assignment designed to enhance practical skills in implementing machine learning algorithms, data preprocessing, model evaluation, and deployment techniques aligned with industry standards.
