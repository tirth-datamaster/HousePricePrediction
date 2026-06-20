# 🏠 House Price Prediction

## 📌 Project Overview
This project was completed as part of my Data Science Internship. The objective was to build machine learning models that can predict house prices using different property-related features and identify the factors that influence house prices the most.

The project covers the complete machine learning workflow including data exploration, data preprocessing, visualization, model training, evaluation, and performance comparison.
---

## 🎯 Problem Statement
House prices are influenced by several factors such as area, number of bedrooms, bathrooms, parking facilities, furnishing status, and other amenities. The goal of this project is to build a regression model that can accurately predict house prices based on these features.

---
## 📂 Dataset Information
* Dataset Name: Housing.csv
* Total Records: 545
* Total Features: 13
* Target Variable: Price

### Features Included
* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road Access
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Parking
* Preferred Area
* Furnishing Status

---
## 🛠️ Technologies Used
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 🔍 Data Preprocessing
The following preprocessing steps were performed:
* Checked dataset structure and data types
* Checked for missing values
* Removed duplicate records
* Converted categorical variables using One-Hot Encoding
* Prepared the dataset for machine learning models

---

## 🤖 Machine Learning Models
Two regression models were trained and compared:

### 1. Linear Regression
A simple and interpretable regression model used as the baseline model.

### 2. Random Forest Regressor
An ensemble learning model that combines multiple decision trees to improve prediction performance.

---

## 📊 Model Performance
| Model                   | MAE (₹)   | RMSE (₹)  | R² Score |
| ----------------------- | --------- | --------- | -------- |
| Linear Regression       | 970,043   | 1,324,507 | 0.6529   |
| Random Forest Regressor | 1,021,546 | 1,400,566 | 0.6119   |

✅ Best Performing Model: Linear Regression
---

## 📈 Key Findings
* Area was the most important factor affecting house prices.
* Bathrooms showed a stronger impact on price than expected.
* Air conditioning and parking also contributed significantly to property value.
* Linear Regression performed better than Random Forest on this dataset.
* The model explained approximately 65% of the variation in house prices.

---

## 📸 Project Visualizations

### Price Distribution
Shows how house prices are distributed across the dataset.

### Correlation Heatmap
Displays relationships between different features and house prices.

### Actual vs Predicted Prices
Compares actual house prices with model predictions.

---

📁 Repository Structure
HousePricePrediction
│
├── analysis.ipynb
├── Housing.csv
├── summary.docx
├── README.md
│
└── charts
    ├── price_distribution.png
    ├── correlation_heatmap.png
    ├── actual_vs_predicted.png
    └── feature_importance.png

---

## 👨‍💻 Author

**Tirth Patel**
B.Tech Artificial Intelligence & Data Science
Sankalchand Patel College of Engineering

---

## ⭐ Learning Outcome
This project helped me gain practical experience in data preprocessing, visualization, regression modeling, model evaluation, and applying machine learning techniques to solve a real-world business problem.
