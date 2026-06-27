# 🛒 Cart Abandonment Analysis

An end-to-end Data Analytics project that analyzes customer behavior across an e-commerce purchase funnel to identify where users abandon their shopping journey and estimate the business impact of lost sales.

---

## 📌 Project Overview

Cart abandonment is one of the biggest challenges in e-commerce, directly affecting revenue and customer conversion. This project explores customer interactions from website visits to completed purchases, identifies bottlenecks in the sales funnel, and provides actionable business recommendations.

The project covers the complete analytics workflow:

- Data Cleaning
- Data Validation
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Funnel Analysis
- Revenue Impact Analysis
- Business Insights
- Interactive Dashboard (Power BI)

---

## 🎯 Objectives

- Analyze customer behavior across the purchase funnel.
- Calculate key business KPIs.
- Measure cart abandonment and conversion rates.
- Identify stages with the highest customer drop-off.
- Estimate potential revenue lost due to abandoned carts.
- Provide business recommendations to improve conversion.

---

## 📂 Dataset

- **Source:** Kaggle
- **Dataset:** E-commerce Cart Abandonment Dataset
- **Rows:** 120,000
- **Columns:** 17 (16 after preprocessing)

The dataset contains customer sessions, purchase funnel events, revenue information, user attributes, marketing channels, and device information.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Power BI

---

## 📋 Project Workflow

```
Business Problem
        │
        ▼
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Data Validation
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Business Insights
        │
        ▼
Power BI Dashboard
        │
        ▼
Business Recommendations
```

---

## 📊 Key Performance Indicators

| KPI | Value |
|------|-------|
| Total Sessions | 120,000 |
| Total Users | 112,352 |
| Product Views | 77,870 |
| Cart Additions | 27,156 |
| Purchases | 8,181 |
| Overall Conversion Rate | 6.82% |
| Cart Abandonment | 18,975 |
| Total Revenue | ₹17.02 Million |
| Potential Revenue Lost | ₹9.47 Million |

---

## 📈 Key Findings

- Only **6.82%** of sessions resulted in a completed purchase.
- The largest customer drop-off (**65.13%**) occurred between **Product View** and **Add to Cart**.
- Customers abandoned carts worth approximately **₹9.47 Million**, representing a significant revenue recovery opportunity.
- Mobile users accounted for nearly **70%** of total sessions.
- Device type, marketing channel, month, and user type showed minimal variation in abandonment rates.
- The dataset contains synthetic patterns (e.g., fixed abandoned cart values and deterministic discount behavior), which were identified and documented during data validation.

---

## 💡 Business Recommendations

- Improve product pages with better descriptions, reviews, and clearer pricing.
- Optimize the Add-to-Cart experience to reduce the largest funnel drop-off.
- Simplify the checkout process to improve purchase completion.
- Implement abandoned cart recovery campaigns using email or push notifications.
- Continue optimizing the mobile shopping experience due to its high traffic share.
- Validate insights using real transactional data before making strategic decisions.

---

## 📊 Dashboard

The Power BI dashboard includes:

- Executive KPI Cards
- Customer Conversion Funnel
- Revenue Earned vs Potential Revenue Lost
- Cart Abandonment by Device
- Cart Abandonment by Marketing Channel
- Monthly Cart Abandonment Trend
- User Type Analysis
- Interactive Filters


## 🚀 Future Improvements

- Analyze real-world transactional data.
- Build a machine learning model to predict cart abandonment.
- Perform A/B testing analysis.
- Integrate customer lifetime value (CLV).
- Develop real-time monitoring dashboards.

---

## 👩‍💻 Author

**Rahena Parveen M R**
