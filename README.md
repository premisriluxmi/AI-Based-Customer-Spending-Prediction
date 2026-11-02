# AI-Based Customer Spending Prediction

## Project Overview

The AI-Based Customer Spending Prediction project aims to build a beginner-friendly machine learning system that predicts whether a customer belongs to a Low, Medium, or High spending category using demographic and purchasing-related information.

This project is part of my AI & ML Internship at Veda Technology.

## Project Objective

- Understand the complete machine learning workflow.
- Prepare and explore customer data.
- Perform feature engineering and preprocessing.
- Train classification models to predict customer spending categories.

## Dataset Information

- **Total Records:** 200 customers
- **Dataset Type:** Synthetic dataset created for educational purposes.
- **Target Variable:** Spending_Category
- **Categories:** Low, Medium, High

### Dataset Features

| Feature | Description |
|---|---|
| Customer_ID | Unique customer ID |
| Age | Customer age |
| Annual_Income | Annual income |
| Purchase_Frequency | Monthly purchase frequency |
| Avg_Order_Value | Average order value |
| Membership_Years | Years of membership |
| Website_Visits | Website visits |
| Monthly_Spending | Estimated monthly spending |
| Spending_Category | Customer spending category |

**Note:** Monthly_Spending is excluded from model inputs because it is directly used to determine the target category.

## Project Progress

### Day 1 – Dataset Understanding and Preparation

- Created a synthetic customer dataset containing 200 records.
- Loaded the dataset using Pandas.
- Examined dataset rows and columns.
- Checked data types and statistical information.
- Identified input features and target variable.
- Examined spending categories.
- Exported the dataset as a CSV file.

**Output:** `customer_spending_dataset.csv`

### Day 2 – Data Cleaning and Exploratory Data Analysis

- Checked missing values and duplicate records.
- Performed basic data cleaning.
- Explored customer spending patterns.
- Created five visualizations:
  1. Customer Spending Category Distribution
  2. Customer Age Distribution
  3. Annual Income Distribution
  4. Purchase Frequency vs Monthly Spending
  5. Average Order Value by Spending Category
- Exported the cleaned dataset.

**Output:** `customer_spending_cleaned.csv`

### Day 3 – Feature Engineering and Model Training

- Created new features: Age Group and Income Level.
- Selected input features and target variable.
- Applied StandardScaler for numerical features.
- Applied OneHotEncoder for categorical features.
- Split the dataset into training and testing sets (80:20).
- Trained two classification models:
  - Logistic Regression
  - Decision Tree Classifier
- Generated sample predictions.
- Saved both trained models.

**Output:**
- `logistic_regression_model.pkl`
- `decision_tree_model.pkl`

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Jupyter Notebook

## Project Files

| File Name | Description |
|---|---|
| Customer_Spending_Prediction_Day1.ipynb | Dataset understanding |
| Customer_Spending_Prediction_Day2.ipynb | Data cleaning and EDA |
| Customer_Spending_Prediction_Day3.ipynb | Feature engineering and model training |
| customer_spending_dataset.csv | Original dataset |
| customer_spending_cleaned.csv | Cleaned dataset |
| column_description.csv | Column descriptions |
| logistic_regression_model.pkl | Trained Logistic Regression model |
| decision_tree_model.pkl | Trained Decision Tree model |

## Project Status

- Day 1: Completed
- Day 2: Completed
- Day 3: Completed

## Internship

AI & ML Internship – Veda Technology