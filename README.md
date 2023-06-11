# Relax-Takehome-Challange
# User Adoption Analysis

## Introduction
This analysis aims to identify factors predicting future user adoption based on user engagement data. The dataset includes user account information and usage summaries. An "adopted user" is defined as a user who logged into the product on three separate days within a seven-day period.

## Data Description
The dataset consists of two CSV files: `takehome_users.csv` and `takehome_user_engagement.csv`. The user table contains data on 12,000 users, including name, ID, email, creation source, creation time, and more. The usage summary table records user logins on different days.

## Approach
1. Data cleaning and preparation:
   - Handled missing values and converted timestamps.
2. Feature engineering:
   - Calculated login days within a seven-day period.
   - Created additional features for user activity and engagement.
3. Exploratory data analysis:
   - Analyzed target variable distribution and feature relationships.
   - Generated summary tables and visualizations.
4. Model building and evaluation:
   - Used machine learning algorithms to predict user adoption.
   - Evaluated models using appropriate metrics.

## Findings
Factors predicting user adoption:
1.Organization_id
2.The hour and week day that account was created

Further research and data collection are recommended to validate and expand upon these findings.

