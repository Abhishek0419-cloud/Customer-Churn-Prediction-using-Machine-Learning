# Customer Churn Prediction System

## Problem

Telecom companies lose significant revenue when customers discontinue their services (churn).
The goal of this project is to predict whether a customer will churn so that the company can take preventive actions such as retention offers and customer support.

## Solution

I built an end-to-end Machine Learning pipeline that predicts customer churn using customer demographic and service usage data.

## Project Workflow

* Data preprocessing and cleaning
* Encoding categorical variables
* Handling class imbalance using SMOTE
* Model training using Decision Tree, Random Forest, and XGBoost
* Model evaluation using Accuracy, Confusion Matrix, and ROC-AUC
* Feature importance analysis to identify churn drivers
* Model deployment using Pickle for real-time predictions

## Model Performance

The Random Forest classifier achieved strong performance and was selected as the final model based on ROC-AUC evaluation.

## Key Insights

Major factors affecting churn:

* Contract type
* Monthly charges
* Customer tenure

## How to Run

1. Install dependencies:

```
pip install -r requirements.txt
```

2. Run prediction:

```
python predict.py
```

The system will output churn prediction and probability for a new customer.

## Technologies Used

Python, Pandas, Scikit-learn, SMOTE, Random Forest, XGBoost, Matplotlib
