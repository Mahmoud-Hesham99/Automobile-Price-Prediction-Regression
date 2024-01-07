# Automobile Price Prediction

## Overview

This project focuses on predicting automobile prices using various regression models. The analysis covers a range of tasks, including data loading and preprocessing, exploratory data analysis, feature selection, and model development. The goal is to build an accurate and robust predictive model for automobile prices.

## Contents

1. **Data Loading and Data Types Fixing:**
   - The dataset is loaded into the notebook, and data types are adjusted to ensure proper handling of features.

2. **Data Wrangling:**
   - Missing data is addressed, and strategies for imputation are implemented.
   - Data standardization and binning are performed to prepare the dataset for modeling.

3. **Feature Selection:**
   - Individual feature patterns are analyzed using visualizations and descriptive statistical analysis.
   - Correlation and causation between features are explored.
   - ANOVA analysis is conducted to understand the relationships between categorical variables and the target variable.

4. **Model Development:**
   - Multiple Linear Regression is implemented for initial modeling.
   - A Polynomial Second Degree model is constructed to capture non-linear relationships.
   - Model evaluation includes visualization, R-squared, and RMSE metrics.
   - Ridge and Lasso regularization techniques are applied to improve the polynomial model's performance.
   - Random Forest Regressor is explored as an alternative model.

## Model Selection

After thorough evaluation, the Lasso Regularization Polynomial Model is selected as the best-performing model. The decision is based on comprehensive analyses, including visualization insights and metrics like R-squared and RMSE.

## Next Steps

Future iterations of this project could include:

- Further exploration of hyperparameter tuning for the selected models.
- Experimentation with additional machine learning algorithms.
- Deployment of the predictive model for real-world applications.

Feel free to explore the notebook for detailed code implementations and visualizations.

