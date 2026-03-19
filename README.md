# 🤖 Federated Learning-Based Predictive Maintenance

## 📌 Overview
This project implements a **Federated Learning (FL) framework** for predictive maintenance, enabling multiple clients to collaboratively train a model **without sharing raw data**.

An **LSTM-based deep learning model** is used to predict machine failure types from sensor data while preserving data privacy.

---

## 🏗️ Architecture
- **Data Distribution**: Dataset split across multiple clients  
- **Local Training**: Each client trains an LSTM model on its local data  
- **Federated Aggregation**: Model weights are aggregated to form a global model  
- **Global Update**: Updated model is redistributed to clients  
- **Evaluation**: Performance measured on test datasets  

---

## 🎯 Output
- Prediction of failure types:
  - TWF, HDF, PWF, OSF, RNF  
- Federated global model performance  
- Evaluation metrics:
  - Accuracy, Precision, Recall, F1-score, MSE  

---

## 🛠️ Tech Stack
Python, TensorFlow/Keras, NumPy, Pandas, Scikit-learn, Matplotlib

---

## 📌 Summary
A privacy-preserving predictive maintenance system using Federated Learning, enabling decentralized training while maintaining strong predictive performance.
