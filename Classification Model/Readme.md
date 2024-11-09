# Classification Model Module

This module is responsible for training, evaluating, and predicting network anomalies using the classification model on the NSL-KDD dataset. It focuses on identifying various types of network attacks based on the given features and labels in the dataset.

---

## 1. File Structure and Description

This module consists of the following key files:

- **`classification_model.py`**: Contains the core functions for training, evaluating, and predicting with the model.
- **`config.yaml`**: Configuration file for model parameters, hyperparameters, and dataset paths.

---

## 2. Architecture diagram

![Network Traffic Analysis and Anomaly Detection Architecture](https://github.com/user-attachments/assets/08d42504-b17b-47ca-a5fe-b13dfd0ae889)

## 3. Methods

Data Collection and Preprocessing: Using publicly available datasets, preprocess and label network traffic data.
Feature Engineering: Extract features (e.g., packet size, connection duration, protocol type) relevant to identifying anomalies.
Model Development:
ML Models: Isolation Forest, One-Class SVM, K-Nearest Neighbors (KNN)
Deep Learning Models: Autoencoders, CNNs, RNNs
Hybrid Models: Combining anomaly-based and signature-based approaches for a robust detection system
Model Evaluation: Assess models on accuracy, precision, recall, and F1-score.
Alert Mechanism: Generate alerts with anomaly details when a threat is detected.
