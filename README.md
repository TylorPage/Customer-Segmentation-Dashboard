# Customer Segmentation Dashboard

## Overview

This project explores customer demographic and behavioral data to identify patterns in purchasing and spending habits. Using the Customer Personality Analysis dataset, I created a data dashboard aimed at understanding different customer segments and providing insights into targeting high-value groups more effectively.

## Dataset

- Source: [Kaggle – Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)
- Description: This dataset includes demographic, financial, and purchase behavior data for 2,240 customers of a retail company.
- Size: ~300 KB (CSV)
- Key Columns:
  - Age
  - Income
  - Marital Status
  - Spending Score
  - Recency (days since last purchase)
  - Products Purchased (Wines, Fruits, Meats, etc.)

## Objectives

- Identify high-value customer segments based on income and purchase activity
- Visualize customer distribution across demographic attributes (age, education, marital status)
- Explore correlations between spending score, income, and purchase categories
- Support targeted marketing decisions through segmentation analysis

## Tools Used

- Tableau Public (Data visualization and dashboard)
- Google Sheets (Initial data review and cleaning)
- GitHub (Project documentation and portfolio publishing)

## Data Cleaning Process

I cleaned the original dataset using Google Sheets with the following steps:

- Removed rows with missing `Income` values
- Standardized column names for clarity (e.g., `MntWines` → `Wines_Purchased`)

## Key Insights

- Customers with high income and low recency are typically the most active buyers
- Wine and meat purchases are the strongest indicators of overall spending
- Married customers tend to have more stable spending patterns than single or divorced individuals
- Customers over 50 showed higher loyalty and average purchase value than younger groups
- Birth year 1970 highest purchase rate of meat and wine

## Dashboard Preview

[View the Interactive Tableau Dashboard](https://public.tableau.com/)  
*Link will be updated once dashboard is published.*

## Skills Demonstrated

- Exploratory data analysis (EDA)
- Customer segmentation
- KPI reporting and dashboard creation
- Data visualization for business insights

## Next Steps

- Apply clustering techniques to group customers more accurately
- Create targeted marketing personas for each major segment
- Extend dashboard to include time-series trends and retention rates
