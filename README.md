# Credit Card Fraud Detection

This repository contains a Python script for detecting credit card fraud using various visualization and machine learning techniques. The dataset consists of 50,000 credit card transactions, each labeled as fraudulent or non-fraudulent.

Overview
The script performs the following steps:

Importing the dataset
Exploratory Data Analysis (EDA)
Outlier detection
Feature reduction
Preprocessing
Model training and evaluation
Usage
To run the script, you will need Python and the following libraries installed:

pandas
numpy
matplotlib
seaborn
scikit-learn
You can then run the script as follows:

bash
Copy code
python credit_card_fraud_detection.py
Data
The dataset contains 50,000 credit card transactions, with each transaction having 30 features. The Class feature indicates whether the transaction is fraudulent (1) or not (0).

Exploratory Data Analysis (EDA)
The EDA includes various visualizations to understand the distribution of the features, their correlation, and their relationship with the target variable (Class). Some of the visualizations used are:

Pie chart for target distribution
Scatter plots for target distribution with two features
Histograms, KDE plots, box plots, and violin plots for feature distribution with the target variable
Heatmaps for feature correlation
Scatter plots for correlation between features and the target variable
Outlier Detection
The script uses the Tukey outlier detection method to identify outliers in the dataset. Outliers are visualized using box plots for each feature.

Feature Reduction
Principal Component Analysis (PCA) is used to reduce the dimensionality of the dataset, making it easier to visualize and analyze. The script includes plots for explained variance of the principal components and 2D plots of the transformed data.

Preprocessing
The script checks for missing values in the dataset and handles them if necessary.

Model Training and Evaluation
A machine learning model can be trained on the preprocessed data to predict whether a given transaction is fraudulent or not. The choice of model and its evaluation metrics are not included in this README but can be added based on the user's preferences.
