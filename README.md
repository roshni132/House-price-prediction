# House-price-prediction
# California House Price Prediction

## Overview
This repository contains an end-to-end Machine Learning project that predicts house prices using the famous **California Housing Dataset**. The goal of this project is to build, evaluate, and analyze a **Linear Regression** model to understand the complete machine learning workflow.

## Objectives
* Load and preprocess the dataset.
* Perform Exploratory Data Analysis (EDA) to find correlations.
* Train a standard Linear Regression model.
* Evaluate the model using standard metrics (MAE, RMSE, R²).

## Tech Stack Used
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

## Key Findings
* **Feature Correlation:** The EDA revealed that Median Income has the strongest positive correlation with house prices.
* **Data Capping:** During visualization, a strict ceiling was observed in the actual prices exactly at the $500,000 mark. This real-world data collection cap affects the linear model's predictions.

## Model Performance
The Linear Regression model was evaluated on a 20% unseen testing split:
* **Mean Absolute Error (MAE):** 0.533
* **Root Mean Squared Error (RMSE):** 0.746
* **R-squared (R²) Score:** 0.576

## How to View the Project
Simply click on the `Housepriceprediction.ipynb` file in this repository to view the complete code, exploratory data analysis, and result graphs (Actual vs. Predicted and Residual plots).
