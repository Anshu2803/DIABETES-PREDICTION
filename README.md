# DIABETES-PREDICTION
This project uses a machine learning model to predict whether an individual is diabetic based on health-related inputs such as glucose levels, blood pressure, insulin levels, BMI, and other features. The model was trained using a support vector machine and classifier algorithm.

Table of Contents:
Project Overview
Model Training
How It Works
Results

Project Overview:
This project provides a simple web interface that allows users to enter various health metrics and predict their diabetes status. The machine learning model, trained using the Support Vector Machine (SVM) algorithm, analyzes the input data to determine the likelihood of diabetes.

The Pima Indians Diabetes Database was used for training, and the project is built using the Flask framework to deliver the web interface.

Model Training:
Algorithm: Support Vector Machine (SVM)
SVM was chosen for its strong performance in binary classification tasks, especially for datasets where data points are not perfectly separable.
Dataset: The model is trained on the Pima Indians Diabetes Database, which includes data on pregnancies, glucose, insulin, blood pressure, BMI, and other health-related variables.
Model Performance: The SVM classifier was trained and tested using this data, achieving good accuracy on both training and test datasets.

How It Works:
Input: The user enters health data such as glucose level, blood pressure, and BMI.
Processing: The input data is passed to the SVM model, which has been trained to identify patterns that correspond to diabetes.
Output: The model returns a prediction indicating whether the person is diabetic or non-diabetic.

Results:
Accuracy Score on Training Data: 78.34%
Accuracy Score on Test Data: 77.92%
The model shows good performance in predicting diabetes, with accuracy scores close to 78% on both the training and test datasets. This indicates that the model generalizes well and is suitable for making predictions on new, unseen data.
