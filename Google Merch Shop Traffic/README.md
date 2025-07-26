# 📊 GA4 Traffic Source Dashboard

A marketing analytics dashboard built with **Google Analytics 4** data to help analyze traffic sources, user engagement, and conversion performance for the **Google Merch Shop** website.

🔗 **[View the interactive dashboard on Looker Studio →](https://lookerstudio.google.com/reporting/d1e4b149-c542-4208-9a5a-ce2b8f9d1b99)**
<p align="center">
  <img src="https://github.com/ntmh12/da-projects/blob/main/Google%20Merch%20Shop%20Traffic/GA4_Traffic_Source_Dashboard%20-%20Preview.png" alt="GA4 Dashboard Preview" width="100%" />
</p>

---

## 🔍 Overview

This dashboard provides a clear breakdown of user acquisition channels, behavior metrics, and conversion performance using data from **GA4 + Looker Studio**.

### 🎯 Key Metrics Tracked
- Total Users & Sessions
- Engagement Rate & Bounce Rate
- Session Duration
- Channel Performance
- Most Viewed Landing Pages

---

## 📦 Data Preparation

- **Extract**  
   - Enabled BigQuery linking in **Google Analytics 4** to export event data from the Google Merch Shop property.

- **Transform**  
   - Wrote custom **SQL queries in BigQuery** to:
     - Aggregate sessions by traffic channel
     - Join relevant user and event-level metrics
     - Calculate key engagement and conversion indicators

- **Load & Visualize**  
   - Connected BigQuery tables to **Looker Studio**
   - Built charts and tables using **Looker Studio visual and calculated fields**

This approach ensures scalability, flexibility, and real-time updating when working with GA4 data.

---

## 🧰 Tools & Technologies

- **Google Analytics 4 (GA4)**
- **BigQuery**
- **Looker Studio**

---

## ✅ Key Takeaways

- **Direct traffic** brings the most users but low engagement and conversion.
- **Email and Referral channels** have the highest conversion rates.
- **Organic Search** remains strong in user acquisition and revenue.
- Deep page-level insight helps optimize navigation and marketing content.

---

> Thank you for visiting!
