# Random Forest Loan Repayment Predictor

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-DecisionTree%20%7C%20RandomForest-brightgreen.svg)
![Python](https://img.shields.io/badge/Python-3.x-blue.svg)

This repository contains a machine learning project that predicts whether borrowers on LendingClub.com will pay back their loans in full or not. It utilizes DecisionTreeClassifier and RandomForestClassifier algorithms for classification.

## Overview

LendingClub.com is a platform connecting borrowers and investors. Investors want to invest in individuals with a high probability of repaying their loans. The goal of this project is to create a predictive model to help identify such individuals.

### Dataset

The dataset used for this project contains lending data from 2007-2010 and includes the following columns:

- `credit.policy`: 1 if the customer meets the credit underwriting criteria of LendingClub.com, and 0 otherwise.
- `purpose`: The purpose of the loan (e.g., "credit_card," "debt_consolidation," "educational," etc.).
- `int.rate`: The interest rate of the loan as a proportion (e.g., 0.11 for 11%).
- `installment`: The monthly installments owed by the borrower if the loan is funded.
- `log.annual.inc`: The natural log of the self-reported annual income of the borrower.
- `dti`: The debt-to-income ratio of the borrower.
- `fico`: The FICO credit score of the borrower.
- `days.with.cr.line`: The number of days the borrower has had a credit line.
- `revol.bal`: The borrower's revolving balance (amount unpaid at the end of the credit card billing cycle).
- `revol.util`: The borrower's revolving line utilization rate.
- `inq.last.6mths`: The borrower's number of inquiries by creditors in the last 6 months.
- `delinq.2yrs`: The number of times the borrower has been 30+ days past due on a payment in the past 2 years.
- `pub.rec`: The borrower's number of derogatory public records.

### Data Preprocessing

Data preprocessing includes handling missing values, encoding categorical variables using `pd.get_dummies`, and other necessary data transformations.

### Exploratory Data Analysis

Seaborn is used for initial data exploration and visualization to gain insights into the dataset.

### Model Training and Evaluation

Two classification algorithms, DecisionTreeClassifier and RandomForestClassifier, are employed to train the predictive models. Model performance is evaluated using confusion matrices and classification reports to measure accuracy.


## Repository Files

Here's a list of the files in this repository:

1. `loan_repayment_prediction.ipynb` - Jupyter Notebook containing the code for the machine learning project.
2. `data.csv`-  Dataset in CSV format.
3. `LICENSE` - The MIT License file for this project.
