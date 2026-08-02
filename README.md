# IDXExchange
# 🏠 MLS Housing Market Analytics Pipeline

An end-to-end real estate analytics project built to transform raw MLS transaction data into actionable market intelligence through Python and Tableau.

This project processes residential Multiple Listing Service (MLS) data, performs cleaning and feature engineering, enriches transactions with mortgage rate data from FRED, detects outliers, and generates datasets for interactive Tableau dashboards focused on housing market trends and competitive intelligence.

---

## Overview

This repository demonstrates a complete analytics workflow used for housing market analysis:

1. **Aggregate monthly MLS datasets**
2. **Validate and clean raw transaction data**
3. **Enrich data with external economic indicators**
4. **Engineer key market metrics**
5. **Detect and flag outliers**
6. **Create analysis-ready datasets**
7. **Build Tableau dashboards for market and competitive analysis**

---

## Features

### Week 1: Data Aggregation
- Combine monthly MLS listing and sold files
- Filter to residential properties
- Create unified time-series datasets

### Weeks 2-3: Exploratory Data Analysis
- Missing value analysis
- Distribution summaries
- Data quality checks
- Property type breakdowns

### Week 4: External Data Enrichment
- Pull 30-year mortgage rates from FRED
- Resample weekly data to monthly averages
- Merge economic indicators with MLS transactions

### Week 5: Data Cleaning
- Date conversion and validation
- Numeric type corrections
- Missing value handling
- Geographic coordinate checks
- Invalid record flagging

### Week 6: Feature Engineering
Generate metrics such as:

- Price Ratio
- Close-to-Original List Ratio
- Price Per Square Foot
- Days on Market
- Listing-to-Contract Days
- Contract-to-Close Days
- Year-Month variables

### Week 7: Outlier Detection
- IQR-based outlier identification
- Flag extreme observations without deleting raw records
- Create filtered analysis datasets

### Weeks 8-10: Tableau Dashboards
#### Market Analysis
- Median close price trends
- Average days on market
- Close-to-list ratio
- New listings
- Closed sales

#### Competitive Intelligence
- Top agents by sales volume
- Top offices by transactions
- ZIP code heat maps
- Sales volume analysis

### Weeks 11-12: Summarizing Findings for Santa Cruz
#### One-Page Market Intelligence Report
- Market overview
- Pricing trends
- Market activity
- Competitive landscape
- Key data-driven insights

#### Final Presentation
- Overview of the data pipeline
- Data cleaning and feature engineering process
- Dashboard walkthrough
- Market insights and conclusions

