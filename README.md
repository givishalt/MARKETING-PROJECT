# 📊 Marketing Campaign Analysis & Conversion Prediction

## 📌 Project Overview

This project focuses on analyzing marketing campaign performance and building a **Linear Regression model** to predict conversions based on key metrics such as clicks, views, and cost-related features.

The goal is to:

* Understand campaign performance trends
* Clean and preprocess real-world marketing data
* Build a predictive model for conversions
* Visualize insights for better decision-making

---

## 📂 Dataset Description

The dataset includes marketing-related features such as:

* Clicks
* Views
* Conversion Rate
* Click-Through Rate (CTR)
* Cost per Click (CPC)
* Monthly campaign performance

Some columns required preprocessing due to:

* Percentage values (`%`)
* Currency symbols (`$`)
* Mixed data types

---

## 🛠️ Data Preprocessing

Performed the following steps:

* Converted percentage columns to numeric values
* Removed currency symbols and converted to float
* Handled mixed data types in object columns
* Checked for missing values
* Feature selection for model building

---

## 📈 Exploratory Data Analysis (EDA)

Key visualizations include:

* Monthly conversion trends (line plot)
* Feature vs target relationships
* Distribution plots
* Residual analysis

### 🔍 Key Insights:

* Highest conversions observed in early months (Feb–Mar)
* Mid-year shows performance fluctuations
* November shows the lowest conversion efficiency
* Slight recovery observed at year-end

---

## 🤖 Model Building

### Model Used:

* Linear Regression

### Steps:

1. Train-test split
2. Feature scaling (Normalization)
3. Model training
4. Prediction

---

## 📊 Model Evaluation Metrics

* MAE (Mean Absolute Error)
* MSE (Mean Squared Error)
* RMSE (Root Mean Squared Error)
* R² Score
* Adjusted R²

---

## 📉 Visualization for Model Evaluation

* Actual vs Predicted plot
* Residual plot
* Residual distribution

These plots help evaluate:

* Model accuracy
* Error distribution
* Overfitting/underfitting

---

## 🚀 Key Learnings

* Importance of data cleaning in real-world datasets
* Difference between normalization and standardization
* Proper train-test splitting to avoid data leakage
* Handling shape and dimensionality issues in ML
* Model evaluation using multiple metrics

---

## ⚙️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 📌 Future Improvements

* Try advanced models (Ridge, Lasso, Random Forest)
* Hyperparameter tuning
* Feature engineering
* Deploy using Streamlit

---

## ▶️ How to Run

```bash
# Clone the repository
git clone <your-repo-link>

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook
```

---

## 🎯 Conclusion

This project demonstrates a complete workflow from **data preprocessing → analysis → modeling → evaluation**, providing meaningful insights into marketing campaign performance and predictive modeling.

---

