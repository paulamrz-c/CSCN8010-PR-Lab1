# CSCN8010 - Practical Lab 1: Univariate Linear Regression

Welcome to my repository for **Lab 1 - Univariate Linear Regression on California Housing Prices**.

This repository contains:

### 📓 - The Jupyter Notebook  
The notebook `lab1_univariate_regression.ipynb` follows a full machine learning workflow:
- Framing the problem
- Exploratory Data Analysis (EDA)
- Training three separate univariate linear regression models:
  - Median Income
  - Population
  - Households
- Comparing model performance using MSE, RMSE, MAE, and R²
- Visualizing regression lines and residuals
- Drawing conclusions on the best model for predicting house values

### HTML Export (for GitHub Pages)
You can view the published notebook [here](https://paulamrz-c.github.io/CSCN8010-PR-Lab1/Univariate_PR_California_Housing.html)

### Dataset
The dataset California Housing Dataset is available in: https://www.kaggle.com/datasets/camnugent/california-housing-prices


---

## 🚀 Quick Start

```bash
python -m venv venvPR
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
.\venvPR\Scripts\activate
pip install -r requirements.txt
python -m ipykernel install --user --name=venv --display-name "Python PR (venv)"
jupyter notebook

```
