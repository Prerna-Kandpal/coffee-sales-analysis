# ☕ Coffee Shop Sales Analysis

This project explores real-world coffee sales data collected from a vending machine. The goal is to perform exploratory data analysis (EDA), generate sales insights, and build a machine learning model to predict sales value based on key features.

---

##  Dataset Overview

- **Data Range**: March 2024 – Present  
- **Source**: Simulated vending machine transactions  
- **Columns**:
  - `date`: Transaction date  
  - `datetime`: Timestamp of purchase  
  - `cash_type`: Mode of payment (cash/card)  
  - `card`: Card identifier or cash flag  
  - `money`: Sale amount  
  - `coffee_name`: Type of coffee purchased

---

## 🔍 Project Workflow

###  Step 1: Data Cleaning
- Handled missing values
- Fixed data types
- Removed duplicates
- Standardized coffee names and payment entries

###  Step 2: Exploratory Data Analysis (EDA)
- Coffee popularity analysis
- Sales distribution by weekday and hour
- Monthly sales trends by coffee type

###  Step 3: Machine Learning
- Linear Regression model to predict `money` (sales amount)
- Used features: `coffee_name`, `cash_type`, `day`, and `hour`
- Evaluation: MSE and R² score

###  Step 4: Insights
- Most popular: **Latte** and **Americano with Milk**
- Peak hours: **10 AM** and **7 PM**
- Highest sales on **Tuesday**
- Over **90%** payments made via **card**

---

## 🛠️ Tools & Libraries

- Python 
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

---
