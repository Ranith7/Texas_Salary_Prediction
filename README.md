# Texas_Salary_Prediction
Predicted Texas state employee salaries using machine learning with deep EDA, outlier detection, and wage gap analysis. Delivered actionable payroll insights through model comparison, visualizations, and salary forecasting based on job roles, departments, and other key factors. (Regression • ML • EDA • Salary Forecasting)



---

# Texas Employee Salary Prediction 📊

##  Project Overview

This project aims to support the **Texas State Government** in understanding, analyzing, and predicting employee salaries using historical payroll data. The analysis helps identify wage disparities, uncover trends over time, and forecast salaries through machine learning techniques.

---

##  Problem Statement

### Objectives:

1. 📊 **Data Analysis** – Prepare a complete analysis report on the employee salary data.
2. 🔮 **Salary Prediction** – Build a model to predict annual income based on employee attributes.
3. 💡 **Answer Key Questions**:

   * Who are the **outliers** in the salaries?
   * What **departments or roles** show the biggest **wage disparities**?
   * How have **salaries and compensations** changed over time?

---

## 📁 Dataset Features (Attributes)

| Column Name  | Description             |
| ------------ | ----------------------- |
| Agency       | Agency code             |
| Agency Name  | Full agency name        |
| Last Name    | Employee's last name    |
| First Name   | Employee's first name   |
| MI           | Middle Initial          |
| Class Title  | Role/Designation        |
| Ethnicity    | Demographic information |
| Gender       | Male/Female             |
| Status       | Employment status       |
| Employ Date  | Joining date            |
| Hourly Rate  | Hourly compensation     |
| Hrs per Week | Working hours/week      |
| Monthly      | Monthly income          |
| Annual       | Annual income           |
| State Number | State-level identifier  |

---

##  Project Tasks & Workflow

### 1.  Data Preprocessing

* Handled null values and data inconsistencies
* Converted categorical columns using label encoding and one-hot encoding
* Normalized/Standardized numerical columns for model accuracy

### 2. 📊 Exploratory Data Analysis (EDA)

* Analyzed salary distributions and outliers
* Investigated gender and ethnicity-based salary gaps
* Identified disparities between departments, roles, and seniority
* Studied compensation changes over employment years

### 3.  Model Building

* Used regression models like:

  * **Linear Regression**
  * **Decision Tree Regressor**
  * **Random Forest Regressor**
* Evaluated models using R² and Adjusted R² scores

### 4.  Visualization

* Correlation heatmaps, bar plots, boxplots, and trend lines for storytelling
* Outlier detection using boxplots
* Distribution plots of annual salaries

---

##  Results & Insights

* **Key Outliers**: Identified using statistical measures and visual plots
* **Departmental Disparities**: Managerial roles showed significant wage gaps
* **Trends Over Time**: Certain roles and departments displayed salary growth while others remained stagnant
* **Best Model**: \[Your best model name here] with R² = \[score], showing effective salary prediction

---

## ⚠ Challenges Faced

* Dealing with **missing and inconsistent data entries**
* **Encoding categorical features** while avoiding multicollinearity
* Handling **imbalanced distributions** in roles and pay ranges
* Selecting and tuning the **right regression models**
* Maintaining **interpretability** in model predictions

---

## 📌 Conclusion

The project successfully built a reliable salary prediction model and derived actionable insights that can help the Texas government in payroll planning, fairness checks, and strategic HR decisions.

---

## 🛠️ Tech Stack

* **Python**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Jupyter Notebook**: For data exploration and model development

---

## 🧾 Short GitHub Description

> Predict employee salaries using machine learning and uncover insights from Texas State payroll data through deep EDA and visualization.
> *(Regression • ML • Data Analysis • Salary Forecasting)*

---

