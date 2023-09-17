# Liver-Cirrhosis-Prediction-using-XGBoost


## Overview
This repository contains the code and analysis for a machine learning project aimed at predicting liver cirrhosis using patient lab test results and medical history data. The data was collected by May Clinic. It can be found [here](https://www.mayo.edu/research/documents/pbcseqhtml/doc-10027141).

## Project Highlights
- Conducted thorough exploratory data analysis on a comprehensive dataset comprising over 400 patients' records, gaining valuable insights into feature relationships and patterns.

- Employed robust data preprocessing techniques, including missing value imputation, categorical variable encoding, and feature engineering, to ensure data quality and model performance.

- Implemented a comparative study of two classification algorithms: Logistic Regression and XGBoost, utilizing stratified k-fold cross-validation to evaluate their predictive performance.

- Achieved a commendable ~74% accuracy rate and a strong ROC AUC score of 0.74 by fine-tuning the XGBoost model, demonstrating its superior predictive power.

- Created informative SHAP (SHapley Additive exPlanations) feature importance plots to provide interpretable insights into the model's decision-making process.

## Requirements
- Python 3.x
- Common data science libraries including Pandas, Numpy, Scikit-learn, XGBoost, SHAP, and others. Refer to the Jupyter notebooks for specific library usage details.
