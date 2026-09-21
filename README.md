# YouTube Revenue Analysis

## Project Overview

This project analyzes YouTube channel performance data to identify the factors associated with YouTube revenue using Python and data analysis techniques.

The analysis focuses on exploring relationships between video performance metrics and estimated revenue, followed by the development and evaluation of machine learning regression models.

## Objectives

- Explore the YouTube channel performance dataset.
- Clean and prepare the data for analysis.
- Perform exploratory data analysis (EDA).
- Identify factors associated with estimated revenue.
- Analyze correlations between revenue and performance metrics.
- Build regression models to predict estimated revenue.
- Evaluate model performance using appropriate regression metrics.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Project Workflow

1. Data Loading
2. Data Inspection
3. Data Cleaning and Preprocessing
4. Exploratory Data Analysis
5. Correlation Analysis
6. Revenue Factor Analysis
7. Feature Preparation
8. Linear Regression
9. Random Forest Regression
10. Model Evaluation

## Exploratory Data Analysis

The analysis examines relationships between estimated revenue and different YouTube performance metrics, including views, watch time, video duration, monetized playbacks and other available channel performance variables.

Visualizations and statistical analysis were used to identify patterns and relationships within the dataset.

## Machine Learning

Two regression approaches were explored:

- Linear Regression
- Random Forest Regression

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Key Findings

The analysis identified several YouTube performance-related variables that show relationships with estimated revenue.

Correlation analysis and regression modelling were used to investigate which available factors were associated with revenue.

The notebook also considers the potential influence of revenue-related variables that may introduce target leakage when used as predictors.

## Repository Contents

```text
youtube-revenue-analysis/
│
├── README.md
└── Youtube_Revenue.ipynb
