# Breast-Cancer-Classification-Using-Machine-Learning
This project demonstrates the use of various machine learning algorithms to classify breast cancer data from the popular sklearn breast cancer dataset. The project involves loading the dataset, preprocessing it, implementing different classifiers, and comparing their performance.

# Table of Contents
1 Project Overview
2 Dataset
3 Preprocessing
4 Classification Algorithms
5 Model Comparison 
6 Usage
7 Results
8 Contributing

# Project Overview
In this project, we aim to predict whether a tumor is malignant or benign based on various features. We implement five machine learning algorithms, compare their performance, and provide insights into which algorithm works best.

# Dataset
We use the breast cancer dataset available in the sklearn.datasets module. The dataset consists of 30 features and a binary target variable (1: Malignant, 0: Benign).

# Preprocessing
Before applying machine learning models, we preprocess the data:

1 Handling missing values: The dataset does not contain missing values.
2 Feature scaling: We applied min-max scaling, standard scaling to ensure that features with larger magnitudes don’t dominate the model training process.

# Classification Algorithms
We implemented the following algorithms:

# Logistic Regression:
Description: A simple linear model that estimates the probability of a binary outcome.
Suitability: Logistic Regression works well with binary classification problems like this one.

# Decision Tree Classifier:
Description: A tree-like model that splits data based on feature values.
Suitability: This model is highly interpretable and handles non-linear data well.

# Random Forest Classifier:
Description: An ensemble model that combines multiple decision trees to improve accuracy and reduce overfitting.
Suitability: Works well with high-dimensional datasets and reduces overfitting.

# Support Vector Machine (SVM):
Description: A powerful algorithm that tries to find the best hyperplane separating two classes.
Suitability: Effective in high-dimensional spaces.

# k-Nearest Neighbors (k-NN):
Description: A non-parametric algorithm that classifies new instances based on the majority class of its nearest neighbors.
Suitability: Suitable for smaller datasets but can be slow for large datasets.

# Model Comparison
We compared the performance of the models using the following metrics:

1 Accuracy Score
2 Confusion Matrix
3 Classification Report

# Usage
Run the EDA Notebook to explore the dataset.
Run the Model Training Notebook to train the models.
Run the Model Comparison Notebook to compare the results.

# Results
in general, Random Forest and SVM often perform well on this type of dataset. However, The best performing algorithms are k-Nearest Neighbors, Decision Tree Classifier, Random Forest Classifier because except all other algorithms are overfit.

# Contributing
Contributions are welcome! Feel free to open issues or submit pull requests
