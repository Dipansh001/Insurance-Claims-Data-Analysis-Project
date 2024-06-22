# Insurance-Claims-Data-Analysis-Project
This project involves comprehensive data analysis on insurance claims using Python. Tasks include merging datasets for a 360-degree view, data auditing, datatype correction, missing value imputation, customer age categorization, and various statistical analyses. 
This project focuses on a comprehensive analysis of insurance claims data using Python to provide meaningful business insights. The key tasks and outcomes are outlined below:

Data Preparation
Data Import and Merge: Combined claims_data.csv and cust_data.csv to create a comprehensive dataset for analysis.
Data Audit: Performed datatype verification to ensure consistency with business requirements.
Data Cleaning: Converted the claim_amount column to numeric by removing the $ sign.
Data Transformation
Unreported Claims: Created an alert flag (1,0) for injury claims not reported to the police.
Customer Uniqueness: Ensured unique customer IDs by retaining the most recent claim and removing duplicates.
Missing Values: Imputed missing values using the mean for continuous variables and mode for categorical variables.
Age Calculation and Categorization: Calculated customer age and categorized into Children (<18), Youth (18-30), Adult (30-60), and Senior (>60).
Analytical Insights
Average Claim Amount: Calculated the average amount claimed by customers across different segments.
Total Claim Amount by Incident Cause: Summarized claim amounts for incidents occurring at least 20 days before October 1, 2018.
State-Specific Analysis: Counted adults from TX, DE, and AK claiming for driver-related issues.
Gender and Segment Analysis: Created a pie chart showing claim amounts as a percentage based on gender and segment.
Driver-Related Issues by Gender: Used a bar chart to compare claims for driver-related issues between genders.
Fraudulent Claims by Age Group: Visualized the age group with the highest fraudulent policy claims.
Monthly Claim Trend: Illustrated the monthly trend of total claimed amounts in chronological order.
Statistical Analysis
Average Claim Amount by Gender and Age: Visualized average claim amounts for gender and age categories using a facetted bar chart for fraudulent and non-fraudulent claims.
Hypothesis Testing
Claim Amount Similarity: Tested for similarity in claim amounts between males and females.
Age Category and Segment Relationship: Investigated the relationship between age categories and segments.
Claim Amount Trend: Compared the current year's claim amounts to the 2016-17 fiscal average of $10,000.
Age Group and Claim Amount Difference: Analyzed differences in claim amounts across age groups.
Policy Claims and Claimed Amount Relationship: Examined the relationship between the total number of policy claims and the claimed amount.
