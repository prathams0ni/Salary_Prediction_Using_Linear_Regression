# Machine Learning Model Training in Simple Linear Regression

## ML Model Training in Simple Linear Regression with Data Cleaning, Pre-Processing, EDA, Training Model, Testing Model, Validation Model, Final Accuracy of Model.

## Simple Linear Regression — Data Analysis Project:

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)
![Scikit-Learn](https://img.shields.io/badge/Library-ScikitLearn-green.svg)
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-yellow.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-blue.svg)
![Seaborn](https://img.shields.io/badge/Library-Seaborn-purple.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

---

## Project Overview:

This project demonstrates the implementation of **Simple Linear Regression**, one of the most fundamental techniques in Machine Learning.  
It focuses on understanding the linear relationship between **two continuous variables** — one **independent (X)** and one **dependent (Y)**.  

The notebook explains:
- The intuition behind linear regression  
- The step-by-step implementation in Python  
- Visualization and evaluation of the regression model  

---

## Objectives:

- Understand the **concept of Simple Linear Regression**
- Learn how to split data into **training** and **testing** sets  
- Train a regression model using **Scikit-learn**
- Visualize the **best-fit regression line**
- Evaluate model performance using metrics such as **R² Score** and **Mean Squared Error (MSE)**

---

## Tools and Libraries:

| Tool / Library | Purpose |
|----------------|----------|
| **Python** | Programming language |
| **Jupyter Notebook** | Interactive data analysis environment |
| **Pandas** | Data manipulation and loading |
| **NumPy** | Numerical operations |
| **Matplotlib / Seaborn** | Data visualization |
| **Scikit-learn (sklearn)** | Machine Learning library for model building and evaluation |

---

## Concept Overview:

**Simple Linear Regression Equation:**

\[
Y = b_0 + b_1X
\]

Where:  
- \( Y \) = Dependent variable (output)  
- \( X \) = Independent variable (input)  
- \( b_0 \) = Intercept  
- \( b_1 \) = Slope of the regression line  

The model aims to find the best line that minimizes the **sum of squared errors (SSE)** between actual and predicted values.

---

## Dataset Description:

The dataset used in this notebook typically includes:
- **X (Independent Variable):** Example — Years of Experience, Advertising Spend, Temperature, etc.  
- **Y (Dependent Variable):** Example — Salary, Sales Revenue, Ice Cream Sales, etc.  

This simple dataset helps demonstrate how linear regression predicts continuous outcomes.

---

## Steps Performed:

1. **Importing Libraries**  
2. **Loading Dataset using Pandas**  
3. **Exploring Data (EDA)** — shape, info, describe, and correlation  
4. **Visualizing Relationships** — using scatter plots and heatmaps  
5. **Splitting Data** into Training and Test sets  
6. **Training the Model** with `LinearRegression()` from Scikit-learn  
7. **Making Predictions** on test data  
8. **Visualizing Regression Line** with actual vs. predicted values  
9. **Evaluating the Model** using R² Score and MSE  

---

## Visualizations:

The notebook includes:
- Scatter plots showing **relationship between X and Y**
- Regression line illustrating **model fit**
- Distribution plots of residuals
- Actual vs Predicted comparison graph

---

**Actual vs Predicted Chart:**

<img width="721" height="623" alt="image" src="https://github.com/user-attachments/assets/48d86cf3-7e86-4709-9ba6-f50d0ecf0e50" />

[Regression Line](https://raw.githubusercontent.com/prathams0ni/Simple-Linear-Regression/main/images/regression_line.png)

---

## Run this Project:

**To Run this project you need a Jupyter Notebook in your system. also I uploaded a dataset file for the same first download it in your system & copy the path of dataset file & paste it in importing dataset column after pd.read_excel you have to paste the path of dataset file. after that you can run each & every cell to run it.**

---

## Conclusion:

This project provides a clear understanding of how Simple Linear Regression works and how it can be implemented using Python.
By visualizing the relationship between variables, it shows how data trends can be captured mathematically and used for prediction.
