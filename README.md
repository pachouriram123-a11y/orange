🚀 Loan Default Prediction using Logistic Regression (Orange Data Mining)
📌 Project Overview

This project demonstrates a Loan Default Prediction Model built using Orange Data Mining (No-Code Machine Learning Tool).

The objective is to predict whether a customer is likely to default on a loan (1) or not default (0) using Logistic Regression with Ridge (L2) regularization.

The project includes:

Data preprocessing
Feature selection
Logistic Regression model training
Model evaluation
ROC analysis
Confusion Matrix analysis
🛠 Tools Used
Orange Data Mining
Logistic Regression (Ridge Regularization)
CSV Dataset
Machine Learning Evaluation Metrics
📂 Project Workflow
File
 ↓
Select Columns
 ↓
Logistic Regression
 ↓
Test & Score
 ↓
├── ROC Analysis
└── Confusion Matrix
📊 Dataset Information

Dataset contains 100 rows of loan-related records.

Example Features:
Applicant Income
Loan Amount
Credit Score
Employment Status
Loan Term
Existing Debt
Monthly Income
Loan Purpose
Previous Defaults
Target Variable (Default: 0/1)
⚙ Model Configuration
Algorithm:

Logistic Regression

Regularization:
Ridge (L2)
Validation:
10-Fold Cross Validation
Stratified Sampling Enabled
📈 Model Performance
Test & Score Results
Metric	Score
AUC	0.991
Accuracy	0.970
F1 Score	0.970
Precision	0.971
Recall	0.970
MCC	0.930
Interpretation
Model achieved 97% accuracy
Very strong AUC (99.1%)
Balanced precision and recall
Indicates excellent classification performance
🔍 Confusion Matrix
Actual / Predicted	0	1
0	68	2
1	1	29
Insights:
True Negatives → 68
False Positives → 2
False Negatives → 1
True Positives → 29
📉 ROC Analysis

ROC Curve shows excellent model discrimination capability.

Curve remains close to top-left corner
Indicates high sensitivity and specificity
AUC ≈ 0.99
📸 Screenshots

Create a folder:

images/

Add screenshots:

images/workflow.png
images/test_score.png
images/roc_analysis.png
images/confusion_matrix.png

Then add:

## Workflow
![Workflow](images/workflow.png)

## Test & Score
![Test Score](images/test_score.png)

## ROC Analysis
![ROC](images/roc_analysis.png)

## Confusion Matrix
![Confusion Matrix](images/confusion_matrix.png)
▶ How to Run
Install Orange Data Mining
Open .ows workflow
Load CSV dataset
Run workflow
View evaluation metrics
📌 Future Improvements
Compare with Random Forest
Hyperparameter tuning
Larger datasets
Feature engineering
👨‍💻 Author

Rohit Pachori
MBA (Applied Finance)
Project: Loan Default Prediction using Orange
