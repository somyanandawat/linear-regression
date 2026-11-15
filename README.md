# Linear and Polynomial Regression — Data Science & Machine Learning

My hands-on implementation of Linear Regression, Multiple Linear Regression, and Polynomial Regression as part of my Data Science and Machine Learning learning journey.

This repository documents my practical learning through Python, Jupyter Notebook, real-world-style datasets, model training, prediction, evaluation, and residual analysis.

## Concepts Covered

- Introduction to Linear Regression
- Simple and Multiple Linear Regression
- Introduction to Non-Linear Relationships
- Polynomial Regression
- Independent and dependent variables
- Slope, intercept, and regression coefficients
- Best-fit line and Ordinary Least Squares (OLS)
- Model training and prediction
- Polynomial feature transformation
- Model evaluation metrics (R², Adjusted R², RMSE)
- Residual analysis
- Multicollinearity and Variance Inflation Factor (VIF)
- Linear vs. Polynomial Regression comparison

## Case Studies and Implementations

### 1. Newspaper Circulation Prediction — Simple Linear Regression

- Predict Sunday newspaper circulation using daily newspaper circulation.
- Fit a regression model using `statsmodels` Ordinary Least Squares (OLS).
- Explore model coefficients, t-values, and p-values.
- Evaluate model fit using R-squared and Adjusted R-squared.
- Generate predictions for new daily circulation values.

### 2. Store Sales Prediction — Simple Linear Regression

- Predict daily sales based on store footfalls.
- Train a Linear Regression model using `scikit-learn`.
- Understand model coefficients (slope) and intercept.
- Generate predictions for individual and multiple new footfall values.

### 3. Advertising Sales Prediction — Multiple Linear Regression

- Predict sales using TV, Radio, and Newspaper advertising budgets.
- Explore relationships between advertising channels and sales.
- Perform correlation analysis and visualize relationships using a heatmap.
- Check multicollinearity using Variance Inflation Factor (VIF).
- Split data into training and testing sets.
- Train a Multiple Linear Regression model.
- Generate predictions and compare actual vs. predicted sales.

### 4. Advertising Sales Prediction — Polynomial Regression

- Understand when Multiple Linear Regression may not capture non-linear relationships.
- Identify non-linear patterns through data exploration and scatter plots.
- Use TV and Radio advertising features to predict non-linear sales.
- Train and evaluate a Linear Regression baseline model.
- Apply Polynomial Feature Transformation (Degree 2).
- Generate polynomial features using `PolynomialFeatures`.
- Train a Polynomial Regression model using `scikit-learn`.
- Evaluate models using R-squared and RMSE.
- Analyse residual plots.
- Compare Linear Regression and Polynomial Regression performance.

## Technologies and Libraries Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn

## Repository Structure

```text
linear-regression/
│
├── 01_Linear_Regression.ipynb
├── 02_Multiple_Linear_Regression.ipynb
├── 03_Polynomial_Regression.ipynb
│
├── General_Stores.csv
├── NewspaperData.csv
├── advertising.csv
├── advertising_nonlinear.csv
│
└── README.md
```

## Learning Objective

Build a practical understanding of regression algorithms by applying them to real-world-style prediction problems.

The objective is to understand how regression models work, interpret their results, evaluate model performance, analyse residuals, and explore how polynomial feature transformation can help model non-linear relationships.

*Learning step by step, one model at a time.* 🚀
