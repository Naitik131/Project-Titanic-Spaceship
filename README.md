# Project-Titanic-Spaceship
# 🚀 Spaceship Titanic - Kaggle Project

This repository contains my solution for the [Spaceship Titanic](https://www.kaggle.com/competitions/spaceship-titanic) Kaggle competition, where the goal is to predict whether passengers were transported to another dimension after the spaceship collision.

## 📂 Structure
- `train.csv`, `test.csv`, `sample_submission.csv` → Kaggle datasets (not uploaded due to rules).
- `notebooks/` → Jupyter notebooks for EDA, feature engineering, and modeling.
- `submission.csv` → Final Kaggle submission.
- `requirements.txt` → Python dependencies.

## 🧑‍💻 Approach
- **Preprocessing**: handled missing values, one-hot encoded categorical features, engineered features like `TotalSpend`, and split `Cabin` into `Cabin1`, `CabinNo.`, and `Cabin2`.
- **Models**: Logistic Regression → Random Forest → XGBoost.  
- **Validation**: used K-Fold Cross Validation, evaluated with Accuracy.  
- **Submission**: best score achieved with XGBoost after hyperparameter tuning.

## 📊 Results
- Local validation accuracy: ~`80%`  
- Kaggle Public LB: ~`79.8%`  

