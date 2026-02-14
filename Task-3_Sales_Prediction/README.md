# 💰 Sales Prediction

## 📌 Project Overview

The Sales Prediction project is a machine learning project that predicts future sales for a company based on historical data.  

By analyzing patterns in past sales data, the model can forecast trends, helping businesses make informed decisions about inventory, marketing, and strategy.

---

## 🎯 Objective

- Predict sales for different products or stores  
- Understand time-series and regression problems  
- Apply data preprocessing and feature engineering  
- Train regression models and evaluate performance  
- Gain practical machine learning experience

---

## 📊 Dataset Information

The dataset contains:

- Historical sales data for products/stores  
- Features may include:  
  - Product ID  
  - Store ID  
  - Date  
  - Units sold  
  - Revenue or price  
- CSV format (`sales_data.csv`)  

---

## 🛠️ Technologies Used

- Python  
- Jupyter Notebook  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- Machine learning algorithms (Linear Regression, Random Forest)

---

## 🔍 Project Workflow

### 1️⃣ Data Loading
- Imported dataset using Pandas  
- Checked shape and data types  

### 2️⃣ Data Cleaning
- Checked for missing values  
- Handled duplicates  
- Converted dates into datetime objects if needed  

### 3️⃣ Exploratory Data Analysis (EDA)
- Visualized sales trends over time  
- Checked correlations between features  
- Identified seasonal patterns  

### 4️⃣ Feature Engineering
- Created new features such as:  
  - Month, Year, Day of Week  
  - Lag features (previous sales)  

### 5️⃣ Train-Test Split
- Split dataset into training and testing sets  
- Ensured chronological order for time-dependent data  

### 6️⃣ Model Training
- Applied regression algorithms:  
  - Linear Regression  
  - Decision Tree / Random Forest Regressor  

### 7️⃣ Model Evaluation
- Evaluated models using:  
  - Mean Absolute Error (MAE)  
  - Mean Squared Error (MSE)  
  - R-squared (R²)  

### 8️⃣ Prediction
- Predicted future sales for upcoming periods  
- Visualized predicted vs actual sales  

---

## 📈 Model Performance

- Models achieved good accuracy in predicting sales trends  
- Random Forest performed better in capturing non-linear patterns  
- Visualization shows predicted values closely follow actual trends  

---

## 📁 Project Structure


