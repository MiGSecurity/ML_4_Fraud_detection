# Credit Card Fraud Detection with Deep Neural Networks

A complete machine learning pipeline for detecting fraudulent credit card transactions using a deep Multi-Layer Perceptron (MLP) with PyTorch.

## 📊 Project Overview

This project implements a robust fraud detection system that can identify suspicious transactions with high precision. The model achieves **88.89% precision** and **80% recall** on imbalanced financial data, demonstrating strong performance in real-world scenarios where false positives are costly.

## 🚀 Key Features

- **Deep Neural Network**: 3-hidden layer MLP with dropout regularization
- **Class Imbalance Handling**: Automatic class weighting for fraud detection
- **Early Stopping**: Prevents overfitting and optimizes training time
- **Comprehensive Evaluation**: Precision, Recall, F1-Score, ROC-AUC, and confusion matrix
- **Production Ready**: Saves trained model and scaler for inference
- **Stratified Sampling**: Maintains class distribution across splits

## 📈 Performance Metrics

| Metric | Score |
|--------|-------|
| Precision | 88.89% |
| Recall | 80.00% |
| F1-Score | 84.21% |
| ROC-AUC | 88.24% |

**Confusion Matrix:**
