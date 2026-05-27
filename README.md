# 📊 Meta Ad Performance & Analytics Dashboard

## 📌 Project Overview
This project is an end-to-end, corporate-grade Power BI dashboard designed to track and analyze advertising campaigns across Meta platforms (Facebook and Instagram). It provides actionable visibility into campaign reach, user engagement, conversion funnels, and budget utilization, enabling marketing stakeholders to optimize ad spend and platform strategy.

## 🛠️ Tech Stack & Skills Demonstrated
* **Business Intelligence:** Power BI
* **Calculations & Logic:** DAX (Data Analysis Expressions)
* **Data Architecture:** Relational Data Modeling (Star Schema), Parameterization

## 📈 Key Metrics & KPIs Analyzed
* **Visibility & Interaction:** Impressions, Clicks, Shares, Comments.
* **Efficiency Ratios:** * Clickthrough Rate (CTR)
    * Engagement Rate (Total Engagements / Impressions)
* **Conversion Funnel:** * Conversion Rate (Purchases / Clicks)
    * Purchase Rate (Purchases / Impressions)
* **Financial Tracking:** Total Campaign Budget, Average Budget per Campaign.

## ⚙️ Methodology & Workflow
1.  **Data Architecture & Modeling:** Built a robust Star Schema connecting a central Fact table (`Ad Events`) with multiple Dimension tables (`Users`, `Ads`, `Campaigns`, and a custom `Date/Calendar` table). Managed one-to-many relationships to ensure accurate metric filtering and aggregation.
2.  **DAX Implementation:** Engineered dynamic DAX measures for complex ratios (e.g., handling zero-division errors using the `DIVIDE` function), cumulative totals, and dynamic titles/parameters to switch metrics seamlessly within visuals.
3.  **Visual Analytics:** Designed interactive, multi-platform views (Facebook vs. Instagram) utilizing conditional formatting, weekly/hourly trend lines, and geographic heat maps to pinpoint high-performing demographics and timeframes. 


## 👨‍💻 About the Author
**[Ranjeet Bayas]** Data Analytics Professional specializing in Python, SQL, and Power BI. Focused on building robust data pipelines and translating raw metrics into strategic business intelligence.

💼 **LinkedIn:** (https://www.linkedin.com/in/ranjeet-bayas-556310258/)  
