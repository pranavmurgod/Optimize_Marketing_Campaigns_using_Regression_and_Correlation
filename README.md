# Optimize_Marketing_Campaigns_using_Regression_and_Correlation

## Marketing Strategy Analysis
This project provides a comprehensive analysis of marketing strategies to determine their impact on sales across different client types. By applying feature engineering, exploratory data analysis (EDA), and statistical modeling, it examines the influence of various campaigns and sales approaches on sales performance, providing targeted recommendations for marketing strategies.

## Project Overview
In competitive markets, it’s crucial to understand the effectiveness of different marketing strategies to maximize sales. This analysis addresses two key questions:

What impact do each marketing strategy and sales visit have on sales (amount collected)?
Are specific strategies more effective for different client types?

## Table of Contents
Introduction
Data Loading and Quality Checks
Feature Engineering
Exploratory Data Analysis and Statistical Analysis
Final Recommendations

## Introduction
The goal of this project is to evaluate how various marketing strategies affect sales. Through regression, correlation analysis, and feature engineering, the study investigates the impact of campaigns (Email, Flyer, Phone) and sales contact points (Sales Contact 1–5) on sales, categorized by client type.

## Data Loading and Quality Checks
Data Import: Loaded data from Campaign Data.csv and performed quality checks.
Initial Exploration: Verified data types, checked for missing values, and reviewed basic statistics.
Libraries Used: pandas, numpy, seaborn, and scipy.stats.

## Feature Engineering
Date Processing: Converted date columns to datetime format and extracted month and year attributes.
Additional Features: Created new columns for month and year to aid in time-based analysis.

## Exploratory Data Analysis and Statistical Analysis
1. Data Distribution:
Reviewed distribution by account types and sales differences.
2. Statistical Analysis:
Conducted correlation and regression analyses to identify the impact of each strategy on sales.
Explored the influence of competition and account types on sales performance.
3. Market Strategy Impact on Sales:
Calculated the correlation of each marketing and sales strategy on total sales, with a breakdown by client type for more nuanced insights.
4. Regression Analysis:
Created regression models to understand the contribution of each strategy.
Analyzed effectiveness by account type for targeted marketing insights.

## Final Recommendations
This analysis provides ROI estimates per campaign and identifies optimal strategies for different client types. For example, medium facility clients showed a high return on flyer campaigns, generating an average of $4 for every dollar spent, with Sales Contact 2 being most effective.

## Key Findings:
High ROI Campaigns: Specific campaigns and sales contacts yield high returns for different account types.
Targeted Strategies: Using segmented strategies by client type optimizes budget allocation, potentially increasing overall sales.

## Technologies Used
Python
Libraries: pandas, numpy, seaborn, statsmodels

## Conclusion
This project illustrates the value of targeted marketing strategies. By leveraging statistical analysis, this study provides actionable recommendations to maximize marketing ROI and sales impact. If you’re interested in further details or potential improvements, feel free to reach out!






