# BreastCancer-ML-Classification
A machine learning project implementing Decision Tree, Logistic Regression, and MLP classifiers to predict breast cancer recurrence. Features data preprocessing, oversampling for class balance, and model comparison using cross-validation, achieving 98.5% accuracy with Decision Trees.

Key Features

Implementation of three different classification algorithms:

Decision Tree Classifier
Logistic Regression
Multi-Layer Perceptron (MLP) Classifier


Extensive data preprocessing pipeline including:

Missing value handling
Categorical variable encoding
Feature scaling
Class imbalance correction through oversampling


Comprehensive model evaluation using:

10-fold cross-validation
Multiple performance metrics (accuracy, precision, recall, F1-score)
Confusion matrices
Comparative analysis visualizations



Results

Decision Tree Classifier: 98.5% accuracy
MLP Classifier: 85.8% mean cross-validation accuracy
Logistic Regression: 62.7% mean cross-validation accuracy

Technologies Used

Python
scikit-learn
matplotlib
seaborn

Dataset
The dataset consists of 286 instances with 9 input features and a binary target variable indicating cancer recurrence. Features include patient age, menopausal status, tumor size, lymph node involvement, and other clinical parameters.
