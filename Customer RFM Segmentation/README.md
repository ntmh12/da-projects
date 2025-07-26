# 👥 Customer Segmentation Dashboard

This project applies **Customer 360** and the **RFM (Recency - Frequency - Monetary)** model to classify customers into behavioral segments. It aims to help stakeholders better understand their customer base and design data-driven strategies for growth.

🔗 **[View dashboard preview](https://github.com/ntmh12/da-projects/blob/main/Google%20Merch%20Shop%20Traffic/GA4_Traffic_Source_Dashboard%20-%20Preview.png)**

---

## 📦 Data Preparation

- **Database**: Microsoft SQL Server  
- **Data source**: Two tables – `Customer_Transaction` and `Customer_Registered`  
- **Steps**:
  1. Filtered active customers (with `Stop_Date IS NULL`)
  2. Calculated:
     - **Recency**: Days since last purchase
     - **Frequency**: Number of transactions
     - **Monetary**: Total transaction value
  3. Applied **NTILE function** (quartile scoring) to assign RFM scores from 1 to 4
  4. Grouped 37 unique RFM combinations into 4 main customer segments:
     - **VIP Customers**
     - **Potential Customers**
     - **General Customers**
     - **Secondary Customers**

---

## 📊 Features

- Total revenue and total customers  
- Customer & revenue share by segment (donut charts)
- Cumulative contribution tables for both volume and value
- High-value vs low-engagement customers
- Opportunity segments for upsell/reactivation

---

## 🎯 Business Insights

- **Group 444** (VIP): Contributes 21.9% of revenue with highest engagement  
- **Group 214**: Under-engaged but high-spending → opportunity for targeted campaigns  
- **General Customers** (34.4%): Large in volume, price-sensitive  
- **Secondary Customers**: At risk of churn, require reactivation campaigns  
- **Potential Customers**: Frequent and valuable – candidates to become VIPs  

---

## 🛠 Tools & Technologies

- 🗃️ **SQL Server** – Data filtering, RFM scoring using window functions  
- 📊 **Power BI** – DAX measures, custom visuals  
- 📁 **PDF Report** – Executive summary for stakeholders

---

## 📁 Files Included

- `/Dashboard preview.png` – Screenshot of dashboard  
- `/Customer Report.pdf` – Full business analysis and presentation  
- `/SQL_RFM_Scoring.sql` – RFM calculation script

---
