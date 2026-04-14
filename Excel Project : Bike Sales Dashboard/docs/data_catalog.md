# 📊 Data Catalog – Bike Sales Project

## 📌 Overview
This document describes the structure, columns, and transformations applied to the Raw and Processed datasets used in the Bike Sales Dashboard project.

---

# 🗂 1. Raw Dataset (bike_sales_raw.xlsx)

## 📊 Description
Original uncleaned dataset containing customer demographic and behavioral data.

## 📑 Columns

| Column Name        | Data Type   | Description |
|-------------------|------------|-------------|
| ID                | Integer     | Unique identifier for each customer |
| Marital Status    | Categorical | Customer marital status (M / S) |
| Gender            | Categorical | Customer gender (M / F) |
| Income            | Numeric     | Annual income |
| Children          | Integer     | Number of children |
| Education         | Categorical | Education level |
| Occupation        | Categorical | Job role |
| Home Owner        | Categorical | House ownership (Yes / No) |
| Cars              | Integer     | Number of cars |
| Commute Distance  | Categorical | Distance to work |
| Region            | Categorical | Customer region |
| Age               | Integer     | Age |
| Purchased Bike    | Categorical | Purchase status |

## ⚠️ Issues Identified
- Duplicate records  
- Abbreviations (M/S, M/F)  
- No age grouping  
- Inconsistent formatting  

---

# 🧹 2. Processed Dataset (bike_sales_cleaned.xlsx)

## 📊 Description
Cleaned and structured dataset ready for analysis and dashboard creation.

## 📑 Columns

| Column Name        | Data Type   | Description |
|-------------------|------------|-------------|
| ID                | Integer     | Unique identifier |
| Marital Status    | Categorical | Married / Single |
| Gender            | Categorical | Male / Female |
| Income            | Numeric     | Cleaned income |
| Children          | Integer     | Number of children |
| Education         | Categorical | Education level |
| Occupation        | Categorical | Job role |
| Home Owner        | Categorical | Yes / No |
| Cars              | Integer     | Number of cars |
| Commute Distance  | Categorical | Distance categories |
| Region            | Categorical | Region |
| Age               | Integer     | Age |
| Age Brackets      | Categorical | Derived age groups |
| Purchased Bike    | Categorical | Yes / No |

## 🔄 Transformations

- Removed duplicates  
- Standardized categorical values  
- Converted income to numeric  
- Created Age Brackets column  

## 📊 Age Brackets Logic

- Adolescent → Age < 30  
- Middle Age → 30–50  
- Old → Age > 50  

---

## 🎯 Purpose
To analyze customer behavior and improve bike sales through data-driven insights.
