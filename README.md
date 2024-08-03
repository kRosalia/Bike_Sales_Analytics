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
### Building a dashboard
1. Create a Pivot table.
   Here we will be looking at the average income of someone who bought or did not buy a bike
   - Breaking it out by gender
   - Created visualisation on average income per purchase


### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:
- What is the overall sales trend?
- Which products are top sellers?
- What are the peak sales periods?

### Results/Findings

The analysis results are summarized as follows:
1. The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
2. Product Category A is the best-performing category in terms of sales and revenue.
3. Customer segments with high lifetime value(LTV) should be targeted for marketing efforts.

### Recommendations
1. Optimize Holiday Season Promotions:
  - Since sales peak during the holiday season, invest in targeted marketing campaigns and promotions during this period to maximize revenue.
-   Consider offering special holiday deals, discounts, and bundles to attract more customers and boost sales further.
2. Focus on Product Category A:
- Allocate more resources to the production, marketing, and development of Product Category A since it is the best-performing category.
- Conduct market research to understand why this category performs well and identify opportunities to introduce new products or variations within this category.
3. Target High LTV Customer Segments:
- Develop personalized marketing strategies aimed at customer segments with high lifetime value (LTV).
- Use data analytics to identify the characteristics and behaviors of these high LTV customers and tailor marketing messages to meet their needs and preferences.
4. Enhance Customer Retention Strategies:
- Implement loyalty programs, exclusive offers, and personalized communication to retain high LTV customers and encourage repeat purchases.
- Gather feedback from these customers to continually improve products and services and enhance customer satisfaction.
5. Diversify Marketing Channels:
- Explore and utilize various marketing channels, such as social media, email marketing, and content marketing, to reach and engage high LTV customers.
- Use targeted advertising to ensure that marketing efforts are focused on the most profitable customer segments.
6 Monitor and Adjust Strategies:
- Continuously monitor sales data and customer behavior to identify trends and adjust marketing strategies accordingly.
