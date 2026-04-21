# Customer-Lifetime-Value-CLV-Prediction-using-RFM-Regression
# Customer Lifetime Value (CLV) Prediction & Customer Segmentation

## 📌 Overview

This project focuses on analyzing customer transaction data to predict **Customer Lifetime Value (CLV)** and segment customers based on purchasing behavior.

The goal is to transform raw transactional data into **actionable business insights** that can support marketing, retention, and revenue optimization strategies.

---

## 🎯 Objectives

* Understand customer purchase behavior
* Segment customers using RFM (Recency, Frequency, Monetary)
* Predict future customer value (CLV)
* Identify high-value customers for targeted strategies

---

## 📊 Dataset

* ~500,000+ retail transactions
* Features include: InvoiceDate, CustomerID, Quantity, UnitPrice

---

## ⚙️ Approach

### 1. Data Cleaning

* Removed null Customer IDs
* Filtered cancelled transactions
* Ensured valid purchase records

### 2. Feature Engineering

* Created RFM features:

  * Recency (days since last purchase)
  * Frequency (number of purchases)
  * Monetary (total spend)

* Additional features:

  * Avg purchase value
  * Purchase frequency
  * Customer lifespan

### 3. Modeling

* Applied **Linear Regression** to predict CLV
* Evaluated using:

  * R² Score
  * Median Absolute Error

### 4. Visualization

* Purchase frequency distribution
* Revenue contribution analysis
* Customer segmentation insights

---

## 📈 Key Insights

* A small segment of customers contributes a large share of revenue
* High-frequency customers show strong CLV predictability
* Recency is a strong indicator of future purchase likelihood

---

## 💡 Business Impact

* Helps businesses identify high-value customers
* Enables targeted marketing & retention strategies
* Supports revenue forecasting and decision-making

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib

---

## 🚀 Future Improvements

* Use advanced models (XGBoost, Random Forest)
* Deploy as a dashboard (Power BI / Streamlit)
* Integrate real-time customer data

---

## 👤 Author

Arnab Dey
