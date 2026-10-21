# Telecom Plan Recommendation System

## Overview

This project analyzes telecom customer behavior and builds a recommendation framework for suggesting suitable telecom packages based on usage patterns.

The goal is to transform raw telecom data into actionable business insights that can support marketing and customer retention strategies.

---

## Business Problem

Telecommunication providers manage large volumes of customer data, including:

- Call activities
- Mobile data consumption
- Billing information

Without proper segmentation, it is difficult to understand customer behavior and provide personalized service offerings.

This project aims to:

- Identify customer behavior patterns
- Segment customers into meaningful groups
- Recommend suitable data and voice plans
- Support customer retention and ARPU growth

---

## Project Objectives

- Clean and prepare telecom customer data
- Extract behavioral features from usage records
- Perform customer segmentation using machine learning
- Generate recommendation logic based on segment characteristics
- Build interactive dashboards for business stakeholders

---

## Dataset

The project uses telecom-related customer information such as:

- Call logs
- Data usage records
- Billing information

After preprocessing, customer-level features were created for analysis and modeling.

Examples:

- Monthly voice usage
- Monthly data consumption
- Average spending
- Usage frequency

---

## Technology Stack

### Programming

- Python
- SQL

### Python Libraries

- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

### Visualization

- Power BI
- DAX

---

## Project Workflow

### 1. Data Extraction

SQL queries were used to retrieve and aggregate customer behavior data.

Tasks included:

- Data filtering
- Aggregation
- Feature extraction

---

### 2. Data Cleaning & Preprocessing

Data was prepared using Python and Pandas:

- Missing value handling
- Duplicate removal
- Feature engineering
- Data transformation

---

### 3. Exploratory Data Analysis (EDA)

Customer behavior was explored through:

- Usage distribution analysis
- Revenue analysis
- Consumption pattern analysis

---

### 4. Customer Segmentation

K-Means Clustering was applied to identify customer groups based on behavior characteristics.

Sample segments included:

- High Data Users
- Voice-Centric Users
- Balanced Users
- Low Activity Users

---

### 5. Recommendation Framework

Based on customer segments, suitable plans can be recommended.

Examples:

| Segment | Suggested Package |
|----------|------------------|
| High Data Users | Large Data Plans |
| Voice-Centric Users | Voice-focused Plans |
| Balanced Users | Combo Packages |
| Low Activity Users | Basic Packages |

---

### 6. Dashboard Development

An interactive Power BI dashboard was developed to visualize:

- Customer segments
- Usage behaviors
- Revenue contribution
- Recommendation insights

---

## Key Results

✅ Identified distinct customer behavior segments

✅ Built a customer recommendation framework

✅ Developed an interactive Power BI dashboard

✅ Transformed raw telecom data into actionable business insights

---

## Dashboard Preview

### Overview

(Add Screenshot Here)

### Customer Segments

(Add Screenshot Here)

### Recommendation Insights

(Add Screenshot Here)

---

## Repository Structure

```
telecom-plan-recommendation-system
│
├── data
│   ├── raw
│   └── processed
│
├── sql
│   ├── data_extraction.sql
│   ├── feature_engineering.sql
│   └── analysis.sql
│
├── notebooks
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_customer_segmentation.ipynb
│   └── 04_recommendation_model.ipynb
│
├── dashboard
│   ├── Telecom_Dashboard.pbix
│   └── screenshots
│
└── README.md
```

---

## Author

Nguyen Pham Hung

LinkedIn:
https://www.linkedin.com/in/hungcv/

Email:
hungnp1272@ut.edu.vn
