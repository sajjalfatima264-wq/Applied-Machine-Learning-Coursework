Applied Machine Learning Coursework

This repository contains my practical assignments for the Applied Machine Learning course, progressing from classical ML algorithms to custom deep learning architectures.

📂 Contents
Assignment 01: Regression & Classification

Notebook: BSCE23042.ipynb | Report: BSCE23042.pdf

Q1: Built Multiple Linear Regression on a custom Marketing_Sales dataset (500 records). Achieved an R² Score of 0.9668, identifying Social Media as the highest contributing factor to sales.

Q2: Compared KNN, Logistic Regression, and Decision Trees on the Iris dataset. KNN (k=5) achieved 100% accuracy, outperforming the other models due to the distinct physical dimensions of the species.

Assignment 02: Naive Bayes & SVM

Notebook: 1Task42.ipynb | Report: BSCE23042_Assignmnent2.pdf

Implemented Gaussian Naive Bayes from scratch and compared it with Scikit-learn's SVM (Linear and RBF kernels) on the Breast Cancer Wisconsin dataset.

Key Takeaway: The RBF kernel handled non-linear boundaries effectively, proving superior for complex medical data classification.

Assignment 03: Artificial Neural Networks

Notebook: 2Task42.ipynb | Report: BSCE23042_ML-3.pdf

Built a custom fully connected neural network from scratch for binary classification (Breast Cancer dataset).
Key Takeaway: Implementing custom Dropout and BatchNormalization was crucial to prevent the model from overfitting the training data.

Assignment 04: CNN & RNN
Code: taska_bsce23042.py (CNN), task_b_bsce23042.py (RNN) | Report: BSCE23042.pdf

Part A (CNN): Built a custom CNN for the PlantVillage dataset (38 classes, 54K+ images). Achieved a 96.30% validation accuracy using 5+ Conv layers, BatchNorm, and adaptive learning rates.

Part B (LSTM): Built a stacked LSTM for IMDb sentiment analysis. Achieved an 88.75% validation accuracy and an AUC of 0.9555, successfully handling long-range dependencies in text.

🛠️ Tech Stack
Languages: Python
Libraries: TensorFlow/Keras, Scikit-learn, NumPy, Pandas, Matplotlib, Seaborn
Tools: Jupyter Notebooks, Google Colab
