# Customer-Churn-Analysis-Engagement-Segmentation-Dashboard
 --This Power BI project analyzes churn behavior across 10,000 banking customers by exploring demographic, financial, and behavioral features. 
 
 --The goal is to uncover key churn drivers, segment high-risk customers, and support retention strategies with data-driven insights.
## Project Overview
 **Tool Used**: Power BI,Excel
- **Dataset**: 10,000 bank customers (CSV format)
- **Techniques**: DAX Measures, Calculated Columns, Conditional Formatting, Decomposition Trees, Scatter Plots, Heatmaps, Sankey Diagrams
- **KPIs Tracked**: Churn Rate %, Retention %, Customer Activity, Product Usage, Balance Bands, Salary Segments

##Link Of Dashboard

 <a href="https://github.com/sah777s/Customer-Churn-Analysis-Engagement-Segmentation-Dashboard">Dashboard</a>

## 🧠 Business Questions Solved

1. What is the overall customer churn rate and how is it trending?
2. Which countries have the highest churn rates?
3. Are older customers more likely to churn?
4. Do inactive customers churn more than active ones?
5. How does gender influence churn behavior across regions?
6. What impact does tenure have on churn risk?
7. Does low balance correlate with churn?
8. Which product ownership patterns indicate loyalty?
9. Can we identify high-value but high-risk customers?
10. What are the key drivers of churn across all segments?

---

## 📊 Key Insights

- **Overall Churn Rate**: 20.37%
- **Germany** shows highest churn (32.44%) among countries.
- **Customers aged 51–60** have highest churn (56.21%).
- **Inactive users** churn at 26.85% vs 14.27% for active ones.
- **High-Value High-Risk** segment churns at **97.5%**.
- **Customers with 2 products** show lowest churn (7.58%); 3+ products spike unexpectedly.
- **Low balance (≤₹50K)** customers churn at 34.67%.
- Built engagement scoring model:
  - Very Low Engagement → 65.46% churn
  - High Engagement → 14.11% churn
 
#  🔄 Project Process

## 📥 Data Sourcing

Downloaded customer churn dataset from Kaggle.

Included 10,000 customers with demographic, financial, and behavioral fields.

## 🧹 Data Cleaning & Prep

Removed irrelevant columns (RowNumber, Surname), ensured data types.

Created calculated columns: age groups, tenure bands, credit score tiers, engagement segments.

## 📊 Data Modeling in Power BI

Built DAX measures for churn rate, retention, active/inactive split, product usage, and high-risk segmentation.

Defined relationships and formatting for interactivity.

## 📈 Dashboard Development

Built visuals: KPI cards, bar charts, scatter plots, decomposition tree, heatmaps, and Sankey diagram.

Enabled slicers for drilldown by geography, gender, tenure, and engagement.

## 📌 Insights & Delivery

Identified churn hotspots (Germany, age 51–60, inactive users, low balance).

Flagged high-value high-risk customers for prioritized retention.

Delivered interactive Power BI dashboard with actionable insights.

### 📊 Churn Overview Dashboard

![image alt](https://github.com/sah777s/Customer-Churn-Analysis-Engagement-Segmentation-Dashboard/blob/b070d6410d303052d23fb0ff018851dd01f52b01/1.png)
![image alt](https://github.com/sah777s/Customer-Churn-Analysis-Engagement-Segmentation-Dashboard/blob/main/2.png)
![image alt](https://github.com/sah777s/Customer-Churn-Analysis-Engagement-Segmentation-Dashboard/blob/main/3.png)
![image alt](https://github.com/sah777s/Customer-Churn-Analysis-Engagement-Segmentation-Dashboard/blob/main/4.png)
![image alt](https://github.com/sah777s/Customer-Churn-Analysis-Engagement-Segmentation-Dashboard/blob/main/5.png)

#  📌 Project Insights – Customer Churn Analysis

🔄 Overall churn rate is 20.37%, with 2,037 out of 10,000 customers having exited.

🌍 Germany has the highest churn rate at 32.44%, compared to France (16.15%) and Spain (16.67%).

👵 Customers aged 51–60 are most likely to churn, with a churn rate of 56.21%.

👩‍🦰 Female customers account for 60.37% of churned users, compared to 39.63% male.

❌ Inactive members churn at 26.85%, nearly double the rate of active members (14.27%).

💳 Credit card holders show significant churn, tracked through a dedicated KPI (7,055 users).

💵 Low-balance customers (≤₹50K) churn at 34.67%, while zero-balance customers show only 13.82% churn.

📦 Customers with 2 products are most loyal (7.58% churn), while those with 3+ products churn at alarming rates (up to 100%).

⚠️ A High-Risk Segment was identified with 86.90% churn from a group of 145 customers.

🔥 High-Value High-Risk customers (e.g., high balance but inactive, aged >50) show 97.5% churn.

🧠 Created Engagement Segments:

Very Low Engagement → 65.46% churn

High Engagement → 14.11% churn

📊 Advanced visuals like decomposition trees, heatmaps, scatter plots, and Sankey diagrams helped uncover multidimensional churn patterns.

# Final Conclusion

This Power BI dashboard uncovers key churn drivers and empowers targeted retention strategies through data-driven customer segmentation


