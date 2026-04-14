# 🚴 Bike Sales Dashboard (Excel Project)

## 📌 Project Overview
This project focuses on analyzing customer data to understand buying behavior and improve bike sales.  
Using **Excel**, raw data was transformed into an **interactive dashboard** that provides **actionable business insights**.

---

## 🧩 Business Problem
Lack of clear insights into customer behavior makes it difficult to target the right audience and optimize sales strategies.

---

## 🎯 Business Objective
This project aims to help businesses improve bike sales by analyzing customer demographics and behavior so that better marketing and sales strategies can be developed.

---

## 📊 Dataset Columns

The dataset contains the following features:

- ID  
- Marital Status  
- Gender  
- Income  
- Children  
- Education  
- Occupation  
- Home Owner  
- Cars  
- Commute Distance  
- Region  
- Age  
- Purchased Bike  
- Age Brackets *(Derived Column)*

---
## 🧹 Data Cleaning
The raw dataset was cleaned and prepared using Excel:

- Removed duplicate records to ensure accuracy
- Standardized categorical values (e.g., "M" → "Married", "S" → "Single")
- Created **Age Brackets** using nested IF formulas:
  - Adolescent (<30)  
  - Middle Age (30–60)  
  - Old (>60) 
- Ensured consistent formatting for analysis

---

## 📊 Data Analysis (Pivot Tables)
Pivot Tables were created to analyze key metrics:

- Average Income by Gender & Purchase Status  
- Purchase behavior based on Customer Age Brackets  
- Impact of Commute Distance on Bike Purchases  

---

## 📈 Dashboard Preview

![](images/bike_sales_dashboard.png)

---

## 📊 Key Visuals
- **Bar Chart (Income vs Purchase):** Higher income → more purchases  
- **Line Chart (Age Brackets):** Middle-aged customers dominate sales  
- **Line Chart (Commute Distance):** Shorter distance (0–5 miles) → higher purchases  
- **Slicers (Marital Status, Region, Education)**  

---

## 🔍 Key Insights

- Middle-aged customers are the most likely to purchase bikes
- Customers with higher income show a higher tendency to purchase bikes
- Shorter commute distances (0–5 miles) are associated with higher bike purchases
- Bike purchases decrease as commute distance increases beyond 5 miles
- Male customers generally have higher average income, but purchase patterns are similar across genders
- Customer segmentation (education, region, marital status) significantly affects buying behavior

---

## 💼 Business Impact
- Enables targeted marketing strategies  
- Improves customer segmentation  
- Supports data-driven sales decisions  

---

## 🛠 Tools Used

- Microsoft Excel  
- Pivot Tables & Charts
- Data Cleaning Techniques  
- Slicers & Interactive Dashboard Design  

---

## 📂 Repository Structure

```
bike-sales-dashboard-excel/
│
├── dataset/
│   ├── raw/
│   │   └── bike_sales_raw.xlsx
│   │
│   ├── processed/
│   │   └── bike_sales_cleaned.xlsx
│
├── docs/
│   └── data_catalog.md
│
├── images/
│   └── bike_sales_dashboard.png
│
├── README.md
└── .gitignore
```

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi there! I'm **Sumit Sutar**. An experienced Data Analyst who uncovers hidden trends, patterns and anomalies and leverages business intelligence to generate insights, improve operational efficiency and drive organizational growth.


Let's stay in touch! Feel free to connect with me on the following platforms:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sumitsutar321)
