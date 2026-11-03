# AI-Based Customer Spending Prediction

## Project Overview

This project focuses on predicting customer spending categories using Machine Learning classification algorithms.

The system analyzes customer details such as age, annual income, purchase frequency, average order value, membership years, and website visits to classify customers into three spending categories:

- Low Spending
- Medium Spending
- High Spending

The dataset used in this project is a simulated customer dataset created for learning and demonstration purposes.

## Project Objectives

- Understand and prepare the customer dataset.
- Perform data cleaning and Exploratory Data Analysis (EDA).
- Create useful features for machine learning.
- Train and compare two classification models.
- Evaluate model performance using classification metrics.
- Identify important features influencing predictions.
- Predict the spending category of a sample customer.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## Project Workflow

### Day 1 – Dataset Understanding and Preparation

- Created a simulated customer spending dataset containing 200 records.
- Examined dataset structure, columns, data types, and statistical information.
- Checked missing values and duplicate records.
- Identified input features and the target variable.

### Day 2 – Data Cleaning and Exploratory Data Analysis

- Handled missing values and duplicate records.
- Performed exploratory data analysis.
- Created visualizations to understand customer spending patterns.
- Saved the cleaned dataset.

### Day 3 – Feature Engineering and Model Training

- Created Age Group and Income Level features.
- Applied StandardScaler for numerical features.
- Applied OneHotEncoder for categorical features.
- Split the dataset into training and testing sets.
- Trained two classification models:
  1. Logistic Regression
  2. Decision Tree Classifier
- Saved the trained models using Joblib.

### Day 4 – Model Evaluation and Analysis

- Generated predictions using both trained models.
- Evaluated model performance using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- Generated confusion matrices and classification reports.
- Analyzed Decision Tree feature importance.
- Created a sample customer prediction function.
- Generated business insights and saved evaluation results.

## Model Performance Comparison

| Evaluation Metric | Logistic Regression | Decision Tree |
|---|---:|---:|
| Accuracy | 75% | 87.5% |
| Precision | 75% | 88.1% |
| Recall | 75% | 87.5% |
| F1-Score | 75% | 87.2% |

**Best Performing Model:** Decision Tree Classifier

The Decision Tree model achieved 87.5% accuracy and performed better than Logistic Regression on this test dataset.

## Project Files

| File Name | Description |
|---|---|
| customer_spending_dataset.csv | Original simulated dataset |
| customer_spending_cleaned.csv | Cleaned dataset |
| column_description.csv | Dataset column descriptions |
| Customer_Spending_Prediction_Day1.ipynb | Dataset preparation |
| Customer_Spending_Prediction_Day2.ipynb | Data cleaning and EDA |
| Customer_Spending_Prediction_Day3.ipynb | Feature engineering and model training |
| Customer_Spending_Prediction_Day4_Evaluation.ipynb | Model evaluation and analysis |
| logistic_regression_model.pkl | Saved Logistic Regression model |
| decision_tree_model.pkl | Saved Decision Tree model |
| model_comparison_results.csv | Model evaluation results |
| feature_importance.csv | Decision Tree feature importance |

## Key Learning Outcomes

- Data preprocessing and cleaning
- Exploratory Data Analysis
- Feature engineering
- Classification algorithms
- Model evaluation
- Confusion matrix interpretation
- Feature importance analysis
- Making predictions using trained models

## Conclusion

This project demonstrates how Machine Learning classification algorithms can be used to analyze customer data and predict spending categories.

Among the two trained models, the Decision Tree Classifier achieved better performance with 87.5% accuracy on the test dataset.

The project helped develop practical knowledge of the end-to-end Machine Learning workflow, from dataset preparation to model evaluation and prediction.

---

**Project Status:** Completed

**Project Type:** Machine Learning – Classification

**Dataset:** Simulated Customer Spending Dataset
