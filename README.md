# Fuel-Economy
Project Title: Fuel Economy Analysis and Prediction

Project Overview

This project analyzes fuel economy (measured in miles per gallon, MPG) using a dataset of automobile specifications. It involves data preprocessing, exploratory data analysis (EDA), feature engineering, and predictive modeling to understand the relationships between vehicle attributes and fuel efficiency.

Objectives

Clean and preprocess raw data, handling missing values and converting categorical features.
Explore statistical properties of fuel economy and visualize key relationships.
Identify correlations between vehicle attributes (e.g., weight, horsepower, displacement) and MPG.
Train predictive models to estimate fuel efficiency using regression techniques.
Evaluate model performance using metrics like R² and Mean Absolute Error (MAE).
Technologies & Tools
Programming Language: Python
Libraries: Pandas, NumPy, Matplotlib, Seaborn, Statsmodels, Scikit-learn

Key Features & Methodology

Data Preprocessing

Load dataset and inspect data types, missing values, and unusual entries.
Convert categorical variables (e.g., 'origin') and handle missing numerical values in 'horsepower'.
Create additional features such as squared weight to capture non-linear relationships.

Exploratory Data Analysis (EDA)

Compute summary statistics and visualize MPG distribution.
Generate scatter plots and correlation heatmaps to examine relationships between variables.

Feature Engineering & Model Training

Prepare features for regression models, including polynomial terms and dummy variables.
Use Ordinary Least Squares (OLS) regression and Ridge Regression to predict MPG.
Apply cross-validation (K-Fold) to assess model generalization.

Model Evaluation

Calculate R² and MAE to measure model accuracy.
Perform residual analysis to check for normality and model assumptions.

Results & Insights

Identified key predictors of fuel economy, with weight showing the strongest negative correlation with MPG.
Ridge regression provided robust performance with optimized hyperparameters.
Cross-validation confirmed the stability of the predictive models.
Future Enhancements
Implement additional machine learning models (e.g., Decision Trees, Random Forests).
Expand the dataset with modern vehicle data for improved generalization.
Deploy the model as a web-based fuel economy predictor.
