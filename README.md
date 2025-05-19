# MNIST MLP Lab – Neural Networks with Keras and TensorFlow

This repository contains the solution for the Activity 1 of the Neural Networks course. The objective is to build, train, and evaluate a Multilayer Perceptron (MLP) using the MNIST dataset of handwritten digits.

## 📌 Project Scope

This project explores the following topics:
- Input data normalization and reshaping.
- One-hot encoding of labels.
- Architecture design with dense layers, activation functions, and regularization.
- Compilation and training of MLP models.
- Evaluation of training strategies: layer size, epochs, optimizers, early stopping.
- Regularization techniques (L2, Dropout, BatchNormalization).
- Model comparison and selection based on accuracy and loss.
- Final model reaching >95% validation accuracy.

## 📁 Structure

mnist-mlp-lab/
│
├── notebook/
│ └── muinar06_act1_individual.ipynb # Main Jupyter Notebook with answers
│
├── figures/
│ └── *.png # Accuracy/loss charts for experiments
│
├── models/
│ └── final_model.h5 # Saved final model
│
├── reports/
│ └── actividad1_mnist_mlp.pdf # PDF version of the notebook (for delivery)
│
└── requirements.txt # Required Python dependencies


## 🧪 Setup

To run this notebook locally:

```bash
# (Recommended) Create a virtual environment
python -m venv mnist-mlp-env
source mnist-mlp-env/bin/activate  # macOS/Linux
# OR
mnist-mlp-env\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt

# Add virtual environment to Jupyter kernels (optional)
pip install ipykernel
python -m ipykernel install --user --name=mnist-mlp-env
