# 🏠 House Prices: Advanced Regression Techniques

This repository contains a complete solution for the Kaggle competition
**"House Prices: Advanced Regression Techniques"**.\
The goal is to predict the final sale price of residential homes in
Ames, Iowa using advanced regression and feature engineering techniques.

This repository includes: - The **full solution notebook** - The **four
original competition files** - The **final submission file**

------------------------------------------------------------------------

## 📂 Repository Contents

  ------------------------------------------------------------------------------------------------------
  File                                                  Description
  ----------------------------------------------------- ------------------------------------------------
  `House_Prices_Advanced_Regression_Techniques.ipynb`   Complete solution notebook

  `train.csv`                                           Training dataset

  `test.csv`                                            Test dataset

  `sample_submission.csv`                               Submission format

  `data_description.txt`                                Official dataset description

  `submission.csv`                                      Final generated predictions

  `README.md`                                           Project documentation
  ------------------------------------------------------------------------------------------------------

------------------------------------------------------------------------

## 📌 Problem Description

Predict the **final SalePrice** of houses using **79 explanatory
variables** describing almost every aspect of residential homes,
including: - Lot size - Neighborhood - Building quality - Year built /
remodeled - Basement and garage details - Interior features

Target column: - `SalePrice` --- Final selling price of the house (USD)

------------------------------------------------------------------------

## 🎯 Objective

Build a regression model that: - Learns from the training dataset -
Predicts sale prices for unseen data - Minimizes **Root Mean Squared
Error (RMSE)**

------------------------------------------------------------------------

## 🧠 Evaluation Metric

The competition uses **Root Mean Squared Error (RMSE)** on logarithmic
values:

RMSE = sqrt( (1/n) \* Σ ( log(y) − log(y_hat) )² )

Lower RMSE indicates better performance.

------------------------------------------------------------------------

## 🔧 Solution Workflow

1.  **Exploratory Data Analysis (EDA)**
    -   Study feature distributions
    -   Identify missing values and outliers
    -   Analyze correlations
2.  **Data Cleaning**
    -   Handle missing values
    -   Fix incorrect data types
    -   Treat outliers
3.  **Feature Engineering**
    -   Encoding categorical features
    -   Log-transform skewed numerical features
    -   Create new derived features
4.  **Model Training**
    -   Baseline Linear Regression
    -   Regularized models (Ridge, Lasso)
    -   Random Forest / Gradient Boosting
5.  **Model Evaluation**
    -   Cross-validation
    -   RMSE scoring
6.  **Prediction & Submission**
    -   Generate predictions for test data
    -   Create `submission.csv`
    -   Upload to Kaggle leaderboard

------------------------------------------------------------------------

## 🛠️ Technologies Used

-   Python 3
-   NumPy
-   Pandas
-   Matplotlib
-   Scikit-learn
-   Jupyter Notebook

------------------------------------------------------------------------

## ▶️ How to Run

1.  Open the notebook:

        House_Prices_Advanced_Regression_Techniques.ipynb

2.  Make sure the following files are in the same directory:

    -   `train.csv`
    -   `test.csv`
    -   `sample_submission.csv`
    -   `data_description.txt`

3.  Run all cells in order.

4.  The final submission file will be generated as:

        submission.csv

------------------------------------------------------------------------

## 📈 Output Format

The output CSV is in the format:

Id,SalePrice\
1461,169000\
1462,187500\
...

------------------------------------------------------------------------

## 🏆 Competition Link

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

------------------------------------------------------------------------

## ✍️ Author

Created for educational and machine learning practice purposes.

------------------------------------------------------------------------

## 📄 License

This project is intended strictly for learning and academic use.
