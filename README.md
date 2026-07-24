#  Car Sales Price Prediction using Linear Regression

##  Project Overview

This project focuses on building a Linear Regression model to predict car sales using historical automobile data. The project follows a complete Machine Learning workflow, including data cleaning, exploratory data analysis (EDA), feature engineering, variable selection, model building, and performance evaluation.

The objective is to identify the key factors influencing car sales and develop a predictive model that supports data-driven business decisions.

---

##  Business Objective

The goal of this project is to analyze various vehicle characteristics and build a Linear Regression model to predict **Sales in Thousands**.

The project aims to answer questions such as:

- Which vehicle attributes influence sales the most?
- How do engine size, horsepower, and price affect sales?
- Which variables are statistically significant?
- How accurately can sales be predicted using Linear Regression?

---

##  Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Scikit-learn

---

##  Dataset

The dataset contains automobile information with the following features:

- Manufacturer
- Model
- Sales_in_thousands (Target Variable)
- Four_year_resale_value
- Vehicle_type
- Price_in_thousands
- Engine_size
- Horsepower
- Wheelbase
- Width
- Length
- Curb_weight
- Fuel_capacity
- Fuel_efficiency
- Latest_Launch
- Power_perf_factor

---

# 📋 Project Workflow

## 1️ Data Understanding

- Imported the dataset
- Explored dataset structure
- Checked data types
- Generated descriptive statistics

---

## 2️ Data Cleaning

Performed data preprocessing including:

- Missing value treatment
- Duplicate value checking
- Data type corrections
- Outlier detection
- Feature consistency checks

---

## 3️ Exploratory Data Analysis (EDA)

Performed detailed EDA to understand the relationships between variables.

### Univariate Analysis

- Distribution plots
- Histograms
- Boxplots

### Bivariate Analysis

- Scatter plots
- Correlation analysis
- Sales vs Numerical Features

### Multivariate Analysis

- Correlation Heatmap
- Pairwise Relationships

---

## 4️ Feature Engineering

Applied feature engineering techniques such as:

- Dummy Variable Creation for categorical features
- Date transformation
- Data Transformation
- Feature Scaling (where applicable)

---

## 5️ Variable Reduction

Reduced unnecessary variables using statistical techniques:

- Correlation Analysis
- Variance Inflation Factor (VIF)
- P-value Analysis
- Backward Elimination

---

## 6️ Model Building

Built a Multiple Linear Regression model using:

- Statsmodels (OLS)
- Scikit-learn LinearRegression

---

## 7️ Model Evaluation

Evaluated model performance using:

- R² Score
- Adjusted R²
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- MAPE (Mean Absolute Percentage Error)

---

##  Data Visualization

Created visualizations using:

- Histogram
- Boxplot
- Scatter Plot
- Pair Plot
- Heatmap
- Distribution Plot
- Correlation Matrix

---

##  Business Insights

- Identified the key factors influencing car sales.
- Evaluated the relationship between price and sales.
- Analyzed the impact of engine size and horsepower.
- Reduced multicollinearity using VIF analysis.
- Selected statistically significant variables for the final model.
- Built an interpretable regression model for sales prediction.

---

##  Python Libraries Used

```python
import numpy as np
import pandas as pd

import matplotlib.pyplot as plt
import seaborn as sns

import scipy.stats as stats

import statsmodels.formula.api as smf

from sklearn.model_selection import train_test_split

from sklearn.linear_model import LinearRegression

from sklearn.metrics import (
    mean_absolute_error,
    mean_squared_error,
    mean_absolute_percentage_error
)
```

---

##  Machine Learning Concepts Covered

- Linear Regression
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Dummy Variables
- Variable Reduction
- Correlation Analysis
- Multicollinearity (VIF)
- Statistical Modeling
- Model Evaluation
- Train-Test Split

---

##  Project Structure

```
Car-Sales-Linear-Regression/
│
├── Dataset/
│   └── Car_sales.csv
│
├── Notebook/
│   └── Car_Sales_Linear_Regression.ipynb
│
├── Images/
│
├── README.md
│
└── requirements.txt
```

---

##  How to Run

### Clone Repository

```bash
git clone https://github.com/your-github-username/Car-Sales-Linear-Regression.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scipy statsmodels scikit-learn
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

##  Skills Demonstrated

- Python Programming
- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Visualization
- Statistical Analysis
- Linear Regression
- Variable Selection
- Multicollinearity Analysis
- Machine Learning
- Model Evaluation
- Predictive Analytics

---

##  Learning Outcomes

Through this project, I gained practical experience in:

- End-to-end Machine Learning workflow
- Data preprocessing and cleaning
- Exploratory Data Analysis
- Statistical feature selection
- Building Linear Regression models
- Evaluating regression performance
- Interpreting business insights from predictive models

---

##  Author

**Shoaib Khan**

 Email: SHOAIB913599@gmail.com

 LinkedIn: https://www.linkedin.com/in/shoaib-khan-1b16232b2

 GitHub: https://github.com/your-github-username

---

##  Support

If you found this project useful, please consider giving it a  Star.

---

##  Keywords

Python, Linear Regression, Machine Learning, Data Analytics, Predictive Analytics, Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, Statsmodels, EDA, Data Cleaning, Feature Engineering, VIF, Regression Analysis, Model Evaluation.
