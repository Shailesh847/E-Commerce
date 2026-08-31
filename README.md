# eCommerce Customer Segmentation & Behavioral Analysis

## Project Overview

Every customer is different. Some customers purchase frequently, some spend more, while others may be losing interest.

This project focuses on analyzing eCommerce customer data and dividing customers into meaningful groups based on their purchasing behavior and customer value.

The goal is to understand different customer segments and identify suitable marketing strategies for each group.

---

## Business Objective

The main objective of this project is to:

- Analyze customer purchasing behavior
- Segment customers based on their value and activity
- Identify high-value and at-risk customers
- Understand behavioral differences between customer groups
- Provide actionable marketing recommendations
- Create a structured customer segmentation framework

---

## Dataset

The dataset contains simulated eCommerce customer data created for educational and analytical purposes.

The analysis was performed using a small customer dataset to demonstrate how customer segmentation can be implemented in a real-world eCommerce scenario.

### Key Data Fields

Depending on the available customer information, the dataset contains fields related to:

- Customer ID
- Customer demographics
- Customer spending
- Purchase/order frequency
- Recency or customer activity
- Other customer attributes

---

## Tools Used

- **Microsoft Excel** – Data cleaning, calculations, segmentation and analysis
- **Excel Charts** – Data visualization
- **Microsoft Word** – Detailed project documentation

---

## Customer Segmentation Methodology

The customer segmentation framework uses customer value and purchasing behavior.

Three major customer segments were created:

### 1. High Value / Loyal

These are customers with relatively high customer value and stronger purchasing activity.

**Recommended strategies:**
- Loyalty rewards
- VIP benefits
- Early access to new products
- Personalized recommendations
- Cross-selling and upselling

---

### 2. Regular / Growth

These customers show moderate purchasing activity and have potential to become high-value customers.

**Recommended strategies:**
- Personalized product recommendations
- Discount bundles
- Loyalty points
- Free shipping offers
- Increase purchase frequency

---

### 3. Low Value / At Risk

These customers have relatively lower activity or value and may require re-engagement.

**Recommended strategies:**
- Re-engagement campaigns
- Limited-time offers
- Personalized discounts
- Product reminders
- Customer feedback surveys

---

## Segmentation Logic

A `Value_Score` was created using the available customer behavior measures.

The score considers:

- **Spend Score** – Customer spending level
- **Frequency Score** – Purchase/order activity
- **Recency Score** – How recently the customer interacted or purchased, when available

The final score is used to assign customers to segments.

| Value Score | Customer Segment |
|---|---|
| ≤ 35 | Low Value / At Risk |
| > 35 and ≤ 65 | Regular / Growth |
| > 65 | High Value / Loyal |

---

## Project Workflow

The project followed these steps:

1. Understand the customer dataset
2. Review available customer attributes
3. Clean and prepare the data
4. Calculate customer behavior scores
5. Create the customer value score
6. Assign customers to segments
7. Compare customer segments
8. Analyze behavioral patterns
9. Create charts and visualizations
10. Develop marketing recommendations

---

## Key Analysis

The analysis focuses on questions such as:

- How many customers belong to each segment?
- Which segment contains the most customers?
- Which customers have the highest spending?
- Which customers purchase more frequently?
- Which customers may require re-engagement?
- How can marketing strategies differ between customer groups?

---

## Dashboard / Visualization Ideas

The analysis can be presented through an Excel or Power BI dashboard containing:

- Total Customers
- Total Revenue / Customer Spend
- Average Customer Spend
- Average Purchase Frequency
- Customer Segment Distribution
- Average Spend by Segment
- Purchase Activity by Segment
- Customer-level segmentation table

---

## Business Recommendations

Based on customer segmentation, an eCommerce company can use different strategies for different customer groups instead of sending the same campaign to everyone.

### High Value / Loyal
Focus on customer retention and increasing lifetime value.

### Regular / Growth
Focus on increasing purchase frequency and average order value.

### Low Value / At Risk
Focus on reactivation and understanding why customer engagement is decreasing.

---

## Key Learning

The biggest learning from this project is that customer segmentation is not only about creating customer groups.

The real value comes from understanding **why customers behave differently** and using those insights to support better business decisions.

---

## Project Files

This repository contains:

- `eCommerce_Customer_Segmentation_Excel_Project.xlsx` – Customer dataset and Excel analysis
- `eCommerce_Customer_Segmentation_Report.docx` – Detailed project report
- `README.md` – Project documentation

---

## Future Improvements

This project can be further improved by:

- Implementing RFM (Recency, Frequency, Monetary) analysis
- Using K-Means clustering
- Creating an interactive Power BI dashboard
- Performing customer lifetime value analysis
- Building customer churn prediction models
- Adding cohort analysis
- Analyzing customer purchase trends over time

---

## Conclusion

Customer segmentation helps eCommerce businesses understand their customers and create more targeted strategies.

By dividing customers into **High Value / Loyal, Regular / Growth, and Low Value / At Risk** groups, businesses can focus their marketing efforts on the customers who need the most attention and have the greatest potential value.

This project demonstrates how basic customer analytics can be transformed into practical business recommendations using Excel.

---

## Author

**Shailesh Kumar Verma**

Aspiring Data Analyst

Skills: Excel | Power BI | SQL | Data Analysis | Data Visualization
