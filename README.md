# AI-ML Assignment 8

# Handwritten Digit Recognition using Artificial Neural Networks (ANN)

---

## Author Details

**Name:** Uday Pratap Singh

**Registration Number:** 23BA10540

**Application Number:** IN26011163

**Batch:** 1(A)

---

# Objective

The objective of this assignment is to develop an Artificial Neural Network (ANN) model capable of recognizing handwritten digits (0–9) using the MNIST dataset. The model learns patterns from pixel values of handwritten images and classifies them into the correct digit class. This demonstrates the application of Deep Learning in image recognition and multi-class classification problems.

---

# Dataset

**Dataset Name:** MNIST Handwritten Digits Dataset

**Kaggle Link:**

https://www.kaggle.com/datasets/oddrationale/mnist-in-csv

**Dataset Files**

- mnist_train.csv
- mnist_test.csv

---

# Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- TensorFlow
- Keras
- Scikit-learn

---

# Methodology

## 1. Data Understanding

- Loaded the MNIST dataset using Pandas.
- Displayed the first five records.
- Identified input features and target variable.
- Displayed dataset dimensions.
- Displayed summary information.
- Visualized one handwritten digit using Matplotlib.

---

## 2. Data Preprocessing

- Checked for missing values.
- Separated input features and target labels.
- Normalized pixel values between 0 and 1.
- Split the dataset into 80% training and 20% testing.
- Applied One-Hot Encoding to target labels.

---

## 3. Model Architecture

The Artificial Neural Network consists of the following layers:

| Layer | Neurons | Activation |
|--------|---------|------------|
| Input Layer | 784 | Input |
| Hidden Layer 1 | 128 | ReLU |
| Hidden Layer 2 | 64 | ReLU |
| Output Layer | 10 | Softmax |

---

## Model Configuration

- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Metric: Accuracy
- Epochs: 10
- Batch Size: 32

---

# Results

The trained ANN model successfully classified handwritten digits from the MNIST dataset.

The following outputs were generated:

- Dataset Information
- Summary Statistics
- Sample Handwritten Digit
- Model Summary
- Test Accuracy
- Confusion Matrix
- Classification Report
- Accuracy vs Epoch Graph
- Loss vs Epoch Graph
- Sample Predictions

---


---

# Conclusion

This project demonstrates the effectiveness of Artificial Neural Networks in handwritten digit recognition. The hidden layers learned complex image features that enabled accurate classification of digits from 0 to 9. Normalization and One-Hot Encoding improved the model's performance during training. Compared with traditional Machine Learning algorithms, Deep Learning automatically extracts useful features from raw image data, resulting in better accuracy. However, ANN models require greater computational resources and longer training time, especially when working with large datasets.





