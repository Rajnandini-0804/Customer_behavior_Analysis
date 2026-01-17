# Customer_behavior_Analysis
This project represents a complete, industry standard, end-to-end data analytics workflow, designed to mirror the real responsibilities of professional analysts in modern business environments. The project encompasses all critical stages of data analysis, from data preparation and modeling to insight generation, visualization, and reporting.

📌 Project Overview
The goal of this project is to simulate a corporate-grade end-to-end data analytics workflow, demonstrating the ability to translate raw data into strategic business intelligence by:

✅ Data Preparation,Modeling & Exploratory Data Analysis (Python): Clean and transform the raw dataset for analysis.

✅ Data Analysis (MYSQL): Simulate business transactions, and run queries to extract insights on customer segments, loyalty, and purchase drivers.

✅ Visualization & Insights (Power BI): Build an interactive dashboard that highlights key patterns and trends, enabling stakeholders to make data-driven decisions.

✅ Report and Presentation: Write a clear project report summarizing your key findings and business recommendations. Prepare a presentation that visually communicates insights and actionable recommendations to stakeholders.


The project follows an end-to-end data analytics workflow using **Python**, **MySQL Workbench**, and **Power BI**.

---

## 🧰 Tools & Technologies Used

* **Python (Jupyter Notebook)** – Data cleaning, preprocessing, feature engineering
* **Pandas, NumPy** – Data manipulation
* **MySQL Workbench** – Structured data analysis using SQL queries
* **Power BI** – Data visualization and dashboard creation

---

## 📂 Dataset Description

The dataset contains customer shopping information such as:

* Customer demographics (Age, Gender, Location)
* Product details (Category, Item Purchased)
* Transaction details (Purchase Amount, Shipping Type, Discounts)
* Customer behavior (Previous Purchases, Subscription Status, Frequency of Purchases)

After cleaning and preprocessing, the dataset was stored in MySQL for further analysis.

---

## 🔧 Data Cleaning & Feature Engineering (Python)

Key steps performed in Python:

* Checked data types and missing values
* Imputed missing review ratings using category-wise median
* Renamed columns using snake_case for consistency
* Created new features such as:

  * **age_group** (Young Adult, Adult, Middle-aged, Senior)
  * **purchase_frequency_days** based on purchase frequency
* Removed redundant columns after validation
* Exported cleaned data for database usage

---

## 🗄️ Data Analysis using MySQL (Business Transactions)

Structured analysis was performed in **MySQL Workbench** to answer key business questions, including:

* Revenue comparison by gender
* Spending behavior of discounted vs non-discounted customers
* Top-rated and most-purchased products
* Customer segmentation based on purchase history
* Subscription impact on revenue
* Revenue contribution by age group

These queries enabled efficient analysis of large datasets and supported downstream visualization in Power BI.

---

## 📊 Data Visualization (Power BI)

Power BI dashboards were created to visualize:

* Revenue trends and customer segments
* Product performance and discount impact
* Subscription vs non-subscription behavior
* Age group–wise revenue contribution

The dashboards provide interactive insights for business decision-making.

---

## ✅ Key Insights

* Subscription customers contribute higher average revenue
* Certain product categories perform better with discounts
* Middle-aged and adult customer groups generate the highest revenue
* Repeat buyers show a stronger likelihood of subscription

---

## 📁 Project Structure

```
├── data/
│   └── customer_shopping_behavior.csv
├── notebooks/
│   └── data_cleaning_analysis.ipynb
├── sql/
│   └── mysql_queries.sql
├── powerbi/
│   └── dashboard.pbix
└── README.md
```

---

## 🎯 Conclusion

This project demonstrates an end-to-end data analytics pipeline, from raw data cleaning in Python to structured querying in MySQL and interactive reporting in Power BI. It highlights practical skills required for real-world data analyst roles.

---

## 👩‍💻 Author

**Rajnandini Bhosale**
Master’s degree in Computer Application
Aspiring Data Analyst

---

⭐ If you find this project useful, feel free to star the repository!
