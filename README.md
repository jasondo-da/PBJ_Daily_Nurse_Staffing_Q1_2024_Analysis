# Medicaid and Medicare Staffing Analysis

![image](https://github.com/user-attachments/assets/13de14d7-19ad-44b2-8c67-34b691aac12d)

## Table of Contents

- [Project Introduction](#project-introduction)
    - [Canadian Data Science Jobs Analysis Jupyter Notebook](#medicaid-and-medicare-staffing-analysis-jupyter-notebook)
    - [Canadian Data Science Jobs Analysis Datasets](#medicaid-and-medicare-staffing-analysis-datasets)
- [Analysis Outline](#analysis-outline)
- [Conclusion](#conclusion)

## Project Introduction

The Clipboard Health sales leadership team has asked for recommendations on possible business decisions based on the Q1 2024 Payroll-Based Journal (PBJ) Daily Nurse Staffing dataset. In this analysis, I will analyze the Q1 2024 Payroll-Based Journal (PBJ) Daily Nurse Staffing dataset along with the FY 2024 SNF VBP Facility-Level dataset and State US Averages dataset to provide possible areas for staffing growth.

### Medicaid and Medicare Staffing Analysis Jupyter Notebook

All codes of Medicaid and Medicare Staffing Analysis in Jupyter Notebook

Link: [Medicaid and Medicare Staffing Analysis](https://github.com/jasondo-da/PBJ_Daily_Nurse_Staffing_Q1_2024_Analysis/blob/main/PBJ_Daily_Nurse_Staffing_Q1_2024_Analysis.ipynb)

### Medicaid and Medicare Staffing Analysis Datasets

This dataset provides a unique glimpse into medicaid and medicare staffing trends in Q1 2024.

Link: [Payroll Based Journal Daily Nurse Staffing](https://data.cms.gov/quality-of-care/payroll-based-journal-daily-nurse-staffing/data)

Link: [FY 2024 SNF VBP Facility-Level Dataset](https://data.cms.gov/provider-data/dataset/284v-j9fz)

Link: [State US Averages](https://data.cms.gov/provider-data/dataset/xcdc-v8bm)


## Analysis Outline

Within this analysis, in the first half, I will uncover new insights and unusual anomalies within the dataset to see if there are any growth opportunities or new demographics to target. The key questions we are looking for are:

• What are the state performance scores based on the FY 2024 SNF VBP Facility-Level dataset?

• Does the medical staff incentive payment multiplier affect their performance scores at the state level?

• Which states should be targeted for specific medical staff jobs?

• To which hospital positions should we allocate more medical staff?

• Can we increase the number of staff contractors?

The second half will consist of the SQL test questions:

• Write a query to return the customer_name, product_name, and total_amount for each sale in the last 30 days.

• Write a query to find the total revenue generated by each product category in the last year. The output should include the product category and the total revenue for that category.

• Write a query to return all customers who made purchases in 2023 and are located in the "West" region.

• Write a query to display the total number of sales, total quantity sold, and total revenue for each customer. The result should include the customer_name, total sales, total quantity, and total revenue.

• Write a query to find the top 3 customers (by total revenue) in the year 2023.

• Write a query to rank products by their total sales quantity in 2023. The result should include the product_name, total quantity sold, and rank.

• Write a query that categorizes customers into "New" (if they signed up in the last 6 months) or "Existing" based on their sign_up_date. Include the customer_name, region, and category in the result.

• Write a query to return the month and year along with the total sales for each month for the last 12 months.

• Write a query to return the product categories that generated more than $50,000 in revenue during the last 6 months.

• Write a query to check for any sales where the total_amount doesn’t match the expected value (i.e., quantity * price).


## Conclusion

### Key Findings

• States with an incentive payment multiplier greater than or equal to 1 will most likely have higher achievement, improvement, and performance scores and thus will be less likely to need additional staffing.

• States with an incentive payment multiplier of less than 1 will be more likely to need more staffing since they are more likely to be overworked, burnt out, or need more work assistance.

• When looking at the aggregate of hours worked by medical role once some states reach a certain threshold the achievement, improvement, and performance scores start to drop dramatically. This leads to an opportunity for more medical staff in those states with high hours worked and lower achievement, improvement, and performance scores.

• Certain hospital roles requiring more than 12 hours can use more staffing within those positions. Most workers can only provide about 5 hours of quality work per day with depreciating quality every hour after. Staffing more help in these positions will greatly increase productivity, work quality, and staff morale.

• Many hospitals experience high turnover rates due to the long hours and high workload. This is an opportunity for Clipboard Health to push more nurses and other medical professionals to do more part-time hours at hospitals. Hospitals will receive higher productivity, quality work, more positive workplace morale, save on full-time benefits, and medical staff members will get the work-life balance they need to stay in the industry long-term.
