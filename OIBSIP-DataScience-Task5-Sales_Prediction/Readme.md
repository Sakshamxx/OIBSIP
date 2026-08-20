
# Sales Prediction Using Python

## Overview

A machine learning regression project that predicts product sales based on advertising expenditure across TV, Radio, and Newspaper channels.

The project uses exploratory data analysis, feature selection, outlier handling, regularization, and regression models to identify the best approach for predicting sales.

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Import libraries
2. Load and understand the dataset
3. Data cleaning and preparation
4. Exploratory Data Analysis
5. Visualize advertising spend vs. sales
6. Correlation analysis
7. Outlier detection and removal
8. Feature selection
9. Train-test split
10. Train regression models
11. Evaluate models using MAE, RMSE and R²
12. Compare model performance
13. Analyze residuals
14. Analyze feature impact
15. Select the best model
16. Make a final sales prediction

## Dataset

The project uses an advertising dataset containing spending on:

- TV
- Radio
- Newspaper

along with the corresponding **Sales**.

## Models Used

- Linear Regression
- Ridge Regression
- Random Forest Regressor

Ridge Regression is included to introduce regularization and reduce the risk of overfitting.

## Evaluation Metrics

The models are evaluated using:

- MAE — Mean Absolute Error
- RMSE — Root Mean Squared Error
- R² Score

## Objective

The main objective is to understand the relationship between advertising expenditure and product sales and build a regression model capable of predicting sales for a new advertising campaign.

## Result

The trained models are compared using multiple regression metrics, and the best-performing model is selected based on its predictive performance.

## Folder Structure

```text
DataScience-Task5-SalesPrediction/
│
├── Main.ipynb
├── Advertising_Budget_and_Sales.csv
└── README.md
```
