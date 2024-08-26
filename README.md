# 🧠 Perceptron Neural Network

This repository contains the implementation of a simple Perceptron neural network. The Perceptron is a foundational concept in machine learning and serves as the building block for more complex neural networks.

## 📝 Introduction

The purpose of this project is to demonstrate the basic workings of a Perceptron neural network using synthetic data. The notebook walks through the steps of data generation, model definition, training, and visualization of the decision boundary.

## ⚙️ Installation

To run this project, you'll need to have Python installed along with the following libraries:

- `numpy`
- `matplotlib`
- `scikit-learn`

You can install these dependencies using `pip`:

```bash
pip install numpy matplotlib scikit-learn
```

## 🚀 Usage
Clone the repository and navigate to the project directory:

```bash
Copy code
git clone https://github.com/yourusername/perceptron-neural-network.git
cd perceptron-neural-network
```

Open the Jupyter notebook:

```bash
Copy code
jupyter notebook Perceptron_Neural_Network.ipynb
```
Run all cells to generate the synthetic data, train the Perceptron model, and visualize the results.

## 📓 Notebook Overview
The notebook is divided into several sections:

📊 Data Generation: Creates a synthetic dataset with two features and two classes.

🔍 Data Preview: Displays a sample of the generated data and their corresponding labels.

🔄 Label Conversion: Converts the labels from {0, 1} to {-1, 1} to be compatible with the Perceptron.

⚖️ Sign Function: Defines a helper function to return the sign of a value.

🏗️ Perceptron Model: Implements the Perceptron model class, which includes weight initialization and the forward pass.

🔧 Optimizer: Implements an optimizer to update the model weights and bias.

🎨 Training and Visualization: Trains the Perceptron model and visualizes the decision boundary along with the data points.

## 📊 Results
The notebook outputs a plot showing the data points and the decision boundary learned by the Perceptron. This visualization helps to understand how the Perceptron classifies the data.

