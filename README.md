# 📌 Executive Summary

Analyzed **100,000+ real-world e-commerce orders** from the Brazilian Olist dataset using **Google BigQuery and Power BI** to uncover revenue trends, logistics inefficiencies, and customer value segmentation opportunities.

This project demonstrates advanced SQL proficiency, large-scale data analysis, and business-driven insight generation.

## Retail Growth & Customer Intelligence Analysis (Olist E-Commerce)

![Dashboard Preview](Power%20BI%20Dashboard/Dashboard.png)

---

# 📂 Repository Structure

| Folder | Description |
|--------|-------------|
| /SQL Query | BigQuery SQL scripts used for analysis |
| /Power BI Dashboard | Interactive dashboard and visuals |
| /Input Data | Dataset reference |

---

## 🛠 Tools & Technologies

- SQL (Google BigQuery)
- Power BI (DAX, Power Query)
- Excel

### SQL Concepts Applied
- Joins
- CTEs
- Window Functions (LEAD)
- Aggregations
- Set Operators (UNION, INTERSECT, EXCEPT)
- Time-based analysis

---

## 📊 Key Insights & Strategic Recommendations

### 1️⃣ Supply Gap Analysis – Logistics Optimization

**Finding:**  
Identified **3,779 City/State combinations** where customer demand exists but no local sellers operate.

**Business Impact:**  
Orders from these cities rely on long-distance shipping, increasing freight costs and delivery times.

**Recommendation:**  
Launch targeted seller acquisition campaigns in these municipalities to:
- Reduce freight costs
- Improve delivery speed
- Strengthen regional marketplace penetration

**Method Used:**  
SQL `EXCEPT DISTINCT` to compare customer locations with seller locations.

---

### 2️⃣ Same-Day Delivery Opportunity ("Golden Cities")

**Finding:**  
Identified **531 cities** where both customers and sellers coexist at scale.

**Business Impact:**  
High potential for same-day delivery due to localized supply and demand.

**Recommendation:**  
Introduce a premium same-day delivery filter in these cities to:
- Improve customer satisfaction
- Increase conversion rates
- Differentiate marketplace offerings

**Method Used:**  
SQL `INTERSECT DISTINCT` to identify overlapping supply-demand cities.

---

### 3️⃣ Unified VIP Segmentation

**Finding:**  
Created a unified Top 40 list of:
- Top 20 Customers by Spend
- Top 20 Sellers by Revenue

**Business Impact:**  
High-value users contribute disproportionately to total revenue.

**Recommendation:**  
Develop a consolidated loyalty & incentive program targeting these high-value customers and sellers.

**Method Used:**  
SQL `UNION ALL` combining ranked customer and seller aggregates.

---

# 📈 Additional Analytical Areas Covered

- Year-over-year revenue comparison (2017 vs 2018)
- Month-on-month order growth trends
- Delivery time vs estimated delivery performance
- Freight cost comparison by state
- Payment type and installment behavior analysis
- Time-of-day order segmentation

---

## 🎯 What This Project Demonstrates

- Large-scale relational data analysis (100k+ records)
- Advanced SQL proficiency
- Business-focused insight extraction
- Logistics and marketplace optimization analysis
- Data storytelling through dashboards
