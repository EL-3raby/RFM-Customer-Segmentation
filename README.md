# Customer Segmentation using RFM Analysis

## 📌 Business Problem
E-commerce businesses often struggle to identify their most valuable customers and those at risk of churning. Treating all customers the same leads to wasted marketing budgets and lost revenue.

## 💡 Solution
This project implements an **RFM (Recency, Frequency, Monetary)** model in Python to automatically segment a customer base into actionable tiers (VIP, Loyal, At Risk, New). 

## 🛠️ Tech Stack & Methodology
- **Python Data Stack:** Pandas, NumPy.
- **Statistical Visualization:** Seaborn, Matplotlib.
- **Logic:** - Calculated days since last purchase (Recency).
  - Counted total transactions (Frequency).
  - Summed total lifetime spend (Monetary).

## 📈 Key Visualizations Included
1. **Segment Distribution:** Bar charts highlighting the ratio of healthy vs. at-risk customers.
2. **Value Clusters:** Scatter plots identifying high-frequency/high-spend anomalies.
3. **Spend Variance:** Boxplots showing the monetary distribution within each segment.
4. **Churn Indicator:** Recency histograms to spot drop-off trends.

## 🚀 Business Value
The output is a fully segmented `.csv` database ready to be imported into any CRM (HubSpot, Mailchimp) for targeted email campaigns, increasing ROI on marketing spend.
