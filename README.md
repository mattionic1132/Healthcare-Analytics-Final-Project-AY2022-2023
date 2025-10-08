# Healthcare-Analytics-Final-Project-AY2022-2023
This project was my first exposure to Machine Learning, which involved the commonly used Diabetes Dataset from Kaggle. My team and I explored, cleaned and selected the right data, fed them into different classifiers and deployed our best model with a Graphical User Interface.

# Project Overview
This repository presents a Healthcare Analytics project focused on early detection of diabetes onset using advanced machine learning methods. The project leverages the well-established Pima Indian Diabetes dataset and compares multiple algorithms to predict diabetes from clinical data, with a user-facing interface for practical deployment.

# Problem Statement
Diabetes melllitus remains a leading non-communicable disease worldwide, responsible for millions of deaths and significant clinical burdens. Conventional diagnostic approaches are often time-consuming, invasive, and sometimes inaccurate or inconvenient for both patients and healthcare workers. The objective of this project is to improve prediction accuracy and diagnostic speed using data-driven machine learning solutions, making early intervention possible.

# Methodology
Dataset & Materials: 

1) Pima Indian Diabetes dataset (768 patients, 8 clinical variables from UCI Repository)
2) Python with core libraries: Scikit-learn, Tkinter (for GUI), Numpy, Pandas
3) All code and models are available and explorable in the repository.

# Data Preprocessing

Outlier Removal: Interquartile Range (preferred) and Z-score methods.
Missing Value Imputation: Median replacement, zeroes specifically handled for tricep skin fold thickness and serum insulin.
Feature Selection: Pearson’s correlation, univariate statistical tests, violin plots.
Class Imbalance Resolution: Oversampling/undersampling approaches were implemented to balance positive and negative outcomes.

# Model Development

Multi-layer Perceptron (MLP): Hyperparameter tuning for layers, neurons, regularization (dropout, kernel constraints), batch size, epochs.
Support Vector Machine (SVM): Explored kernels (linear, polynomial, RBF, sigmoid), exhaustive grid search for hyperparameters, stratified K-fold cross-validation.
K-Nearest Neighbours (KNN): Systematic optimization for best k-values, multiple validation approaches including elbow method and ROC-AUC.
Logistic Regression: Iterative and grid search optimization, l1/l2 penalties, cross-validation.

# Evaluation Metrics
Accuracy, F1-score, Precision, Recall, Area Under ROC Curve (AUC).

# Interface
Tkinter-based GUI where users can input new patient data and receive real-time diabetes onset predictions.

# Results and Model Performance
The SVM model with RBF kernel achieved the highest prediction accuracy (90%) and best overall performance compared with other models, validated through stratified cross-validation and ROC analysis. MLP, KNN, and Logistic Regression models also performed robustly—each model’s confusion matrix, precision, recall, F1-score and ROC curves are detailed in the report.
The GUI integrates the best tuned model for reliability; users can view prediction outcomes from multiple algorithms for increased confidence.

# Update 2025
Some codes might be outdated due to the improvement of different machine learning libraries, however the concepts and leanring points remain unchanged.
