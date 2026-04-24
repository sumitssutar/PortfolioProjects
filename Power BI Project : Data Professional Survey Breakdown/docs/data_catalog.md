# 📊 Data Catalog – Data Professional Survey Dashboard

## 📌 Overview
This dataset contains survey responses collected from data professionals across different roles, countries, and experience levels.  
It is used to analyze salary trends, job satisfaction, skills demand, and career challenges in the data industry.

---

## 📑 Columns Description

| Column Name | Data Type | Description |
|------------|----------|------------|
| Respondent ID | Integer | Unique identifier for each survey participant |
| Age | Integer | Age of the respondent |
| Gender | Text | Gender of the respondent (Male/Female/Other) |
| Country | Text | Country of the respondent |
| Job Title | Text | Current role (e.g., Data Analyst, Data Scientist) |
| Years of Experience | Numeric | Total experience in years |
| Current Yearly Salary | Text | Salary range in text format (e.g., 50-75k) |
| Avg Salary | Numeric | Calculated average salary from range |
| Favorite Programming Language | Text | Preferred programming language |
| Work Life Balance | Numeric | Rating of work-life balance (scale-based) |
| Salary Satisfaction | Numeric | Satisfaction level with salary |
| Difficulty to Break into Data | Text | Perceived difficulty level (Easy/Moderate/Difficult) |

---

## 🔄 Data Transformations

### 🧹 Cleaning Steps
- Removed irrelevant columns  
- Renamed columns for clarity  
- Filtered inconsistent or null values  

### 🔧 Feature Engineering
- Split messy categorical values into structured categories  
- Standardized Job Title and Programming Language fields  

### 💰 Salary Transformation
- Extracted salary ranges from text  
- Removed characters like 'K', '-', '+'  
- Calculated average salary  
- Converted to numeric format for analysis  

---

## 📊 Derived Columns

| Column Name | Description |
|------------|------------|
| Avg Salary | Average of salary range |
| Clean Job Title | Standardized job roles |
| Clean Language | Simplified programming language categories |

---

## 🔗 Relationships
- Single dataset (no joins used in Power BI model)

---

## 🎯 Purpose of Dataset

- Analyze salary distribution across roles and countries  
- Understand skill demand in data industry  
- Evaluate job satisfaction and career challenges  
- Support interactive dashboard creation  

- Salary was originally in range format (not directly usable)  
- Categorical fields required heavy cleaning  
- Some responses were generalized for better visualization  
