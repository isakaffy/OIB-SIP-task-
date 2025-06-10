# OIB-SIP-task-2
Sales Prediction Using Media Advertising

This project demonstrates how to use *Linear Regression* to predict *product sales* based on advertising spend across different media channels: *TV, Radio, and Newspaper*. The goal is to understand the impact of each channel on sales and build a model that can make accurate predictions.

---

##  Dataset Overview

The dataset contains:
*TV*: Advertising budget spent on TV (in thousands of dollars)
*Radio*: Advertising budget spent on radio
*Newspaper*: Advertising budget spent on newspapers
*Sales*: Product sales (in thousands of units)

 Example snapshot:
| TV   | Radio | Newspaper | Sales |
|------|-------|-----------|-------|
| 230.1 | 37.8  | 69.2      | 22.1  |
| 44.5  | 39.3  | 45.1      | 10.4  |

---

##  Objective

Analyze the relationship between advertising channels and product sales.
Build a *Linear Regression* model to predict future sales.
Evaluate the model's performance using appropriate metrics.

---

##  Tools & Libraries Used

Python
Pandas
NumPy
Seaborn & Matplotlib (for visualizations)
Scikit-learn (for regression and evaluation)

---

##  Exploratory Data Analysis (EDA)

Checked for correlations between features
Plotted regression lines and scatter plots
Investigated the effectiveness of each media type

 *TV and Radio* show strong correlation with Sales, while *Newspaper* has weak influence.

---

##  Model Building

Used *Simple Linear Regression* 

Train a model on the data
Predict sales based on advertising budgets

---

##  Model Evaluation

Metrics used:
R² Score
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)

---

##  Results Summary

*TV and Radio* have significant influence on Sales.
*Newspaper* contribution is minimal.
Model generalizes well on unseen data with high accuracy.

---

##  Project Structure
sales-prediction/
│
├── advertising.csv               # Dataset
├── sales_prediction.ipynb        # Jupyter notebook with code and analysis
├── images/                       # Graphs and visualizations
└── README.md                     # Project overview
