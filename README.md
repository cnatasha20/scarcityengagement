# The Effects of Scarcity on Engagement: Analyzing Review Volume in Beauty E-Commerce

# Contents
- scarcityengagement.Rmd: Full R Markdown workflow
  - Data Cleaning & Preprocessing
  - Descriptive Statistics
  - Statistical Analysis
  - Predictive Modeling
  - Brand Residualization
  - Feature Importance Analysis
 
# Methods
- Target: log-transformed review count
- Features: scarcity tags + brand, price, primary category, newness, stock
- Tuning: Optuna, 5 fold cross-validation
- Evaluation: Averaged COR, R2, RMSE, MAE, MinMaxAcc over 10x random splits

# Requirements
- Built with R.4.2.3.
- Key packages: caret, glmnet, e1071, randomForest, xgboost, iml, Optuna, reticulate, tidyverse, corrplot, car, Metrics

# Usage
- Download scarcityengagement.Rmd
- Download product_info.csv from https://www.kaggle.com/datasets/nadyinky/sephora-products-and-skincare-reviews/data
- Open scarcityengagement.Rmd in RStudio
- Run all codes to reproduce results

# Acknowledgements
ChatGPT (OpenAI) and Gemini (Google) were used to optimize coding and assist with troubleshooting.
