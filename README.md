# Fraud Detection using Ensemble Learning

![Fraud Detection](https://cdn.prod.website-files.com/5fbe376a36d4106214faaf3c/62200f9fbd736d0bb2002721_20220302-Credit%20Card%20Fraud%20Detection_Blog%20Thumbnail%20Image.png)

## Overview

This project aims to detect fraudulent transactions in financial datasets using ensemble learning techniques. Fraud detection is crucial for minimizing financial losses and improving the security of payment systems. We applied machine learning models to identify patterns in transaction data that indicate fraudulent behavior.

As part of the project, I've also visualized the data to better understand feature distributions, correlations, and class imbalance, helping us guide the feature engineering and model selection process.

## Key Features

- **Models Used**: RandomForest, AdaBoost, CatBoost, XGBoost, and LightGBM.
- **Best Performance**: XGBoost achieved an AUC of 0.974, and LightGBM achieved 0.93 using cross-validation.
- **Feature Engineering**: Enhanced model performance by creating additional features from raw transaction data.

## Results

- XGBoost: AUC 0.974 on validation set
- LightGBM: AUC 0.93 using cross-validation

