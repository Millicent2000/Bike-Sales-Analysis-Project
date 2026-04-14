# Bike-Sales-Analysis-Project

## Project Overview

This project analyzes bike sales data to understand customer purchasing behavior and identify key factors influencing bike purchases. The dashboard provides insights into customer demographics, income levels, and commuting patterns to support data-driven decision-making.

### Description of Data Source

The dataset contains customer information related to bike purchases, including:
- Demographics (age, gender, marital status, education)
- Financial data (income)
- Geographic data (region)
- Behavioral data (commute distance, purchase decision)

  ### Tool Used
  
- Microsoft Excel
  - Data Cleaning (Find & Replace, removing duplicates)
  - Data Analysis (Pivot Tables)
  - Data Visualization (Pivot Chart)
  - Functions (e.g., IF formula)

   ### Data Cleaning and Preparation

To ensure data quality and consistency, the following steps were performed:

- Removed duplicate records to avoid inaccurate analysis
- Standardized categorical data:
  - Converted abbreviations (e.g., “M”, “S”) to full text (Married, Single)
  - Converted gender abbreviations to full names
- Created a new Age Bracket column using an IF formula:
  - Adolescent
  - Middle Age
  - Old
This improves readability and grouping in charts
- Standardized text values:
  - Replaced “10+ miles” with “10 plus miles” for better compatibility with Pivot Tables
 
### Exploratory Data Analysis (EDA)

During EDA, the following were explored:

- Distribution of customers by age group, gender, and region
- Relationship between income and bike purchases
- Commute distance patterns among customers
- Purchase trends across demographic groups

Pivot Tables were used to summarize and explore patterns before visualization.

### Data Analysis (Charts Explanation)

#### 1. Average Income Per Purchase (Bar Chart)

##### Why this chart?
A bar chart is ideal for comparing values across categories.

##### What it shows:

- Compares average income between customers who purchased bikes and those who did not
- Also segmented by gender

##### Insight purpose:
To determine whether higher income influences bike purchases and identify differences between male and female customers.

#### 2. Customer Commute (Line Chart)

##### Why this chart?
A line chart is useful for showing trends across ordered categories (age groups).

##### What it shows:

- Bike purchases across different age brackets (Adolescent, Middle Age, Old)
- Comparison between customers who purchased and those who did not

##### Insight purpose:
To identify which age group is most likely to purchase bikes.

#### 3. Customer Distance (Line Chart)

##### Why this chart?
Used to compare how commute distance affects purchasing decisions.

##### What it shows:

- Distribution of bike purchases across different commute distances

##### Insight purpose:
To understand whether people who travel longer distances are more likely to buy bikes.

### Findings
- Middle-aged customers are the most likely to purchase bikes
- Customers with higher income show a higher tendency to purchase bikes
- Commute distance has an impact on purchasing decisions
- Gender differences exist in income and purchasing patterns

### Recommendations
- Target middle-aged customers in marketing campaigns
- Focus on higher-income segments for premium bike sales
- Promote bikes as a commuting solution for short-to-medium distances
- Create gender-specific marketing strategies where necessary

### Limitations
- Dataset is limited in size and may not represent real-world population
- Missing external factors (e.g., weather, lifestyle, pricing)
- Income alone may not fully explain purchasing behavior

### Reference

This project was inspired by the tutorial below:

[https://youtu.be/opJgMj1IUrc?si=b0VgAwfyI9OQmmso]

While the tutorial provided the foundation, I independently handled data cleaning, analysis, and dashboard creation.

