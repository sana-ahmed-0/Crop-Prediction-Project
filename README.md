# Crop-Prediction-Project
Overview
This project aims to predict the most suitable crop based on soil nutrients and pH values. It's a simple machine learning pipeline using Logistic Regression as the classification algorithm.

Dataset
The dataset includes the following features:
N - Nitrogen level
P - Phosphorous level
K - Potassium level
ph - Soil pH
crop - Crop label (target)

You can find the dataset in soil_measures.csv.

Tools & Libraries
Python 
Pandas 📊
NumPy
Scikit-learn 

Model & Approach
Data was split into training and testing sets using train_test_split.
A Logistic Regression model was trained for each feature individually.
Accuracy for each feature was computed and compared.

Feature Performance
To understand the individual impact of each soil feature on crop prediction, a logistic regression model was trained separately on each feature. The following table summarizes the prediction accuracy for each:
Feature	Accuracy (%)
Nitrogen (N)	13.86%
Phosphorous (P)	20.23%
Potassium (K)	28.64%
pH	9.77%

These results show that Potassium (K) has the highest predictive power among the individual features, while pH contributes the least when used alone.

Files
soil_measures.csv – Dataset
Project1.ipynb – Model training and evaluation notebook
