# 🌧️ Rainfall Prediction in Ludhiana using Machine Learning

This project aims to predict rainfall in **Ludhiana, Punjab** using historical weather data and machine learning techniques. Accurate rainfall prediction can help in agricultural planning, urban management, and disaster preparedness.

---

## 📌 Project Overview

- **Location:** Ludhiana, Punjab (India)  
- **Data Source:** [Meteostat](https://meteostat.net/)  
- **Time Period:** January 1, 2021 – March 10, 2025  
- **Model Used:** Logistic Regression  
- **Goal:** Predict whether it will rain on a given day

---

## 🗃️ Dataset Description

The dataset contains daily weather observations with the following columns:

- `Avg_Temp`: Average daily temperature (°C)
- `Min_Temp`: Minimum daily temperature (°C)
- `Max_Temp`: Maximum daily temperature (°C)
- `Precipitation`: Rainfall amount (mm)
- `Wind_Direction`: Wind direction in degrees
- `Wind_Speed`: Wind speed (km/h)
- `Pressure`: Atmospheric pressure (hPa)
- `Temp_Variation`: Difference between Max and Min Temp
- `Wind_Direction_Label`: Categorized wind direction (e.g., N, NE, S)
- `Precipitation_Indicator`: Binary target variable (0 = No Rain, 1 = Rain)

---

## 🛠️ Steps Performed

1. **Data Cleaning:** Handled missing values and inconsistencies.
2. **Feature Engineering:** Created new variables like temperature variation and wind labels.
3. **Data Visualization:** Used plots to explore trends and relationships.
4. **Model Building:** Trained a Logistic Regression model for binary classification.
5. **Model Evaluation:** Assessed accuracy, precision, recall, and confusion matrix.

---

## 📊 Model Performance

### 🔍 Accuracy Score: `0.7745`

### 📊 Classification Report:
          precision    recall  f1-score   support

       0       0.80      0.90      0.85       211
       1       0.69      0.51      0.58        95





