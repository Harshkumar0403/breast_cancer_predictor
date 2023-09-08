# breast_cancer_predictor
## Overview
This project aims to develop a Breast Cancer Predictor model that can predict whether a tumor is malignant or benign based on a set of 31 features. The model utilizes the Logistic Regression approach to find the best fit and provide accurate predictions.

## Dataset
The dataset used for this project consists of 31 features and one target variable:

## Features:

radius_mean
texture_mean
perimeter_mean
area_mean
smoothness_mean
compactness_mean
concavity_mean
concave points_mean
symmetry_mean
fractal_dimension_mean
radius_se
texture_se
perimeter_se
area_se
smoothness_se
compactness_se
concavity_se
concave points_se
symmetry_se
fractal_dimension_se
radius_worst
texture_worst
perimeter_worst
area_worst
smoothness_worst
compactness_worst
concavity_worst
concave points_worst
symmetry_worst
fractal_dimension_worst
Target Variable: diagnosis (1 for malignant, 0 for benign)

## Model and Methodology
The Logistic Regression algorithm is employed to train the model on the given dataset. Logistic Regression is a popular choice for binary classification tasks like predicting whether a tumor is malignant or benign. The model learns the relationships between the input features and the target variable to make predictions.

## Visualization
To better understand the dependencies between each feature and the presence of cancer, this project utilizes the Seaborn library for data visualization. Visualizations such as histograms, box plots, or pair plots can be generated to visualize the distribution and relationships between features and the target variable.

## Data Splitting
The dataset is divided into a training set and a testing set using the train-test split technique. This ensures that the model's performance is evaluated on unseen data, helping to assess its generalization capability.

Model Evaluation
After training and testing the model, the project provides the following evaluation metrics:

Confusion Matrix: This matrix displays the number of true positive, true negative, false positive, and false negative predictions made by the model, allowing for a detailed understanding of its performance.

Accuracy Score: The model's accuracy is calculated, indicating the percentage of correct predictions. In this case, a score of 93 percent suggests a strong predictive capability.

## Usage
To use this Breast Cancer Predictor model:

Ensure you have the required libraries installed, including NumPy, Pandas, Scikit-Learn, Seaborn, and Matplotlib.

Load your breast cancer dataset or use the provided dataset.

Train the Logistic Regression model on the dataset.

Use the trained model to predict whether a tumor is malignant or benign based on the 31 input features.

Visualize the dependencies between features and cancer presence using Seaborn.

Evaluate the model's performance using the confusion matrix and accuracy score.

## Dependencies
NumPy

Pandas

Scikit-Learn

Seaborn

Matplotlib
## Credits
This project was created by Harsh kumar.

