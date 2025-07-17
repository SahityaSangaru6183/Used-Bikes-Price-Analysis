# Used-Bikes-Price-Analysis

# 🏍️ Used Bikes Price Analysis and Prediction

A data science project focused on analyzing used bikes data to uncover pricing patterns and develop a machine learning model to predict the resale value of bikes based on key features.

---

## 🔍 Short Description / Purpose

This project aims to help buyers, sellers, and dealers make informed decisions by predicting the selling price of used bikes using historical data and machine learning techniques. The project also explores market trends through detailed EDA.

---

## 💻 Tech Stack

- 🐍 **Python** – Core language  
- 📊 **Pandas, NumPy** – Data wrangling and numerical analysis  
- 📉 **Matplotlib, Seaborn** – Exploratory Data Analysis (EDA)  
- 🤖 **Scikit-learn** – Machine learning model development  
- 📂 **Jupyter/Colab Notebook** – Project development environment

---

## 🗃️ Dataset

- Source: Used Bikes Dataset (e.g., Kaggle or scraped)
- Features include:
  - `name` – Bike name/model  
  - `year` – Year of purchase  
  - `km_driven` – Kilometers driven  
  - `owner_type` – First/Second-hand  
  - `ex_showroom_price` – Original price  
  - `selling_price` – Resale price  
  - `fuel_type`, `seller_type`, `transmission`, etc.

---

## 🎯 Features / Highlights

### • Problem Statement

Can we accurately predict the selling price of a used bike based on key features such as year, kilometers driven, and brand?

### • Solution Overview

- ✅ **Data Cleaning**: Removed outliers, handled missing values, and normalized key fields  
- ✅ **Feature Engineering**: Extracted relevant features (e.g., age from year)  
- ✅ **EDA**: Uncovered patterns in pricing by brand, fuel type, and ownership  
- ✅ **Model Building**: Trained multiple regressors (e.g., **Linear Regression**, **Random Forest**, **XGBoost**)  
- ✅ **Evaluation**: Compared models using metrics like **MAE**, **RMSE**, and **R² score**  
- ✅ **Prediction**: Final model used to predict bike prices on unseen data

---

## 📊 Key Insights

- Older bikes and those with higher kilometers have lower resale values  
- Owner type and brand significantly influence price  
- Random Forest Regressor performed best with the lowest error rate
