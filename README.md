# Customer-Churn-Prediction
## Overview

This project focuses on predicting customer churn using a dataset containing demographic, transactional, and bank relationship information. The solution employs Logistic Regression as the primary machine learning model.

## Features

  Input Data: The dataset includes variables related to customer demographics, bank relationships, and transaction histories.

  Machine Learning Workflow: Data preprocessing, feature selection, and model evaluation using Logistic Regression.

  Evaluation Metrics: ROC-AUC, accuracy, precision, recall, and confusion matrix.

## Installation

## Prerequisites

  1. Python 3.8+

  2. Jupyter Notebook

## Dependencies

Install the required Python packages:

pip install numpy pandas seaborn matplotlib scikit-learn

## Setting Up

1. Clone the repository:

git clone https://github.com/yourusername/customer-churn-prediction.git
cd customer-churn-prediction

2. Open the Jupyter Notebook:

jupyter notebook "Churn Prediction Solution.ipynb"

## Dataset

The dataset contains the following categories:

Demographic Information

customer_id: Customer ID

vintage: Number of days the customer has been with the bank

age: Customer's age

gender: Gender of the customer

dependents: Number of dependents

occupation: Occupation of the customer

city: Anonymized city of residence


## Customer Bank Relationship

customer_nw_category: Net worth category (1: High, 2: Medium, 3: Low)

branch_code: Branch code for the customer's account

days_since_last_transaction: Number of days since the last transaction


## Transactional Information

current_balance: Current balance

previous_month_end_balance: Balance at the end of the previous month

average_monthly_balance_prevQ: Average monthly balance in the previous quarter

average_monthly_balance_prevQ2: Average monthly balance two quarters ago

current_month_credit: Total credit amount for the current month

previous_month_credit: Total credit amount for the previous month

current_month_debit: Total debit amount for the current month

previous_month_debit: Total debit amount for the previous month

current_month_balance: Average balance for the current month

previous_month_balance: Average balance for the previous month

churn: Indicator if the customer will churn (1: Yes, 0: No)


## Usage

1. Load Data and Packages: Load the dataset and necessary libraries.

2. Data Preprocessing: Handle missing values, encode categorical variables, and standardize numerical features.

3. Feature Selection: Select features based on exploratory data analysis (EDA) conclusions.

4. Model Building: Train a Logistic Regression model using the selected features.

5. Evaluation: Assess the model's performance using metrics like ROC-AUC and precision-recall curves.


## Running the Notebook

Open the Churn Prediction Solution.ipynb file in Jupyter Notebook and execute the cells sequentially to:

1. Load the dataset

2. Preprocess the data

3. Build and evaluate the model


## Contribution

Contributions are welcome! To contribute:

1. Fork the repository.

2. Create a new branch for your feature or bug fix.

3. Commit your changes and open a pull request.


## Acknowledgments

Special thanks to the open-source community and publicly available datasets for supporting this project.


