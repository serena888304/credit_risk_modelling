# credit_risk_modelling
Credit risk modeling project in Python covering preprocessing, PD modeling, validation, scorecard development, and monitoring.

## Credit Risk Modeling in Python

A data science project focused on building a complete credit risk modeling workflow in Python, covering data preprocessing, feature engineering, model development, validation, and long-term model monitoring.

> **Project Status:** In Progress  
> Current stage: preprocessing and preparing the test dataset for probability of default modeling.

## Project Overview

This project is a practical credit risk modeling case study based on a real-world style loan dataset. The objective is to develop a structured machine learning workflow that can estimate borrower credit risk and support risk-based decision-making.

The project follows a full credit risk modeling lifecycle, beginning with raw data preprocessing and continuing toward probability of default modeling, model validation, scorecard development, and model maintenance.

## Business Context

Credit risk modeling is widely used by banks, lenders, and financial institutions to estimate the likelihood that a borrower will default on their obligations.

A strong credit risk model helps financial institutions:

- Assess borrower default risk.
- Improve lending and approval decisions.
- Support risk-based pricing.
- Monitor portfolio quality.
- Comply with regulatory expectations.
- Maintain model performance over time.

This project applies Python-based data science techniques to simulate a real credit risk modeling workflow from raw data to model-ready datasets.

## Project Objectives

The main objectives of this project are to:

- Understand the structure and quality of the loan dataset.
- Clean and preprocess raw credit risk data.
- Engineer model-ready features from borrower, loan, and credit history variables.
- Apply credit risk modeling concepts such as Weight of Evidence and Information Value.
- Build a Probability of Default model using logistic regression.
- Evaluate model performance using industry-standard validation metrics.
- Develop a scorecard-style framework for interpretable credit risk assessment.
- Prepare for model monitoring and population stability analysis.

## Planned Workflow

The full project workflow includes the following stages:

1. **Data Import and Initial Exploration**
   - Load raw loan data.
   - Inspect column names, data types, missing values, and target distribution.

2. **Data Preprocessing**
   - Clean raw variables.
   - Handle missing values.
   - Transform categorical variables.
   - Create dummy variables.
   - Group categories using credit risk logic.
   - Align train and test datasets.

3. **Feature Engineering**
   - Apply fine classing and coarse classing.
   - Calculate Weight of Evidence.
   - Calculate Information Value.
   - Select predictive variables for modeling.

4. **Probability of Default Modeling**
   - Build a logistic regression model.
   - Estimate borrower-level default probabilities.
   - Interpret coefficients and risk drivers.

5. **Model Validation**
   - Evaluate model performance using:
     - ROC Curve
     - Area Under the Curve
     - Gini Coefficient
     - Kolmogorov-Smirnov statistic
     - Confusion matrix
     - Accuracy and classification metrics

6. **Scorecard Development**
   - Convert logistic regression outputs into a credit scorecard.
   - Assign points to borrower characteristics.
   - Create interpretable risk scores.

7. **Model Monitoring and Maintenance**
   - Assess population stability.
   - Monitor changes in borrower distribution.
   - Evaluate model drift over time.
   - Prepare for future recalibration.

## Tools and Technologies

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries:**
  - pandas
  - NumPy
  - scikit-learn
  - statsmodels
  - matplotlib
  - seaborn

## Credit Risk Concepts Covered

This project is designed to apply both data science and credit risk modeling concepts, including:

- Probability of Default
- Logistic Regression
- Weight of Evidence
- Information Value
- Fine Classing
- Coarse Classing
- Scorecard Development
- ROC Curve
- AUC
- Gini Coefficient
- Kolmogorov-Smirnov Statistic
- Population Stability Index
- Model Monitoring
