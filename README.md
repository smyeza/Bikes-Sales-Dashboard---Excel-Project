# Bikes Sales Analysis.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning/Preparation](#data-cleaning/preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/findings](#results/findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)



### Project Overview.
This data analysis project aims to provide insights into the average income of customers that purchase bikes across the various regions that our stores are located in.

### Data Sources
Sales Data: The primary dataset used for this analysis is the "Bike Project Dataset.xlsx" file containing detailed information about each bike sale made by the company.

### Tools.
- Excel - Data Cleaning.
- Excel - Pivot Tables.
- Excel - Dashboard.

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:

1. Data Loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:

  - What is the average salary of customers that purchase bikes?
  - Which age group buys the most bikes?
  - What is the marital status of our customers?
  - Which occupation group buys the most bikes?

### Data Analysis

```sql
SELECT * FROM table1
WHERE cond = 2
```

### Results / Findings

The analysis results are summarized as follows:
1.	The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
2.	Product category A is the best-performing category in terms of sales.
3.	Customer segments with high lifetime value(LTV) should be targeted for marketing efforts.


### Recommendations

Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales seasons to maximize revenue.
- Focus on expanding and promoting products in Category A.
- Implement a customer segmentation strategy to target high -LTV customers effectively.

### Limitations

I had to remove all duplicate values from the bike sales data because they would have affected the accuracy of my conclusions from the analysis. 
There are still a few outliers even after the omissions but even then we can still see there is a positive correlation between both budget and number of votes with revenue.

### References

- Excel Tutorial project by Alex the Analyst.
    - [Alex The Analyst Excel Project.](https://www.youtube.com/watch?v=opJgMj1IUrc)













