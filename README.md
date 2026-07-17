# 📊 Strategic Customer Churn Analysis

A data analytics project that analyzes customer churn patterns and provides actionable business recommendations to improve customer retention. The project uses **Python**, **SQL**, and **SQLite** to transform raw customer data into meaningful insights through data analysis, visualization, and feature engineering.

---

## 📌 Project Overview

Customer churn directly impacts business growth and profitability. This project identifies the key reasons why customers leave a platform and provides strategic recommendations to reduce churn and improve customer retention.

The analysis is performed on a **SQLite database (`customer_churn.db`)** containing customer information, subscription details, and customer support records.

---

## 🎯 Objectives

- Analyze customer churn behavior.
- Identify high-risk customers.
- Measure business KPIs such as churn rate and ARPU.
- Discover factors influencing customer retention.
- Provide actionable recommendations for business teams.

---

## ✨ Features

- 📂 SQL-based data extraction from SQLite database
- 🧹 Data cleaning and preprocessing
- 🔧 Feature engineering
- 📊 Exploratory Data Analysis (EDA)
- 📈 Customer churn trend analysis
- 📉 Revenue and subscription analysis
- 🎨 Interactive data visualizations
- 📋 Business KPI reporting
- 💡 Actionable business recommendations

---

## 🛠️ Tech Stack

### Languages
- Python
- SQL

### Database
- SQLite3

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLite3

### Development Environment
- Jupyter Notebook

---

## 📂 Project Structure

```
Strategic-Customer-Churn-Analysis/
│
├── data/
│   └── customer_churn.db
│
├── notebooks/
│   └── Customer_Churn_Analysis.ipynb
│
├── sql/
│   └── queries.sql
│
├── images/
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## 🚀 Project Workflow

### 1. Data Import

- Connected the SQLite database using Python.
- Extracted customer information using SQL queries.
- Loaded data into Pandas DataFrames for analysis.

---

### 2. Data Cleaning

- Corrected data types.
- Renamed columns for consistency.
- Removed unnecessary variables.
- Handled missing values.
- Standardized location data by mapping states to countries.

---

### 3. Feature Engineering

Created new business features including:

- Churn Flag
- Customer Risk Score
- Low Risk Customers
- Medium Risk Customers
- High Risk Customers

---

### 4. Exploratory Data Analysis (EDA)

Performed analysis using:

- GroupBy operations
- Aggregations
- Pivot Tables
- Descriptive Statistics
- Revenue Analysis
- Customer Segmentation

Key Performance Indicators (KPIs):

- Customer Churn Rate
- Average Revenue Per User (ARPU)
- Customer Distribution
- Subscription Performance

---

### 5. Data Visualization

Created visualizations including:

- Monthly Churn Trend
- Churn Distribution
- Subscription Plan Comparison
- Correlation Heatmap
- Pair Plot
- Revenue Analysis Charts

---

## 📊 Key Business Insights

### 📉 Overall Churn Rate

Approximately **28.57%** of customers have churned from the platform.

### 💳 Subscription Plan Analysis

- **Basic Plan:** 60% churn rate
- **Premium Plan:** 14% churn rate

This indicates that customers on the Basic Plan are significantly more likely to leave than Premium subscribers.

### 🎧 Customer Support Analysis

A strong positive correlation (**76–77%**) exists between escalated customer support issues and customer churn, highlighting customer support quality as a major retention factor.

---

## 💡 Business Recommendations

### ✅ Improve Customer Support

- Reduce support escalation rates.
- Improve first-contact resolution.
- Monitor unresolved complaints.

---

### ✅ Optimize the Basic Plan

- Review pricing strategy.
- Compare features with competitors.
- Improve value offered to Basic users.

---

### ✅ Target High-Risk Customers

- Identify Premium customers with high churn risk.
- Launch personalized retention campaigns.
- Offer loyalty rewards and exclusive promotions.

---

## 📈 Business Impact

This project helps organizations to:

- Reduce customer churn
- Improve customer satisfaction
- Increase customer lifetime value (CLV)
- Optimize subscription plans
- Support data-driven decision making

---

## 🚀 Future Improvements

- Deploy an interactive Streamlit dashboard
- Build a real-time churn prediction model
- Integrate Power BI dashboards
- Automate monthly churn reporting
- Develop customer retention recommendation system

---

## ▶️ Getting Started

Clone the repository:

```bash
git clone https://github.com/sarthak-hybrid/Strategic-Customer-Churn-Analysis.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## 🤝 Contributing

Contributions are welcome!

Feel free to fork this repository, create a feature branch, and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Sarthak Kandu**

Aspiring Data Analyst | Python | SQL | Data Visualization

GitHub: https://github.com/sarthak-hybrid

---

⭐ **If you found this project helpful, consider giving it a Star on GitHub!**
