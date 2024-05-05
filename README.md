# Bike_Sales_Analytics

### Project Overview

This data analysis project aims to provide insight into the sales performance of an ecommerce company over the past year. By analyzing various aspects of the bike sales data, we seek to identify trends make data driven reccommendations and gain a deeper understanding of the company's performance. 

### Data Sources
Sales Data: The primary dataset used for this analysis is the "https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx" file, containing detailed information about each sale made by the company.

### Tools

Excel - used for Data Cleaning. [Download here](https://microsoft.com)
  
### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Check for and remove any duplicates in the data
2. Using Find and replace to clearly spell out the customers who are male and female and the marital status, finding and replacing  by columns
3. Make sure the income is in currency and remove the two decimal points to none
4. Sort age by age range through Nested If Ranges
   ```Conditional Formatting
   =IF(L2>54, "Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent", "Invalid")))
   ```

### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:
- What is the overall sales trend?
- Which products are top sellers?
- What are the peak sales periods?

### Data Analysis

Include some interesting code you worked with

```sql
SELECT * FROM table1
WHERE cond = 2
```

### Results/Findings

The analysis results are summarized as follows:
1. The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
2. Product Category A is the best-performing category in terms of sales and revenue.
3. Customer segments with high lifetime value(LTV) should be targeted for marketing efforts.

### Recommendations
