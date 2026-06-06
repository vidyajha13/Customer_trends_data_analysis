# 🛒 Customer Shopping Behavior Analysis

## 📖 Project Overview

Customer behavior is one of the most critical factors influencing business growth in the retail industry. Understanding how customers shop, spend, and respond to discounts or subscriptions enables organizations to make better strategic decisions.

This project analyzes customer transaction data containing **3,900 purchase records** to uncover insights related to customer demographics, purchasing patterns, product performance, subscription behavior, and revenue generation.

Using **Python, PostgreSQL, and Power BI**, the project follows a complete analytics lifecycle from data cleaning and feature engineering to business analysis and dashboard development.

---

## 🎯 Business Problem

Retail businesses often struggle to answer questions such as:

- Which customer segments generate the highest revenue?
- Do subscribers spend more than non-subscribers?
- Which products perform best within each category?
- How effective are discounts in driving sales?
- Which age groups contribute the most revenue?
- Are repeat buyers more likely to subscribe?

This project addresses these questions through data-driven analysis.

---

## 📊 Dataset Information

| Attribute | Details |
|------------|-----------|
| Dataset Size | 3,900 Records |
| Features | 18 Columns |
| Data Type | Customer Transaction Data |
| Missing Values | Review Rating Column |
| Industry | Retail / E-Commerce |

### Key Variables

#### Customer Information
- Customer ID
- Age
- Gender
- Location
- Subscription Status

#### Purchase Information
- Item Purchased
- Category
- Purchase Amount
- Season
- Size
- Color

#### Behavioral Information
- Previous Purchases
- Frequency of Purchases
- Review Rating
- Shipping Type
- Discount Applied

---

## 🛠️ Technology Stack

| Tool | Purpose |
|--------|---------|
| Python | Data Cleaning & Feature Engineering |
| Pandas | Data Manipulation |
| PostgreSQL | Business Analysis |
| SQL | Analytical Queries |
| Power BI | Dashboard Development |
| Jupyter Notebook | Development Environment |

---

## 🔄 Project Workflow

```text
┌──────────────────────────────────────┐
│ Customer Shopping Dataset (CSV)      │
│ 3,900 Records | 18 Features          │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│ Data Exploration (Python)            │
│ • Pandas                             │
│ • df.info()                          │
│ • df.describe()                      │
│ • Missing Value Analysis             │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│ Data Cleaning & Preparation          │
│ • Median Imputation                  │
│ • Column Standardization             │
│ • Data Validation                    │
│ • Redundancy Removal                 │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│ Feature Engineering                  │
│ • Age Group Creation                 │
│ • Purchase Frequency Metrics         │
│ • Customer Segmentation Variables    │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│ PostgreSQL Integration               │
│ • SQLAlchemy                         │
│ • PostgreSQL Database                │
│ • Data Loading from Python           │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│ SQL Business Analysis                │
│ • Aggregations                       │
│ • CASE Statements                    │
│ • CTEs                               │
│ • Window Functions                   │
│ • ROW_NUMBER()                       │
│ • Revenue Analysis                   │
│ • Customer Segmentation              │
│ • Product Performance Analysis       │
│ • Subscription Analysis              │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│ Data Visualization (Power BI)        │
│ • KPI Cards                          │
│ • Bar Charts                         │
│ • Pie Charts                         │
│ • Slicers & Filters                  │
│ • Interactive Dashboard              │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│ Business Insights                    │
│ • Revenue Drivers                    │
│ • Customer Behavior                  │
│ • Product Preferences                │
│ • Discount Impact                    │
│ • Subscription Trends                │
└──────────────────┬───────────────────┘
                   │
                   ▼
┌──────────────────────────────────────┐
│ Strategic Recommendations            │
│ • Loyalty Programs                   │
│ • Subscription Growth                │
│ • Marketing Optimization             │
│ • Product Promotion Strategy         │
└──────────────────────────────────────┘
