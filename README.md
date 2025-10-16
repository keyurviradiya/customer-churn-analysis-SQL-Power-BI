# Customer Churn Analysis - SQL - Power-BI

# Overview
This project analyzes customer churn using MySQL for data processing and Power BI for visualization. 
It aims to identify factors that influence customer churn and help the business improve retention strategies.

# Tools Used
- MySQL – Data cleaning, transformation, and aggregation queries
- **Power BI* – Dashboard creation and insight visualization
- **Python (optional)** – Used for initial data cleaning and combining CSV files
- **GitHub** – Version control and project documentation

# 📁 Folder Structure
```
customer_churn_analysis/
│
├── data/
│   ├── customer_churn_dataset-training-master.csv
│   ├── customer_churn_dataset-testing-master.csv
│   └── customer_churn_clean.csv
│
├── mysql_scripts/
│   ├── 01_create_tables.sql
│   ├── 02_load_and_clean.sql
│   └── query_log.txt
│
├── powerbi/
│   ├── customer_churn_dashboard.pbix
│   └── dashboard_screenshot.png
│
└── README.md
```

## 📈 Key Insights
- Identified total churn rate and customer distribution.
- Analyzed churn by **gender**, **contract type**, and **subscription plan**.
- Found correlation between **support calls**, **payment delays**, and **churn likelihood**.
- Higher churn was observed among customers with shorter contracts and lower total spend.

## 📊 Power BI Visualizations
- **Card Visuals** – Total Customers, Total Churned, Churn Rate
- **Pie Chart** – Churn by Gender
- **Bar Chart** – Churn by Contract Length
- **Column Chart** – Average Spend by Churn
- **Line Chart** – Tenure vs Churn Trend

## ⚙️ How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/customer-churn-analysis.git
   ```
2. Run the SQL scripts in the `mysql_scripts` folder to create and load data.
3. Open Power BI → Load the `customer_churn_clean.csv` file.
4. Recreate or open the `.pbix` dashboard to explore churn insights.

## 🧩 Author
**Viradiya Keyur Bharatbhai**  
MBA in Finance | Aspiring Data Analyst | MySQL • Power BI • Python

