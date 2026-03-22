# ScratchNet 🧠

[![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

**Build neural networks from scratch using only NumPy. Understand every line of code behind deep learning.**

[Features](#-features) • [Quick Start](#-quick-start) • [Documentation](#-documentation) • [Examples](#-examples) • [Why Scratch](#-why-build-from-scratch)

---

## 📖 About

ScratchNet is an educational implementation of neural networks built entirely from scratch using only NumPy. No TensorFlow, PyTorch, or Keras - just pure Python and mathematics. This project is designed to help you understand the inner workings of neural networks by building them layer by layer, from forward propagation to backpropagation.

### Why Build from Scratch?

- 🎓 **Deep Understanding** - Learn what happens under the hood of frameworks
- 📐 **Mathematical Clarity** - See the actual math behind gradient descent
- 🔧 **Full Control** - Modify and experiment with every component
- 🧪 **Educational Value** - Perfect for students and ML enthusiasts
- 💡 **Debugging Skills** - Understand where errors actually occur

---

## ✨ Features

### Core Components
- ✅ **Fully Connected Layers** - Dense layers with customizable sizes
- ✅ **Multiple Activations** - ReLU, Sigmoid, Tanh, Softmax
- ✅ **Backpropagation** - Manual gradient computation with chain rule
- ✅ **Loss Functions** - Cross-entropy, MSE (Mean Squared Error)
- ✅ **Weight Initialization** - He and Xavier initialization
- ✅ **Training Loop** - Customizable epochs and learning rates

### Advanced Features
- 🔄 **Batch Processing** - Train on batches of data
- 📊 **Training Visualization** - Loss and accuracy tracking
- 💾 **Model Saving/Loading** - Save trained weights
- 🎯 **Multi-class Support** - Softmax for classification
- 📈 **Custom Metrics** - Track any custom metric

### Educational Tools
- 📝 **Step-by-Step Comments** - Every line explained
- 🧪 **Unit Tests** - Verify mathematical correctness
- 📚 **Examples** - MNIST, XOR, Iris datasets
- 🔍 **Debug Mode** - Print intermediate values

---

## 🚀 Quick Start

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/scratchnet.git
cd scratchnet

# No installation required! Just import the module
