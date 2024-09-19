

# Walmart Customer Purchase Analysis

## Project Description

This project involves analyzing customer purchase behavior data from Walmart during Black Friday sales. The primary objective is to understand the spending patterns of male and female customers and identify any significant differences in their purchasing behavior. By analyzing transactional data, the project aims to provide insights that can help Walmart make data-driven decisions to optimize marketing strategies and improve customer engagement.

## About Walmart

Walmart is an American multinational retail corporation that operates a chain of supercenters, discount departmental stores, and grocery stores across the United States. With over 100 million customers worldwide, Walmart is a major player in the retail industry.

## Business Problem

The management team at Walmart Inc. seeks to analyze customer purchase behavior, specifically focusing on the purchase amount in relation to the customer's gender and other factors. The goal is to understand if spending habits differ between male and female customers. For instance, do women spend more on Black Friday than men? The dataset assumes an equal split of 50 million male and 50 million female customers.

## Dataset

The dataset used in this analysis consists of transactional data from Walmart stores during Black Friday. The dataset includes the following features:

- **User_ID**: User ID
- **Product_ID**: Product ID
- **Gender**: Sex of the user
- **Age**: Age in bins
- **Occupation**: Occupation (masked)
- **City_Category**: Category of the city (A, B, C)
- **StayInCurrentCityYears**: Number of years staying in the current city
- **Marital_Status**: Marital status
- **ProductCategory**: Product category (masked)
- **Purchase**: Purchase amount

## Analysis Steps

1. **Data Import and Initial Analysis**:
   - Import the dataset and perform initial data analysis, including checking the structure and characteristics of the data.

2. **Null Values and Outliers Detection**:
   - Identify and handle null values and outliers using methods such as boxplots, the `describe` method, and checking for discrepancies between mean and median values.

3. **Data Exploration**:
   - Analyze spending patterns for male and female customers:
     - Track the amount spent per transaction for both genders, calculate the average spending, and draw conclusions.
     - Compare average spending between females and males.
     - Compute confidence intervals to estimate the range within which the population average lies using sample data.
     - Apply the Central Limit Theorem to understand how sample size affects the mean distribution of expenses.
     - Experiment with different confidence interval widths (90%, 95%, 99%) and report observations.

4. **Further Analysis**:
   - Perform similar analyses for marital status and age:
     - For age, categorize into bins such as 0-17, 18-25, 26-35, 36-50, and 51+ years.
     - Compare spending between married and unmarried customers and across different age groups.

5. **Recommendations**:
   - Provide actionable insights and recommendations for Walmart based on the analysis, such as potential areas for marketing strategy adjustments or targeted promotions.



## Impact of the Work

The analysis provided actionable insights into customer spending behaviors, revealing significant differences between male and female customers as well as variations based on marital status and age groups. Key impacts include:

- **Improved Targeted Marketing**: The findings allow Walmart to tailor marketing campaigns more effectively by understanding which demographics spend more and when.
- **Enhanced Customer Engagement**: By addressing the specific spending behaviors of different groups, Walmart can create more personalized shopping experiences.
- **Strategic Decision Making**: The insights support better decision-making in inventory management and promotional strategies based on consumer spending patterns.

Overall, this work helps Walmart leverage data to refine its strategies and enhance its customer experience during peak shopping periods.

## Colab Notebook

The full analysis is available on Google Colab. [View the Notebook](colab_link.md).

## PDF Report

A detailed analysis report is available in the following PDF file: [View Report](walmart_project.pdf).

## Jupyter Notebook

The Python code and analysis are available in the following Jupyter Notebook: [View Notebook](walmart.ipynb).




