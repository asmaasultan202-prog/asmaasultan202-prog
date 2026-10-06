# Tips Prediction using Linear Regression Models

## Overview
This repository contains a machine learning workflow to predict restaurant tips based on customer data using the Seaborn `tips` dataset.

## Workflow
1. **EDA**: Visualizing relationships using boxplots.
2. **Preprocessing**: 
   - `StandardScaler` for numeric features.
   - `OneHotEncoder` for categorical features.
   - Used `Pipeline` and `ColumnTransformer` to avoid data leakage.
3. **Modeling**: Trained and evaluated Linear Regression, Ridge, and Lasso models.
4. **Evaluation**: Compared models using MAE, MSE, RMSE, and R2 Score on train and test datasets.