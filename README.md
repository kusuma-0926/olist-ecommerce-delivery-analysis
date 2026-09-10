# Olist E-Commerce Delivery & Customer Satisfaction Analysis

## Project Overview

This project analyzes Brazilian e-commerce data from Olist to understand how delivery performance, seller behavior, geographic regions, and product categories influence customer satisfaction.

The project combines **Python for data analysis and insight generation** with **Power BI for interactive dashboard development**.

The goal is to identify delivery and customer-experience issues and translate the findings into actionable business insights.

---

## Business Questions

- How does delivery performance relate to customer review scores?
- Which regions have the highest late-delivery rates?
- Which sellers have the highest number of late deliveries?
- Which product categories receive the most negative reviews?
- What factors appear to contribute to customer dissatisfaction?

---

## Tools & Technologies

- **Python**
  - Pandas
  - Matplotlib
  - Data cleaning and exploratory analysis
  - Insight generation
- **Power BI**
  - Data visualization
  - DAX measures
  - KPI cards
  - Interactive dashboard
- **CSV**
  - Dataset used for analysis

---

## Key KPIs

| KPI | Value |
|---|---:|
| Total Orders | 96.52K |
| Late Delivery Rate | 7.82% |
| Average Late Delivery | 8.76 days |
| Average Review Score | 4.11 |
| Negative Reviews | 13.62K |

---

## Key Insights

### 1. Delivery delays are strongly associated with lower review scores

The analysis shows a clear inverse relationship between delivery delays and customer ratings.

| Review Score | Late Delivery Rate |
|---|---:|
| 1 Star | 30.1% |
| 2 Stars | 17.6% |
| 3 Stars | 8.5% |
| 4 Stars | 3.4% |
| 5 Stars | 1.8% |

Orders receiving 1-star reviews were late far more frequently than orders receiving 5-star reviews.

This indicates that delivery punctuality is an important factor associated with customer satisfaction.

---

### 2. Regional delivery performance varies significantly

The regional analysis shows noticeable differences in late-delivery rates.

- **Northeast:** 13.7%
- **North:** 9.5%
- **Central-West:** 7.7%
- **Southeast:** 7.2%
- **South:** 6.8%

The Northeast has the highest late-delivery rate among the five regions analyzed.

These geographic differences may indicate variations in logistics and delivery performance across regions.

---

### 3. Seller performance varies considerably

The analysis identified sellers with significantly higher late-delivery volumes.

Seller performance was evaluated using:

- Late-delivery rate
- Average delivery delay
- Order volume

This helps distinguish between sellers with consistently poor delivery performance and sellers where a high number of late deliveries may be influenced by their overall order volume.

---

### 4. Some product categories have higher negative-review volumes

The dashboard highlights the product categories with the highest number of negative reviews.

The leading categories include:

- Watches & Gifts
- Telephony
- Toys
- Stationery
- Tablets / Printing / Image

This suggests that customer dissatisfaction is not driven by delivery performance alone and may also be related to product expectations and category-specific issues.

---

## Dashboard

The Power BI dashboard provides an overview of:

- Overall order performance
- Average delivery delay
- Average review score
- Late-delivery percentage
- Negative reviews
- Top sellers by late deliveries
- Top product categories by negative reviews
- Late deliveries vs. review scores
- Late-delivery rate by region

### Dashboard Preview

![Olist E-Commerce Dashboard](dashboard.png)

---

## Project Workflow

```text
Raw E-Commerce Data
        ↓
Data Cleaning & Preparation
        ↓
Exploratory Data Analysis in Python
        ↓
Identify Business Insights
        ↓
Create DAX Measures
        ↓
Build Power BI Dashboard
        ↓
Business Recommendations
