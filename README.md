🚢 Titanic Survival Prediction using Logistic Regression
📌 Project Overview

This project implements a Binary Classification Model to predict whether a passenger survived the Titanic disaster using Logistic Regression.

The implementation follows a professional ML workflow using:
Pipeline
ColumnTransformer
Stratified Train-Test Split
Cross Validation
ROC Curve & AUC Evaluation
Automatic saving of outputs

Dataset Source: Seaborn Titanic dataset
Alternative Dataset: Kaggle Titanic Dataset

🎯 Objective
To build a robust Logistic Regression model that:
Predicts passenger survival (0 = Not Survived, 1 = Survived)
Handles missing values properly
Encodes categorical features
Scales numeric features
Evaluates using multiple performance metrics
Saves results automatically for documentation

🛠 Tools & Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Google Colab

#Project Structure
Titanic_Logistic_Regression/
│
├── titanic_logistic_regression.ipynb
├── outputs/
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── classification_report.txt
│   └── metrics.txt
├── README.md

#Outputs
