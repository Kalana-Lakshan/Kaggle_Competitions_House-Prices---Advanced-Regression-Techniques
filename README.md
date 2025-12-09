# House Prices — Advanced Regression Techniques

This repository contains my work for the Kaggle competition "House Prices: Advanced Regression Techniques" (https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques). It includes data, multiple Jupyter notebooks exploring different modelling approaches, and final submission files.

## Repository structure

- House_Prices_Advanced_Regression_Techniques.ipynb — Main exploratory analysis and baseline modelling.
- House_Prices_Advanced_Regression_Techniques_Advanced_techniques_used.ipynb — Advanced feature engineering and modelling experiments.
- House_Prices_Advanced_Regression_Techniques_with_catboost.ipynb — CatBoost-based modelling pipeline and final CatBoost experiments.
- train.csv, test.csv — Original competition data.
- data_description.txt — Data dictionary from the competition.
- sample_submission.csv — Sample submission file provided by Kaggle.
- submission*.csv, submission_catboost_*.csv — Final and intermediate submission files produced during the experiment.
- LICENSE — Repository license.

## Competition

Kaggle competition page: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques

This competition's goal is to predict house sale prices (SalePrice) using tabular features describing residential homes in Ames, Iowa.

## Results (current)

- Kaggle username: Herath Mudiyanselage Kalana Lakshan
- Public leaderboard rank by 2025/09/12: 675
- Best public score: 0.12257 (Your Best Entry!)
- Most recent submission score: 0.12353

Note: scores are Root Mean Squared Logarithmic Error (RMSLE) as used in the competition.

## Notebooks and approach

I organized the work into multiple notebooks:

- Exploratory Data Analysis (EDA): data quality checks, missing value handling, initial feature understanding and visualization.
- Baseline models: simple pipelines using linear regression, ridge, lasso and tree-based models to establish a baseline.
- Feature engineering: transformation of skewed features, creation of new features, encoding categorical variables, and sophisticated imputation strategies.
- Advanced models and ensembling: gradient boosting (XGBoost/LightGBM/CatBoost), stacking/ensembling techniques and hyperparameter tuning.

The CatBoost notebook contains a production-friendly pipeline and produced the best submissions in this repository.

## Reproduce results / Usage

1. Clone the repository:

   git clone https://github.com/Kalana-Lakshan/Kaggle_Competitions_House-Prices---Advanced-Regression-Techniques.git

2. Install dependencies (recommended to use a virtual environment or conda):

   pip install -r requirements.txt

   If a requirements file is not present, common packages used are:
   - numpy
   - pandas
   - scikit-learn
   - matplotlib
   - seaborn
   - xgboost
   - lightgbm
   - catboost
   - jupyter

3. Place the original competition data files (train.csv, test.csv) in the repository root (already included here).

4. Open and run the notebooks in the order you prefer. The CatBoost notebook contains a single pipeline to generate a submission CSV.

Notes:
- For long-running hyperparameter tuning, consider running on a machine with more CPU/RAM or on Kaggle/Colab with GPU support if using libraries that can leverage it.
- Random seeds are set in notebooks for reproducibility; nonetheless results may vary slightly across environments.

## Files of interest

- submission_catboost_final.csv — Final CatBoost submission.
- submission_catboost_optimized.csv — Submission produced after hyperparameter tuning.
- submission*.csv — Additional candidate submissions stored for record.

## License

This project is licensed under the terms in the LICENSE file in the repository root.

## Contact

Herath Mudiyanselage Kalana Lakshan — GitHub: @Kalana-Lakshan

If you want to reproduce specific experiments or need help running the notebooks, open an issue or contact me directly.
