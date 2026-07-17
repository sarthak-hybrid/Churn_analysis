Strategic Customer Churn Analysis
📌 Project Overview
This data analytics project identifies why users leave a platform (churn) and provides actionable retention strategies
. It uses a customer_churn.db SQLite database containing Customer, Subscription, and Support tables
🛠️ Tech Stack
Languages: Python, SQL
Libraries: Pandas, NumPy, Matplotlib, Seaborn, SQLite3
Environment: Jupyter Notebook
🚀 Project Workflow
Data Import: Connected SQLite3 to Python to read data directly using SQL queries
.
Data Cleaning: Fixed data types, renamed columns, dropped empty variables, and resolved missing values (e.g., mapping states to countries)
.
Feature Engineering: Created calculated columns like a binary churn_flag and segmented users into low, medium, and high churn_risk tiers
.
Exploratory Data Analysis (EDA): Leveraged groupby, aggregations, and pivot tables to track KPIs like churn rate and Average Revenue Per User (ARPU)
.
Data Visualization: Built telling charts, including Monthly Churn Trends, Seaborn correlation heatmaps, and pair plots
.
📊 Key Business Insights
Overall Churn Rate: ~28.57% of analyzed users have left the platform
.
Plan Type Impact: The Basic plan experiences the highest churn at 60%, whereas Premium only sees 14%
.
Customer Support Pipeline: There is a high correlation (~76-77%) between users who escalate support issues and those who eventually churn

💡 Actionable Next Steps
Revamp Customer Support: Implement better resolution frameworks to solve complaints before they reach the escalation stage, as escalated tickets heavily drive churn
.
Evaluate the Basic Plan: Investigate pricing, recent changes, or competitor advantages causing massive departures in the Basic tier
.
Targeted Retention: Collaborate with Growth/Marketing teams to prioritize retaining Premium users categorized as "High Risk," as they provide the most lifetime value
.

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request.

---
## 👨‍💻 Author

**Sarthak Kandu**

Aspiring Data Analyst | Python | SQL

GitHub: https://github.com/sarthak-hybrid

---

### ⭐ Support
If you found this project useful, consider giving it a **Star ⭐** on GitHub.
