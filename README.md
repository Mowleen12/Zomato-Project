# 🍽️ Zomato Restaurant Rating Prediction

This project aims to predict restaurant ratings using the **Zomato restaurant dataset**, focusing on features like **location**, **service offerings**, and **cuisine type**. Two machine learning models — **Linear Regression** and **Random Forest Regressor** — are used to estimate ratings and analyze the impact of various restaurant attributes on customer feedback.

---

## 🧠 Problem Statement

> Predict restaurant ratings based on location, service features, and cuisine information using the Zomato restaurant dataset.

---

## 📁 Dataset Overview

The dataset is included in the project (`/data/zomato.csv`) and contains restaurant-related features such as:

- **Restaurant Name**
- **Location**
- **Cuisines**
- **Average Cost for Two**
- **Has Table Booking**
- **Has Online Delivery**
- **Aggregate Rating** (Target)
- **Votes**
- **Price Range**

> All necessary data preprocessing steps like missing value handling, encoding of categorical variables, and feature selection have been applied in the project.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn** – Data visualization and EDA
- **Scikit-learn** – Model training and evaluation

---

## 🤖 Models Used

### 🔹 Linear Regression
- Assumes a linear relationship between features and the target.
- Serves as the baseline model.

### 🔹 Random Forest Regressor
- An ensemble learning method using multiple decision trees.
- Captures complex non-linear relationships between features and rating.

---
