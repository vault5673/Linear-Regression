# 🏠 Housing Price Prediction using Linear Regression

This project focuses on **predicting housing prices** using **multiple linear regression**.  
It includes **data cleaning, preprocessing, exploratory data analysis (EDA), feature scaling, model building**, and **model evaluation**.

---

## 📁 Dataset Overview

- **Source**: Housing Price Dataset (`Housing.csv`)
- **Features**:
  - **Categorical**: `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`, `furnishingstatus`
  - **Numerical**: `area`, `bedrooms`, `bathrooms`, `stories`, `parking`, `price`
- **Target**: `price` (House Price)

---

## 🛠️ Project Workflow

1. Import Libraries
2. Load the Dataset
3. Exploratory Data Analysis (EDA)
4. Outlier Detection and Removal (IQR Method)
5. Encoding Categorical Variables (Label Encoding)
6. Feature Scaling (StandardScaler)
7. Correlation Analysis (Heatmap)
8. Train-Test Split
9. Model Building (Linear Regression)
10. Prediction and Evaluation (R², MAE, MSE)
11. Regression Line Plotting
12. Interpretation of Model Coefficients

---

## 📊 Key Techniques Used

- Label Encoding for categorical columns
- Standard Scaling for continuous features (`price`, `area`)
- Outlier removal using the IQR method
- Correlation heatmap for feature analysis
- Linear Regression modeling
- Evaluation Metrics:
  - R² Score
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)

---

## 📈 Model Performance (Example)

- **R² Score**: 0.65
- **Mean Absolute Error (MAE)**: 0.20
- **Mean Squared Error (MSE)**: 0.08

---

## 📈 Model Intercept

The **intercept** represents the baseline value of the predicted `price` when all feature values are zero (after scaling).

- **Intercept**: `-0.002812275771309709`

