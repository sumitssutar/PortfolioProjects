# 🏡 AirBnB Listings Data Visualization (Tableau Project)

## 📌 Project Overview
This project focuses on analyzing AirBnB listings data using Tableau to uncover pricing trends, revenue patterns and geographical insights.  
An interactive dashboard was built to help understand key factors influencing pricing and profitability.

---

## 🧩 Business Problem
AirBnB hosts and stakeholders lack clear insights into:
- Pricing variations across locations  
- Revenue trends over time  
- Impact of property features (like bedrooms)  

This makes it difficult to optimize pricing and maximize revenue.

---

## 🎯 Goal
To analyze AirBnB listings data and build an interactive dashboard that helps in understanding pricing, demand and revenue patterns.

---

## 📊 Dataset Description

The dataset includes multiple tables:

### 🗂 Listings
- id  
- listing_id  
- zipcode  
- bedrooms  
- price  
- latitude  
- longitude
- etc... 

### 🗂 Calendar
- listing_id  
- date  
- price
- etc...

### 🗂 Reviews
- listing_id  
- review_date
- etc...

---

## 🔗 Data Preparation
- Imported Excel dataset into Tableau  
- Performed **INNER JOINS** using `listing_id`  
- Connected:
  - Listings ↔ Calendar  
  - Listings ↔ Reviews  

---

## 📊 Dashboard Preview
![](Images/airbnb_dashboard.png)

---

🔗 **Live Dashboard:**  
👉 https://public.tableau.com/views/TableauProjectAirBnBListings/Dashboard1

---

## 📊 Key Visuals

### 📍 Price by Zipcode
- Bar chart showing average price across different zip codes  

### 🗺 Price by Location (Map)
- Geospatial visualization using latitude & longitude  
- Highlights high and low price regions  

### 📈 Revenue for Year
- Time series analysis of revenue trends  
- Identifies peak seasons  

### 🛏 Avg Price per Bedroom
- Shows how pricing increases with number of bedrooms  

### 🔢 Distinct Bedroom Listings
- Distribution of listings based on bedroom count  

---

## 🔍 Key Insights

- Pricing varies significantly across zip codes  
- Certain locations generate higher revenue due to demand  
- Revenue peaks during seasonal demand (summer & holidays)  
- Properties with more bedrooms command higher prices  
- Majority of listings are 1-bedroom, indicating high competition  

---

## 💼 Business Impact

- Helps hosts optimize pricing strategies  
- Identifies high-demand locations for investment  
- Supports revenue forecasting  
- Enables better understanding of market competition  

---

## 🛠 Tools Used
- Tableau Public  
- Microsoft Excel  

---

## 📂 Repository Structure
```
airbnb-listings-tableau-dashboard/
│
├── dataset/
│   └── airbnb_data.xlsx
│
├── images/
│   └── airbnb_dashboard.png
│
├── docs/
│   └── data_catalog.md
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

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sumitsutar2507)
