# Handwritten Digit Classification using Artificial Neural Network (ANN)

This project demonstrates handwritten digit recognition using the **MNIST dataset** and a simple **Artificial Neural Network (ANN)** built with **TensorFlow/Keras**.  
The MNIST dataset contains 70,000 grayscale images of handwritten digits (0–9), each of size 28x28 pixels.

---

## 📌 Project Overview
The goal of this project is to classify handwritten digits into 10 classes (0–9).  
We use a **feed-forward neural network** with:
- Input Layer: Flattened 28×28 image → 784 features
- Hidden Layer 1: Dense(128) with ReLU activation
- Hidden Layer 2: Dense(32) with ReLU activation
- Output Layer: Dense(10) with Softmax activation

The model achieves **~97.5% accuracy** on the test set.

---

## 📊 Dataset
- **Source:** [MNIST dataset](http://yann.lecun.com/exdb/mnist/)
- **Training set:** 60,000 images

🛠️ Technologies Used

Python 3

TensorFlow / Keras

Matplotlib (for visualization)

scikit-learn (for accuracy score)


🚀 Training

Optimizer: Adam

Loss function: Sparse Categorical Crossentropy

Metric: Accuracy

Epochs: 10

Validation split: 20%


Training results:

Final Train Accuracy: ~99.4%

Final Validation Accuracy: ~97.3%

Test Accuracy: 97.56%
- **Test set:** 10,000 images
- Each image: 28×28 pixels, grayscale
