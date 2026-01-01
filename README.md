# Salary Prediction Using Simple Linear Regression

## 📌 Project Overview

This project implements **Simple Linear Regression** to analyze and predict **Salary** based on **Years of Experience**. The goal is to understand the relationship between experience and salary, evaluate model performance, and interpret results using real data.

---

## 🎯 Problem Statement

The dataset contains two variables:

* **Years of Experience** (Independent Variable)
* **Salary** (Dependent Variable)

Objectives of the project:

* Identify whether a linear relationship exists between experience and salary
* Build a best-fit regression line
* Analyze how salary changes with experience
* Evaluate model performance using residuals and R-squared score

---

## 📂 Dataset Details

* **File Name:** `Salary.xlsx`
* **Columns:**

  * `YearsExperience`
  * `Salary`
* **Type:** Numerical, continuous variables

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:**

  * pandas
  * numpy
  * matplotlib / seaborn
  * scikit-learn
* **Environment:** Jupyter Notebook

---

## 🔍 Methodology

### 1. Data Loading & Preparation

* Imported dataset from Excel file
* Checked for missing values and data types
* Prepared features and target variable

### 2. Exploratory Data Analysis (EDA)

* Visualized data using scatter plots
* Observed a positive linear trend between experience and salary

### 3. Model Building

* Applied **Simple Linear Regression** using scikit-learn
* Split data into training and testing sets
* Trained the regression model on training data

### 4. Model Evaluation

* Compared **Actual Salary vs Predicted Salary**
* Calculated **Residuals** to analyze prediction errors
* Evaluated performance using **R-squared score**

### 5. Visualization

* Plotted regression line along with actual data points
* Interpreted the best-fit line and error distribution

---

## 📊 Key Results & Insights

* A strong positive linear relationship exists between experience and salary
* Model predictions are reasonably close to actual salary values
* Residuals are distributed around zero, indicating no systematic bias
* R-squared score confirms that experience explains a significant portion of salary variation

---

## 📈 Final Conclusion

The Simple Linear Regression model effectively captures the relationship between **Years of Experience** and **Salary**. The analysis shows that salary increases consistently with experience, making experience a strong predictor of compensation.

The model performs well for basic prediction and explanatory analysis. While minor prediction errors are present, they are within acceptable limits for a simple model. This project serves as a strong foundational implementation of linear regression. Further improvements can be achieved by including additional variables such as education, job role, or industry.

---

## 📁 Repository Structure

```
Salary_Prediction_Using_Linear_Regression/
│
├── Salary.xlsx
├── Salary Prediction Using Linear Regression.ipynb
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone the repository
2. Open `Salary Prediction Using Linear Regression.ipynb` in Jupyter Notebook
3. Install required libraries if not already available
4. Run all cells sequentially

---
