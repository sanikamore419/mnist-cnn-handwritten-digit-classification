# MNIST Handwritten Digit Classification using CNN

## 📌 Project Overview

This project implements a **Convolutional Neural Network (CNN)** for handwritten digit classification using the **MNIST Handwritten Digit Dataset**.

The objective is to automatically recognize handwritten numerical information that can be useful in banking applications such as:

- Cheque amount recognition
- Account number processing
- Postal/PIN code recognition
- Automated numerical data entry

The MNIST dataset is integrated from **Kaggle using the Kaggle API** and processed using Google Colab.

---

## 🎯 Objectives

- Integrate the MNIST dataset using the Kaggle API.
- Load and preprocess handwritten digit images.
- Develop a CNN using convolution, pooling, and fully connected layers.
- Train the CNN to classify handwritten digits from 0 to 9.
- Evaluate the model using suitable classification metrics.
- Analyze errors using a confusion matrix.
- Visualize correct and incorrect predictions.

---

## 📊 Dataset

**Dataset:** MNIST Handwritten Digit Dataset

| Property | Value |
|---|---|
| Training images | 60,000 |
| Testing images | 10,000 |
| Image dimensions | 28 × 28 pixels |
| Number of classes | 10 |
| Classes | 0–9 |

### Dataset Source

The dataset is downloaded from Kaggle using the Kaggle API:

```text
hojjatk/mnist-dataset
