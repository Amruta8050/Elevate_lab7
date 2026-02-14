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
<img width="1239" height="253" alt="Image" src="https://github.com/user-attachments/assets/38ea7f81-cd43-474c-964f-b42b4b116e11" />
<img width="567" height="250" alt="Image" src="https://github.com/user-attachments/assets/27a81a66-4823-4770-a44e-5773f243a137" />
<img width="752" height="611" alt="Image" src="https://github.com/user-attachments/assets/747fa75e-e562-48a0-99fa-3760a72a22f7" />
<img width="794" height="599" alt="Image" src="https://github.com/user-attachments/assets/7dc8eda9-82da-435d-bfc8-c35e514cf415" />
