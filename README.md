# ✈️ Flight Delay Analytics Using Python

## Overview
This project analyzes 50,000 flight records to explore flight delays, cancellations, diversions, airline performance, and operational inefficiencies. The goal is to uncover meaningful patterns in flight operations and derive data-driven business insights.

## Objectives
- Analyze flight arrival and departure delays.
- Compare flight performance across airlines.
- Identify monthly and weekday delay patterns.
- Investigate cancellation and diversion rates.
- Identify major contributors to total delay minutes.
- Perform statistical hypothesis testing.
- Create meaningful features for further analysis.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Project Workflow
1. **Data Understanding & Cleaning** – Dataset exploration, data types, missing values, duplicates, invalid values and outlier investigation.
2. **Exploratory Data Analysis (EDA)** – Univariate, bivariate and multivariate analysis, airline comparisons, temporal analysis, delay causes and correlation analysis.
3. **Statistical Analysis** – Kruskal–Wallis hypothesis tests and 95% confidence interval estimation.
4. **Feature Engineering** – Created departure period, flight duration category and departure delay status.
5. **Business Insights** – Identified major operational patterns and recommendations.

## Key Findings
- Average arrival delay: **4.00 minutes**
- Flights arriving late: **35.72%**
- Cancellation rate: **1.59%**
- Diversion rate: **0.24%**
- Airline with highest average arrival delay: **NK (14.51 minutes)**
- Month with highest average arrival delay: **February (9.77 minutes)**
- Day with highest average arrival delay: **Thursday (5.44 minutes)**
- Largest delay contributor: **Late aircraft delay (205,967 total minutes)**

## Statistical Findings
Kruskal–Wallis tests identified statistically significant differences in arrival-delay distributions across:
- Airlines
- Months
- Days of the week

A 95% confidence interval was estimated for mean arrival delay:
**3.67 to 4.33 minutes**

## Business Recommendations
- Investigate airline-specific delay performance.
- Improve aircraft turnaround efficiency to reduce late-aircraft delays.
- Allocate operational resources during higher-delay periods.
- Monitor weekday and monthly delay patterns.
- Improve disruption management for cancellations and diversions.

## Project Scope
This is a data analytics project focused on data cleaning, exploratory analysis, statistical validation, feature engineering, and business insights. Predictive machine learning was not implemented.

## Repository Contents
- Jupyter Notebook containing analysis, code, and visualizations.
- Dataset, subject to redistribution permission.
- Supporting project visualizations.
- Requirements file.

## Author
**Bipin Satyankar**  
B.Tech – Computer Science and Data Science

---

*Built as a hands-on Python data analytics project.*
