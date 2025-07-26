# 🔥 SEO Campaign Dashboard

This Power BI dashboard delivers actionable insights into the performance of an SEO campaign based on website traffic data. It enables users to monitor visitor behavior, evaluate traffic sources, and track conversions over time.

👉 [**View the live dashboard here**](https://app.powerbi.com/view?r=eyJrIjoiOTJhNmMzZjYtMmJhMS00MGYyLWIxMGMtN2ZlZTA1MjkyMjAyIiwidCI6IjZhYzJhZDA2LTY5MmMtNDY2My1iN2FmLWE5ZmYyYTg2NmQwYyIsImMiOjEwfQ&pageName=ReportSection)

[![SEO Dashboard Preview](https://github.com/ntmh12/da-projects/raw/main/SEO%20CAMPAIGN/preview.png)](https://app.powerbi.com/view?r=eyJrIjoiNTBmNGFhYzMtZGMxYS00Y2JlLThhMzQtMmZhNzJmOTQ0MDU2IiwidCI6IjZhYzJhZDA2LTY5MmMtNDY2My1iN2FmLWE5ZmYyYTg2NmQwYyIsImMiOjEwfQ%3D%3D&pageName=ReportSection)

---

## 📂 Key Features

- Total views, users, and conversion rate over time
- Traffic by day, hour, and day of week
- User segmentation by type (e.g. student, staff)
- Top-performing content by views
- Conversion funnel: from view → list addition → order
- Custom filters for traffic source, user type, and date range
- Drill-down interactions to analyze behavior trends
- Visual storytelling with SEO campaign KPIs

---

## 🧹 Data Preparation

The dataset is sourced from **web advertising performance data**, exported from internal systems. Data preparation involved the following steps:

- **Cleaned raw data in Excel**:
  - Removed redundant columns
  - Fixed invalid or inconsistent date formats
- **DAX Measures**:
  - Calculated metrics such as `Conversion Rate`, `Bounce Rate`
- **Power Query Transformations**:
  - Extracted traffic sources from `MA Referrer` field
  - Categorized users as `Normal`, `Staff`, or `Student`
  - Parsed and classified school information from email domains

---

## 🛠️ Tools & Technologies

- **Power BI**: Data visualization, DAX calculations, dashboard UI
- **Excel**: Initial cleanup and column pruning
- **Power Query**: Data transformation, column extraction, type detection
- **DAX**: Business metrics like conversion rate, bounce rate
- **Visual Design**: Brand-aligned storytelling and responsive layout

---

## 🗝️ Additional Highlights

- Custom slicers for user type, date range, and traffic source
- Hourly and daily traffic visualizations to find engagement peaks
- Top users by order volume and access frequency
- User type breakdown to evaluate staff/student behavior patterns
- Keyword/topic ranking based on view counts
- Clear conversion funnel for marketing evaluation

---

**The end!**
