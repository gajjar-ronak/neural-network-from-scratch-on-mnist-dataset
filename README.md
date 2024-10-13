# Neural Network from Scratch for MNIST Classification

This project demonstrates how to build a simple neural network from scratch using only NumPy, without relying on high-level machine learning libraries. It is designed to classify handwritten digits from the MNIST dataset.

## Features

- **MNIST Dataset**: Preprocessed and used for training and testing.
- **Neural Network**: A fully connected neural network with one hidden layer.
- **Forward Propagation**: Computes the output based on inputs and current weights.
- **Backward Propagation**: Updates weights using the gradient of the cost function.
- **Gradient Descent**: Optimizes weights to reduce the classification error.
- **Visualization**: Learning curve and prediction results are visualized.

## Requirements

- Python 3.x
- NumPy
- Keras (for loading the MNIST dataset)

Install dependencies:

```bash
pip install numpy keras matplotlib
```

## How to Run

1. Clone the repository:

```git clone git@github.com:gajjar-ronak/neural-network-from-scratch-on-mnist-dataset.git
cd neural-network-from-scratch-on-mnist-dataset
```

2. Run the script:

```
python Neural-Network-From-Scratch-On-MNIST-Dataset.py
```

3. The model will train on the MNIST dataset, and you'll see the training loss over time and the accuracy on the test set.

## Neural Network Architecture

Input Layer: 784 nodes (28x28 pixel images flattened) \
Hidden Layer: 64 neurons with sigmoid activation \
Output Layer: 10 neurons with sigmoid activation (for digits 0-9)

## Project Files

Neural-Network-From-Scratch-On-MNIST-Dataset.py: Main script to train and evaluate the neural network. \
README.md: Project documentation.
