# Data Science Project: Global AI Index Insights and Forecasting

This project provides data-driven insights into the **Global AI Index** (2023 edition), analyzing how countries perform in the AI landscape and forecasting their future performance using regression models.

---

## Repository Structure

```plaintext
Global-AI-Index-Insights-and-Forecasting/
│
├── Dataset/                             # Contains the uncleaned and cleaned AI Index dataset
│   └── AI_index_db.csv
|   └── AI_index_db_unclean.csv          
│
├── Data Cleaning & Wrangling.ipynb     # Preprocessing and data cleaning steps
├── EDA.ipynb                           # Exploratory Data Analysis
├── Prediction.ipynb                    # Regression modeling and forecasting
└── README.md                           # Project overview and documentation

```
## Dataset

- **Source:** AI Index Dataset (2023 Edition)
- **Description:** Contains country-wise AI-related metrics including *talent*, *infrastructure*, *operating environment*, *research*, *development*, *commercial*, and *government strategy*.
- **Target Variable:** `total_score` (Overall AI readiness/performance score)

---

## Project Objectives

- Understand and visualize key trends in global AI development.
- Identify top-performing and underperforming countries.
- Predict the `total_score` for a country using machine learning models.

---

## Notebooks Overview

### `Data Cleaning & Wrangling.ipynb`
- Handles missing values, renaming, normalization, and feature selection.
- Ensures data consistency for modeling.

### `EDA.ipynb`
- Visualizes correlations and distributions.
- Highlights influential features using plots and statistics.

### `Prediction.ipynb`
- Builds and evaluates multiple regression models:
  - **Linear Regression**
  - **Decision Tree Regressor**
  - **Random Forest Regressor**
  - **Neural Network Regressor (MLP)**
- Metrics used: `R² Score`, `MAE`, `MSE`, and `RMSE`.
