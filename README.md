# Supply Chain Delivery Risk & Route Optimization System

## Executive Summary
An end-to-end data pipeline and analytics system analyzing 180,000+ supply chain records to identify carrier SLA breaches, delivery delay bottlenecks, and operational cost leaks.

## Problem Statement
Logistics networks face significant financial penalties and customer churn due to unmitigated delivery delays. This project extracts order, shipping, and routing data to build predictive delay risk models and executive KPI dashboards.

## Tech Stack & Architecture
- **Database:** SQL / PostgreSQL (Data Transformation & Aggregation)
- **Analytics & Modeling:** Python (Pandas, Scikit-Learn)
- **Visualization:** Power BI Interactive Executive Dashboard
- **Dataset:** DataCo Smart Supply Chain Dataset (180k Records)

## Key Performance Indicators (KPIs)
- On-Time In-Full (OTIF) Delivery Rate
- Late Delivery Risk Ratio by Region & Carrier
- Average Days to Ship (Scheduled vs. Actual)
- Cost Impact of Delayed Freight

## Repository Structure
```text
├── sql/                   # Analytical SQL transformation queries
├── python/                # ETL scripts and exploratory data analysis
├── dashboard/             # Power BI dashboard files (.pbix) & screenshots
├── README.md              # Project documentation
└── .gitignore             # Git exclusion rules (raw data excluded)
