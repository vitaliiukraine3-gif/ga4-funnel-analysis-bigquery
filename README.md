Google Analytics 4 Funnel Analysis (BigQuery & SQL)

This project analyzes the **user journey and conversion funnel** of an eCommerce platform using the **Google Analytics 4 public dataset** in **BigQuery**.

The goal was to understand user behavior, measure conversion rates at each funnel stage, and identify potential drop-off points.

---

## 📊 Project Overview
**Objective:**
- Explore online campaign performance.
- Analyze visitor flow through the eCommerce conversion funnel.
- Calculate the percentage of users who reached each funnel step.

**Dataset:**  
Google Analytics 4 Public Dataset (`bigquery-public-data.ga4_obfuscated_sample_ecommerce`)

**Database used for practice:**  
`ads_analysis_goit_course` (PostgreSQL)

---

## 🧠 Key Steps
1. Connected to PostgreSQL database via DBeaver for SQL practice.  
2. Accessed GA4 dataset in BigQuery.  
3. Wrote SQL queries to:
   - Identify user events and session data.
   - Calculate funnel steps: *view_item → add_to_cart → begin_checkout → purchase*.  
4. Measured conversion rates and interpreted results.

---

## 🧰 Tools & Technologies
- **SQL**
- **Google BigQuery**
- **Google Analytics 4 Dataset**
- **PostgreSQL**
- **DBeaver**

---

## 🔗 Queries & Resources
- [BigQuery SQL #1 – Funnel Step Analysis](https://console.cloud.google.com/bigquery?sq=783479339854:6e4b170628c7445c933b1ffd44397b31)
- [BigQuery SQL #2 – Conversion Rate Calculation](https://console.cloud.google.com/bigquery?sq=783479339854:bf79ae292ffc40c088435da5cc4e2c66)
 SQL Queries (queries.sql)](./sql_main.sql)
---

## 💬 Summary
This project demonstrates data exploration and SQL querying skills in cloud analytics platforms.  
It focuses on understanding user behavior, campaign effectiveness, and conversion optimization using real-world eCommerce data.
