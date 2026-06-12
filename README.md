# MNIST Digit Classifier using PyTorch

## Overview

This project implements a Handwritten Digit Classifier using PyTorch and the MNIST dataset.

The model is trained on images of handwritten digits (0–9) and learns to predict the correct digit from unseen images. This project was created to understand the fundamentals of neural networks, deep learning, and image classification using PyTorch.

## Features

* Built using PyTorch
* Trained on the MNIST dataset
* Uses a Feed Forward Neural Network (FNN)
* Supports GPU acceleration when available
* Evaluates model accuracy on test data
* Saves the trained model for future use
* Predicts digits from unseen images

## Dataset

MNIST is a benchmark dataset for handwritten digit recognition.

* 60,000 training images
* 10,000 testing images
* Image size: 28 × 28 pixels
* 10 classes (digits 0–9)

## Model Architecture

Input Layer:

* 784 neurons (28 × 28 flattened image)

Hidden Layers:

* Linear Layer (784 → 128)
* ReLU Activation
* Linear Layer (128 → 64)
* ReLU Activation

Output Layer:

* Linear Layer (64 → 10)

## Technologies Used

* Python
* PyTorch
* TorchVision
* Matplotlib

## Training Process

1. Load the MNIST dataset
2. Flatten image tensors
3. Train the neural network
4. Compute loss using CrossEntropyLoss
5. Optimize parameters using Adam Optimizer
6. Evaluate model performance on test data
7. Save the trained model

## Results

The model successfully classifies handwritten digits and demonstrates the complete deep learning workflow, including training, evaluation, and prediction.

## How to Run

1. Install dependencies

```bash
pip install -r requirements.txt
```

2. Open and run:

```text
mnist_project.ipynb
```

## Learning Outcomes

* Neural Network Fundamentals
* Forward Propagation
* Backpropagation
* Model Training and Evaluation
* Image Classification
* PyTorch Workflow

## Future Improvements

* Implement Convolutional Neural Networks (CNNs)
* Add Confusion Matrix Visualization
* Visualize Misclassified Images
* Build a Streamlit Web Application

## Author

Shivam Poojan Yadav
