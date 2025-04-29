# BICUP Soft Drink Demand Forecasting

## Overview

This repository contains a time series analysis and forecasting project focused on predicting 15-minute interval demand for a soft drink product. The analysis utilizes the BICUP competition dataset.

## Objective

The primary goal was to:
1.  Analyze high-frequency demand data to identify patterns like seasonality, trend, and volatility.
2.  Develop and evaluate several time series forecasting models.
3.  Generate a reliable 2-week demand forecast based on the best-performing model.

## Dataset

*   **Source:** `bicup.xlsx` (BICUP  competition data)
*   **Frequency:** 15-minute intervals
*   **Duration:** ~3 weeks (March 1st - March 21st, 2005)

## Key Steps & Techniques

*   **Data Cleaning & Preprocessing:** Handling missing values, ensuring time series continuity, removing duplicates.
*   **Exploratory Data Analysis (EDA):** Visualizing patterns using time series plots, rolling averages, hourly/daily aggregations, and box plots.
*   **Time Series Analysis:** Stationarity testing (ADF), seasonal decomposition.
*   **Modeling:** Training and evaluating SARIMA, Holt-Winters Exponential Smoothing, and Prophet models.
*   **Evaluation:** Comparing models using MAE, MSE, and RMSE on a held-out test set.
*   **Forecasting:** Generating a 2-week forecast with confidence intervals using the best model.

## Models Evaluated

*   SARIMA (Statsmodels)
*   Holt-Winters Exponential Smoothing (Statsmodels)
*   Prophet (Prophet library)

## Key Finding

The Prophet model demonstrated the best performance on the test set based on RMSE.

## Repository Contents

*   `bicup_jupyter_notebook.ipynb`: The main Jupyter Notebook containing the Python code for data loading, cleaning, EDA, modeling, evaluation, and visualization.
*   `bicup_demand_forecasting_report.pdf`: A detailed report summarizing the analysis, findings, model comparison, and business recommendations.
*   `bicup2006.xlsx`: The dataset used for this analysis.
*   *`bicup_demand_forecasting.pdf` : Notebook pdf

## Portfolio Link

For a more detailed project description and portfolio presentation, ckeck out:
**https://lapis-school-f5e.notion.site/Forecasting-Soft-Drink-Demand-A-Time-Series-Modeling-Challenge-1e4ca101e46980c3bae1dce842751774?pvs=4**

## Tech stack

*   Python
*   Pandas
*   NumPy
*   Matplotlib
*   Seaborn
*   Statsmodels
*   Prophet
*   Jupyter Notebook
