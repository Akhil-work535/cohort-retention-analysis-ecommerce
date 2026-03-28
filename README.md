# 📊 User Retention Cohort Analysis for E-commerce Platform

## 🚀 Project Overview
Understanding customer retention is critical for long-term business growth.  
This project analyzes user behavior using cohort analysis to evaluate how well customers return after their first purchase.

---

## 🎯 Business Problem
Despite continuous user acquisition, businesses often struggle with retaining customers.

This project aims to answer:
- Do users return after their first purchase?
- How quickly does retention drop over time?
- Where are the major drop-off points in the user lifecycle?

---

## 📂 Dataset
- Brazilian E-commerce Public Dataset (Olist)
- Contains real-world transactional data including orders, customers, and timestamps

---

## 🛠️ Tools & Technologies
- **Python (Pandas)** – Data cleaning & transformation  
- **SQL (SQLite)** – Data storage  
- **Power BI** – Data visualization & dashboarding  

---

## 🧩 Methodology

### 1. Data Preparation
- Merged orders and customers datasets  
- Converted timestamps to monthly periods  
- Created customer-level transaction timeline  

### 2. Cohort Creation
- Grouped users by their first purchase month (cohort_month)  
- Calculated monthly activity (order_month)  

### 3. Cohort Index
- Computed time difference between first purchase and subsequent activity  
- Represented as months since first purchase  

### 4. Retention Calculation
- Counted unique users per cohort over time  
- Converted counts into retention percentages  

---

## 📊 Key Insights

- 📉 Retention drops sharply after the first month (4.38% → 0.25%)  
- 🚨 Majority of users do not return after their initial purchase  
- 📊 Long-term retention stabilizes near zero, indicating weak customer loyalty  

---

## 📈 Dashboard Highlights

- Cohort heatmap to visualize retention patterns  
- Retention trend line showing drop-off over time  
- KPI cards summarizing key retention metrics  

---

## 💡 Business Recommendations

- Improve post-purchase engagement strategies  
- Introduce retention campaigns (offers, reminders, emails)  
- Focus on enhancing early user experience to reduce churn  

---

## 🔥 Conclusion
This project highlights the importance of retention over acquisition and demonstrates how cohort analysis can uncover critical business insights.

