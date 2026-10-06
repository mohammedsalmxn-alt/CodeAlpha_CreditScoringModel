# Credit Scoring Model

## CodeAlpha Machine Learning Internship — Task 1

### Project Overview

This project develops a machine learning model to predict an individual's creditworthiness using historical financial data.

The project was completed as part of the CodeAlpha Machine Learning Internship.

## Objective

The objective of this project is to classify applicants into two credit-risk categories:

- Good Credit
- Bad Credit

Machine learning classification algorithms were used to train and evaluate the credit scoring model.

## Dataset

The project uses the German Credit dataset.

The dataset contains financial and personal information about credit applicants and a target variable representing credit risk.

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Algorithms

Two classification algorithms were implemented:

### 1. Logistic Regression

Logistic Regression was used as a classification model to predict whether an applicant belongs to the good-credit or bad-credit category.

### 2. Random Forest

Random Forest was implemented as another classification model and its performance was compared with Logistic Regression.

## Data Preprocessing

The following preprocessing techniques were used:

- Separation of features and target
- Identification of numerical and categorical features
- Train-test split
- Standardization of numerical features
- One-hot encoding of categorical features

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- ROC Curve

## Model Results

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Accuracy | 78.00% | 76.00% |
| Precision | 66.67% | 67.65% |
| Recall | 53.33% | 38.33% |
| F1-Score | 59.26% | 48.94% |
| ROC-AUC | 80.40% | 79.49% |

## Best Model

Based on the evaluation results, Logistic Regression performed better overall on the test dataset.

### Logistic Regression Results

- Accuracy: 78.00%
- Precision: 66.67%
- Recall: 53.33%
- F1-Score: 59.26%
- ROC-AUC: 80.40%

Therefore, Logistic Regression was selected as the final model.

## Project Workflow

```text
Dataset
   ↓
Data Understanding
   ↓
Data Preprocessing
   ↓
Train-Test Split
   ↓
Feature Encoding & Scaling
   ↓
Logistic Regression
   ↓
Random Forest
   ↓
Model Evaluation
   ↓
Model Comparison
   ↓
Final Prediction
