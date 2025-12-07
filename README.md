# IntroMLCapstone
Capstone project: House price prediction using classical ML and research-based models
# IntroMLCapstone – Housing Price Prediction

## 1. Project Overview
This repository contains the code for my Intro to Machine Learning capstone project:
**House Price Prediction Using Classical Machine Learning and Research-Based Models: A Reproduction and Comparative Study.**

The goal is to predict house prices on the Kaggle dataset
**"House Prices: Advanced Regression Techniques"** using:
- 3 classical ML models learned in class
- 2 models inspired by recent research papers

## 2. Dataset
- Source: Kaggle – House Prices: Advanced Regression Techniques  
  https://www.kaggle.com/c/house-prices-advanced-regression-techniques
- Files used: `train.csv`, `test.csv`
- Note: Due to size / license, these files are **not included** here.  
  Please download them from Kaggle and place them in the working directory (or `/content/` in Colab).

## 3. Files in This Repository

- `01_linear_regression.ipynb`  
  Implements classic **Linear Regression** with preprocessing and evaluation (MSE, RMSE, MAE).

- `02_polynomial_ridge.ipynb`  
  Implements **Polynomial Features + Ridge Regression**, including hyperparameter tuning over α and comparison of degrees.

- `03_neural_network.ipynb`  
  Implements a **Neural Network Regressor** (Keras/TensorFlow) with train/validation split, learning curves, and performance metrics.

- `04_random_forest_paper.ipynb`  
  Reimplements the **Random Forest** approach from the paper by Sharma et al. (2024), including feature selection, hyperparameter tuning, and evaluation.

- `05_xgboost_paper.ipynb`  
  Reimplements the **XGBoost**-based model from literature, with grid search, residual analysis, and feature importance.

## 4. How to Run

### Option A: Google Colab
1. Upload a notebook (e.g., `01_linear_regression.ipynb`) to Google Colab.
2. Upload `train.csv` and `test.csv` or mount your Google Drive and point to the files.
3. Run all cells from top to bottom.

### Option B: Local (Jupyter Notebook)
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/IntroMLCapstone.git
   cd IntroMLCapstone
