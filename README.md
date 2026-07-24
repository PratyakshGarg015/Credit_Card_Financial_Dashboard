# Credit Card Customer & Transaction Analysis Dashboard

An interactive Power BI dashboard analyzing credit card customer demographics and transaction behavior to uncover revenue drivers and high-value customer segments.

## 📊 Overview

This project analyzes a credit card portfolio spanning **₹56.5M in revenue** and **667K+ transactions** across **10,000+ customer records**, combining customer demographic data with transaction-level detail to answer a core business question: *which customers and card products actually drive revenue, and why?*

## 🎯 Key Insights

- **Card tier concentration:** The **Blue card tier drove 83% of total revenue** (₹47.2M of ₹56.5M), despite being the entry-level product — highlighting a highly concentrated revenue base.
- **Customer segments:** **Businessmen (31%)** and **Graduates (41%)** emerged as the top-revenue customer segments by occupation and education level.
- **Quarterly trends:** Transaction volume grew **6% QoQ** (163K → 173K transactions), with revenue holding steady at roughly **₹14M/quarter**.

## 🛠️ Tools & Tech Stack

- **Power BI** — dashboard design, data modeling, visualization
- **Excel** — initial data cleaning and exploration
- **DAX** — 10+ custom measures for KPIs including revenue, transaction volume, and customer segmentation
- **Power Query** — data transformation and cleaning pipeline

## 📈 Dashboard Features

- **Customer Report:** revenue and interest breakdown by age group, marital status, income group, dependents, education, and state
- **Transaction Report:** quarterly revenue/transaction trends, revenue by card category, expenditure type, chip usage, occupation, and education level
- Interactive filters/slicers for quarter, gender, card category, and transaction channel (swipe/chip/online)

## 🔍 Methodology

1. Cleaned and transformed raw customer and transaction data using Power Query
2. Built a relational data model linking customer demographics to transaction-level records
3. Created 10+ DAX measures to calculate KPIs (revenue, interest earned, transaction counts, segment-wise breakdowns)
4. Designed two dashboard views (Customer Report, Transaction Report) with cross-filtering slicers for interactive exploration
5. Surfaced actionable insights on customer segmentation and card-tier performance to support data-driven business decisions

## 📁 Files

- Dashboard screenshots/exports included in this repository

---
*Built as an independent data analytics project to demonstrate end-to-end BI dashboard development — from raw data to actionable business insight.*
