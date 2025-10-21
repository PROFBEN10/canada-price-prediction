### Canada Per Capita Income Prediction Using Simple Linear Regression
# Overview
This project demonstrates how to use Simple Linear Regression (SLR) to predict Canada’s per capita income based on historical data. The notebook walks through data preprocessing, model training, visualization, and prediction using Python’s popular data science libraries.

The goal is to provide a clear, beginner-friendly yet professional example of applying a regression model to real-world economic data.

# Project Motivation
Understanding income growth trends is crucial for economic forecasting, policy formulation, and investment planning.

This project was inspired by the need to build a simple yet interpretable machine learning model capable of predicting future income trends based on past data.

# Dataset Description
The dataset used is canada_per_capita_income.csv, which contains two main columns:

year: The year of observation

per capita income (US$): Canada’s per capita income in U.S. dollars

The dataset is small, clean, and ideal for demonstrating a regression workflow.

## Methodology
# Data Loading and Preparation

Read CSV data using pandas

Converted data into a DataFrame

Exploratory Data Analysis (EDA)

Visualized trends with Matplotlib and Seaborn

Observed a clear upward trend in per capita income over the years

# Model Training

Applied Simple Linear Regression using sklearn.linear_model.LinearRegression

Trained the model on year as the independent variable and per capita income (US$) as the dependent variable

# Model Evaluation

Plotted regression line vs. actual data

Used the trained model to predict income for future years

# Future Improvements

Incorporate multiple variables (e.g., GDP growth rate, inflation, population) to build a Multiple Linear Regression model.

Evaluate model performance using R², MAE, and RMSE metrics.

Deploy the model as a simple web app using Streamlit or Flask.
