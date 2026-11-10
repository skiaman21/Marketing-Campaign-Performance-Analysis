# 📊 Marketing Campaign Performance Analysis

## Project Overview

This project analyzes digital marketing campaign performance across different advertising platforms, campaign types, industries, countries, and time periods.

The objective is to evaluate marketing effectiveness, understand advertising returns, identify high-performing and underperforming segments, and provide actionable recommendations to improve marketing decisions.

The project uses **Python** for data exploration and cleaning and **Power BI** for data analysis, visualization, and interactive dashboard development.

---

## 🎯 Business Problem

A company is running digital marketing campaigns across multiple advertising platforms and markets. However, it needs a clear understanding of which campaigns and platforms are generating better returns on advertising investment.

The business wants to answer questions such as:

- Which advertising platform generates the highest revenue?
- Which platform provides the best return on advertising spend (ROAS)?
- Which campaign type generates the most conversions?
- Which industries and countries deliver better advertising returns?
- How does marketing performance change over time?
- Where should the company focus its advertising budget?

The analysis aims to help marketing managers evaluate campaign effectiveness and make data-driven decisions.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data exploration and data cleaning |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Power BI | Data analysis and interactive dashboards |
| DAX | Creating calculated measures and KPIs |

---

## 📁 Dataset Information

- **Dataset:** Marketing Campaign Performance
- **Records:** 1,800
- **Columns:** 14
- **Period:** January – December 2024

### Key Dataset Columns

| Column | Description |
|---|---|
| Date | Campaign date |
| Platform | Advertising platform |
| Campaign Type | Type of marketing campaign |
| Industry | Business industry |
| Country | Target country |
| Impressions | Number of advertisement views |
| Clicks | Number of advertisement clicks |
| CTR | Click-through rate |
| CPC | Cost per click |
| Ad Spend | Advertising expenditure |
| Conversions | Number of conversions |
| CPA | Cost per acquisition |
| Revenue | Revenue generated |
| ROAS | Return on advertising spend |

---

## 🔄 Project Workflow

### 1. Data Exploration & Cleaning – Python

Python was used to understand the dataset structure and check data quality.

<img width="981" height="553" alt="dashboard page 1" src="https://github.com/user-attachments/assets/01fb0c1d-2a00-4ba3-af60-23551fa3cc9b" />


**Activities performed:**
- Imported the dataset using Pandas.
- Examined dataset dimensions and column data types.
- Checked missing values.
- Identified duplicate records.
- Checked negative values in numerical columns.
- Validated numerical data.
- Converted the date column into datetime format.

**Result:** Prepared a clean dataset for further analysis and visualization.

### 2. Data Analysis & Visualization – Power BI

The cleaned dataset was imported into Power BI to create performance measures and explore business performance.

<img width="978" height="548" alt="dashboard page 2" src="https://github.com/user-attachments/assets/c4bd31cd-db11-4f95-9879-bb320109a75f" />


**Key activities:**
- Created DAX measures for important KPIs.
- Analyzed revenue and advertising expenditure.
- Compared platform and campaign performance.
- Evaluated ROAS and CPA.
- Analyzed industry and country performance.
- Explored monthly marketing trends.
- Created interactive visualizations and slicers.

### 3. Dashboard Development – Power BI

Developed a two-page interactive dashboard.

#### Page 1: Marketing Performance Overview

Provides an overall view of marketing performance.

**Key components:**
- Total Revenue
- Total Ad Spend
- Total Conversions
- Overall ROAS
- Average CTR
- Average CPC
- Monthly Revenue vs Ad Spend
- Revenue by Platform
- Revenue by Country
- Spend Share by Platform

#### Page 2: Campaign Performance & Insights

Provides a deeper comparison of campaign effectiveness.

**Key components:**
- Campaign Performance KPIs
- Campaign Performance Details
- ROAS by Campaign Type
- Revenue vs Ad Spend by Platform
- ROAS by Industry
- Conversions by Campaign Type

**Interactive Features:**
- Date filters
- Platform filters
- Campaign and industry analysis
- Country-level filtering

---

## 📈 Key Performance Indicators (KPIs)

| KPI | Business Purpose |
|---|---|
| Total Revenue | Measures revenue generated from marketing campaigns |
| Total Ad Spend | Measures advertising investment |
| Total Conversions | Measures the volume of desired customer actions |
| CTR | Measures the percentage of impressions resulting in clicks |
| CPC | Measures the average cost per click |
| CPA | Measures the average cost per conversion |
| ROAS | Measures revenue generated for every unit spent on advertising |

---

## 🔍 Key Business Insights

### 1. Overall Marketing Performance
- Total Revenue: 54.18M
- Total Ad Spend: 11.11M
- Total Conversions: 326.8K
- Overall ROAS: 4.88x

The company generated approximately 4.88 units of revenue for every 1 unit spent on advertising.

### 2. Platform Performance
- TikTok Ads achieved the highest ROAS of 7.62x.
- TikTok Ads also recorded the lowest CPA.
- Google Ads generated the highest revenue but had the lowest platform ROAS of 3.47x.

### 3. Campaign Type Performance
- Search campaigns achieved the highest ROAS of 5.31x.
- Search campaigns also generated the highest number of conversions.
- Shopping campaigns recorded the lowest ROAS of 4.58x.

### 4. Industry Performance
- SaaS recorded the highest ROAS of approximately 5.04x.
- EdTech and E-commerce also demonstrated strong returns.
- Fintech recorded the lowest ROAS of approximately 4.48x.

### 5. Country Performance
- India recorded the highest ROAS of approximately 5.50x.
- UAE generated the highest total revenue.
- USA recorded the lowest country-level ROAS of approximately 4.16x.

### 6. Monthly Performance
- October recorded the highest monthly ROAS.
- May recorded the lowest monthly ROAS.
- December generated the highest monthly revenue.

---

## 💡 Business Recommendations

Based on the analysis, the following recommendations were identified:

1. **Optimize Platform Budget:** Gradually test increasing investment in TikTok Ads because of its higher ROAS and lower CPA.

2. **Review Google Ads:** Investigate high acquisition costs and identify opportunities to improve campaign efficiency.

3. **Improve Shopping Campaigns:** Review audience targeting, product selection, and campaign strategies to improve returns.

4. **Explore Market Opportunities:** Evaluate opportunities to expand marketing activities in India due to its higher ROAS.

5. **Review Industry Performance:** Investigate lower returns in Fintech and identify improvement opportunities.

6. **Study Monthly Trends:** Analyze October's performance to understand the factors behind its higher ROAS and use those findings in future campaign planning.

---

## ⚠️ Project Limitations

- The dataset covers only one year of marketing activity.
- Product costs and other operating expenses are not available.
- Actual business profit and profit margin cannot be calculated.
- Aggregated performance may hide differences between individual campaigns.
- Observed relationships do not necessarily establish causation.

**Note:** ROAS measures revenue relative to advertising spend. It should not be interpreted as actual business profit.

---

## 📌 Project Outcomes

Through this project, I gained practical experience in:

- Exploring and cleaning real-world structured data using Python.
- Working with Pandas and NumPy.
- Understanding marketing performance KPIs.
- Creating DAX measures in Power BI.
- Designing interactive, multi-page dashboards.
- Analyzing business performance across multiple dimensions.
- Converting analytical findings into actionable business recommendations.

---

## 👨‍💻 Author

**Aman Singh Rawat**

Aspiring Data Analyst | Python | Power BI | Excel | SQL

