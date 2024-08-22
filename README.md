# Customer-Segmentation-Using-Classification-in-Project

## Project Overview
This project focuses on classifying customers into different segments based on demographic, behavioral, and socioeconomic attributes. The objective is to apply machine learning techniques for effective customer segmentation, enhancing targeted marketing and personalized customer experiences.

## Problem Statement
We aim to accurately categorize customers into predefined segments using their data. Effective segmentation helps businesses understand their customer base better and tailor their strategies.

## Dataset Overview
The dataset includes the following features:

Gender: Customer's gender.
Ever_Married: Whether the customer is married.
Age: Customer's age.
Graduated: Whether the customer has a college degree.
Profession: Customer’s profession.
Work_Experience: Years of work experience.
Spending_Score: Customer's spending behavior (Low, Average, High).
Family_Size: Size of the customer’s family.
Var_1: A categorical variable related to customer preferences.
Segmentation: Target variable (A, B, C, or D) representing customer segments.
Data Preprocessing
Key preprocessing steps include:

## Handling Missing Values: Imputation using mean/mode or predictive models.
Encoding Categorical Variables: Conversion using one-hot or label encoding.
Feature Scaling: Scaling continuous features for equal model contribution.
Train-Test Split: Division of data for model training and evaluation.
Model Selection
## Explored classification algorithms:

Logistic Regression
Random Forest Classifier
Support Vector Machine (SVM)
Gradient Boosting
Selected Model: Random Forest Classifier, due to its superior accuracy and balanced performance metrics.

## Model Training and Evaluation
Performance metrics:

Accuracy: Overall correctness of the model.
Precision: Accuracy of positive predictions.
Recall: Ability to identify actual positives.
F1-Score: Balanced measure of precision and recall.
Summary:

Random Forest: 98% accuracy.

## Confusion Matrix and Classification Report
Detailed analysis of model performance:

Class A & B: High precision and recall.
Class C & D: Lower precision, indicating some classification challenges.
