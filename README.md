🛍️ Project Description: Customer Shopping Behavior Analysis
1. Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.
The goal is to uncover spending patterns, product preferences, and customer segments to support better business and marketing decisions.

2. Objectives

Identify key factors influencing customer purchases.

Understand product popularity, discount impact, and seasonality.

Analyze demographic-based shopping behavior (age, gender, subscription).

Create an interactive Power BI dashboard to visualize insights.

Provide recommendations for customer engagement and revenue growth.

3. Dataset Summary

Total Rows: 3,900

Columns: 18

Key Features:

Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping Behavior: Discount Applied, Previous Purchases, Review Rating, Shipping Type

Missing Data: 37 missing values in “Review Rating” — filled using median values for each category.

4. Tools and Technologies

Python: Data Cleaning, Feature Engineering, Exploratory Data Analysis (EDA)

Libraries Used: pandas, numpy, matplotlib, seaborn

Power BI: Interactive dashboard and visualization

5. Methodology
Step 1: Data Preparation

Imported dataset using pandas and explored structure with .info() and .describe().

Handled missing values using median imputation.

Standardized column names for readability.

Created new derived columns:

age_group (categorized as Teen, Adult, Senior)

purchase_frequency_days to measure customer activity levels

Removed redundant columns like promo_code_used.

Step 2: Exploratory Data Analysis (EDA)

Performed statistical summaries and correlation analysis.

Visualized:

Revenue distribution by gender and age group

Top 10 purchased products and categories

Impact of discounts and seasons on purchase amount

Relationship between subscription status and spending

Review ratings vs. purchase frequency

Step 3: Feature Engineering and Insights

Grouped data to find high-spending customer segments.

Identified discount-dependent items and customer loyalty patterns.

Observed express shipping users as higher spenders.

Analyzed seasonal purchasing patterns to identify demand peaks.

Step 4: Dashboard Creation (Power BI)

Designed an interactive dashboard to visually present:

Total Revenue and Average Order Value

Sales by Gender, Age Group, and Subscription

Top 5 Products and Categories

Discount Usage vs. Revenue Impact

Customer Segmentation and Repeat Purchase Trends
