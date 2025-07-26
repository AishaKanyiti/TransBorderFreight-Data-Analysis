# 📦 TransBorder Freight Data Analysis (2020–2024)


### Project Overview
This project analyzes cross-border freight data from the Bureau of Transportation Statistics (BTS) for the USA, Canada, and Mexico (2020–2024).
The goal is to uncover trade patterns, freight movement trends, top commodities, and transport modes while identifying areas for efficiency improvement and actionable recommendations.

### Key Objectives
Uncover Freight Movement Patterns – Analyze trends in trade value and weight by mode, region, and commodity.

Identify Operational Inefficiencies – Investigate delays and underutilized infrastructure.

Assess Environmental Impact – Evaluate freight weight as a proxy for emissions by mode.

Analyze Economic Disruptions – Assess year-over-year trade fluctuations.

Provide Data-Driven Recommendations – Support decisions on trade efficiency and infrastructure planning.

### 📂 Dataset
Source: Bureau of Transportation Statistics (BTS)

Period: 2020–2024

Key Fields: Trade Type, Country, State/Province, Mode of Transport, Value, Weight, Commodity

### Tools Used
Tool	Purpose
Python	Data cleaning, merging, and feature engineering
Pandas/Matplotlib/Seaborn	Data wrangling and EDA
Power BI	Interactive dashboard and data visualization
GitHub	Version control and project documentation

### Methodology (CRISP-DM)
#### Business Understanding
Defined objectives and key business questions (e.g., trade trends, top commodities, mode usage, YoY growth).

#### Data Understanding
Examined structure, missing values, and column meanings using BTS documentation.

#### Data Preparation
Merged yearly CSV files (2020–2024).

Cleaned missing values for USASTATE, MEXSTATE, and CANPROV.

Created mappings for trade types, modes, and commodities.

Performed feature engineering (Region column, MonthNumber for sorting, etc.).

#### Modeling / Visualization
Built Power BI dashboards:

Freight Overview & Trends

Freight Weight & Mode Analysis

Regional Freight Distribution

#### Evaluation
Identified top commodities (Machinery, Vehicles, Mineral Fuels).

Trucks dominate freight transport; USA exports lead trade value.

Trade grew until 2022 with slight decline afterward.

### Key Insights
Machinery contributes the highest trade value.

Mineral fuels dominate freight weight.

Trucks are the most used transport mode.

Trade peaked in 2022, then slightly declined.

### Recommendations
Invest in infrastructure upgrades for high-volume truck routes.

Promote logistics optimization to reduce delays and costs.

Support high-value commodities through trade-friendly policies.
