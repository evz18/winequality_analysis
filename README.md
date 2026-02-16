# Wine Quality Analysis (PCA + Regression)

## Overview
This project analyzes a wine quality dataset using exploratory visualization, dimensionality reduction with PCA, and linear regression to evaluate predictive performance.

## Methods
- Feature distribution histograms and feature–target scatter plots
- Standardization (StandardScaler)
- Principal Component Analysis (PCA)
- Linear Regression
- 5-fold Cross-Validation (RMSE)

## Results
- Baseline Linear Regression CV RMSE: **0.7504**
- PCA + Linear Regression (k=8) CV RMSE: **0.7919**

## Key Insight
While PCA provided a low-dimensional representation with decent predictive performance, the full-feature linear model achieved the strongest predictive accuracy for this dataset.

## Future Work
- Compare against Ridge/Lasso regression and nonlinear models
- Treat wine quality as an ordinal classification problem
- Use nested cross-validation for model selection
