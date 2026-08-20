<img width="767" height="432" alt="The 3mtt Capstone Dashboard" src="https://github.com/user-attachments/assets/758b76ed-f9a0-4a01-a1f3-d23eacfdbb25" />

# 3MTT CAPSTONE PROJECT
This is the documentation of the whole process carried out during my capstone project as a Data Analyst Fellow in 3MTT Nextgen Cohort
## Project Title: Nigerian E-commerce Returns Analysis

## Project Overview
---------------------
 
This project analyzes 150,000 e-commerce return records to identify patterns in return requests, refund amounts, return reasons, refund methods, processing time, return status and product categories. 
Microsoft Excel was used for data preparation, validation and exploratory analysis, while Microsoft Power BI was used to create an interactive dashboard and communicate key business insights.
The main aim of this analysis is to uncover returns and refund patterns in a Nigerian E-commerce store and the dataset documentation is not to be used for empirical or policy conclusions. 

## Data Source
---------------------

Hugging face - A synthetic dataset was obtained from Hugging face, generated to resemble Nigerian retail and e-commerce activity.


## Business Problem
---------------------
Product returns and refunds can create significant financial and operational challenges for e-commerce businesses. Understanding why customers return products, which product categories experience the highest return volumes, how refunds are processed, and the financial impact of returns can help businesses improve their operations and customer experience.

This project investigates return and refund patterns to identify ares where an e-commerce business can improve return management and reduce associated costs.

## Objectives
---------------------
- Analyze the volume of return requests.
- Identify the most common return reasons.
- Examine monthly return patterns.
- Analyze return requests by status.
- Identify the most frequently returned product categories
- Analyze refund methods.
- Examine refund amounts by product category
- Evaluste average refund processing time.
- Calculate the financial impact of refunds and restocking fees.
- Provide data-driven business recommendations.


## Data Analysis Tools Used
----------------------
- Microsoft Excel: Ms Excel 2010 was used for data cleaning, preparation, pivot tables and exploratory analysis
- Power BI: This was used for data modeling, DAX calculations, interactive visualization and dashboard development
- Github; for portfolio documentation and project sharing

## Excel Analysis
---------------------
### Data Cleaning and Preparation
The dataset was first prepared in Microsoft Excel before being imported into Power BI.
The following data preparation steps were performed:
- Reviewed the dataset for missing and blank values.
- Checked for inconsistencies in categorical fields.
- Reviewed the data types of numerical, date and text fields.
- Formatted monetary fields in Nigerian Naira.
- Created and validated the Net Refund calculation.
- Created a Month field from the return date for monthly analysis.
- Prepared Product Category information for product-level analysis.
- Reviewed return status categories, including approved, pending and rejected.

### Exploratory Data Analysis
  PivotTables and charts were used to explore return patterns by return reason and month. Additional calculations were performed to support the financial analysis, including refund amounts, restocking fees and net refund values.

  Excel analyses included: 
  1. Return requests by return reason; The analysis compared the number of return requests associated with different reasons such as, damaged product, defective product, duplicate order, late delivery, not as described, poor quality, wrong item delivered and wrong size.
  2. Total Refund Amount; This was analyzed to know the total amount of refunds that was made via the returns.
Others are monthly return requests, refund amount analysis, restocking fee analysis, refund method by refund requests and average processing time.

  <img width="294" height="265" alt="image" src="https://github.com/user-attachments/assets/cf45bf42-7ead-4ed0-b4eb-d77cb88b8995" />

<img width="281" height="271" alt="image" src="https://github.com/user-attachments/assets/3ef4c917-67eb-485c-a7ff-e4fb8b6eaafa" />


  ## Power BI Analysis
  ---------------------
  After the initial analysis and preparation in Excel, the dataset was imported into Power BI for data modeling, DAX calculations and interactive visualization.
  Dax measures were created to calculate key performance indicators and support the dashboard analysis. Some of the key measures included:
  1. Total Returns = COUNTROWS('Returns')
  2. Total Refund Amount =SUM('Returns'[Refund Amount])
  3. Total Restocking Fee = SUM('Returns'[Restocking Fee])
  4. Net Refund Cost = [Total Refund Amount] - [Total Restocking Fee]
### Dashboard Development
An interactive Power BI dashboard was developed to provide a consolidated view of e-commerce returns and refund activity. 
The dashboard contains:
1. Five key KPI cards; Total Returns, Total Refund Amount, Average processing time, Total Restocking fee and Net refund cost.
2. Visualizations for; monthly return trends, return requests by status, returns by refund method, refund amount by product category, average processing time by refund method and top 5 most returned product categories.
3. Interactive slicers to allow users filter the analysis by; return date, return reason, product category, return status and refund method.

<img width="767" height="432" alt="The 3mtt Capstone Dashboard" src="https://github.com/user-attachments/assets/62111556-4a13-464f-8fc9-0d36178a2ba0" />


 ## Key Findings
 ---------------------
 1. The dataset contains 150,000 return records, providing a substantial volume of return activity for analysis.
 2. The total refund amount is approximately ₦15.38 billion, demonstrating the significant financial value associated with returned products.
 3. The total restocking fee is approximately ₦75 million, while the calculated net refund cost is approximately ₦15.30 billion.
 4. The average refund processing time is approximately 7.51 days.
 5. Original payment is the most frequently used refund method, followed by store credit and bank transfer
 6. Beauty & Personal Care appears among the highest returned product categories in the Top 5 analysis.
 7. Monthly return volume varies throughout the year, with noticeable decline toward October.
    
 ## Business Recommendations
 ---------------------
 Based on the analysis, the following recommendations are proposed:
 1. Investigating high-return product category; Product categories with consistently high return volume should be investigated to determine whether the issue is related to product quality, customer expectations, sizing, descriptions or delivery.
 2. Address major return reasons; The business should monitor common return reasons and prioritize corrective actions for recurring issues such as damaged, defective, incorrectly delivered or poorly described products.
 3. Improve refund processing; With an average processing time of approximately 7.51 days, the business could investigate opportunities to reduce processing delays and improve customer refund experience.
 4. Monitor refund costs; The approximately ₦15.30 billion net refund cost indicates that returns represent a significant financial consideration. Management should monitor high-value refunds and identify categories or products responsible for disproportionate refund costs.
 5. Improve product information; With significant returns based on incorrect expectations, wrong size, or "not as described", the business should improve product descriptions, images, specifications and sizing information.
 6. Monitor high-return products; Products with unusually high return volumes should be reviewed individually to identify potential quality or fulfilment problems.

## Project Outcome
---------------------
The project transformed raw e-commerce return data into a structured analytical solution using Microsoft Excel and Power BI.
Excel was used for data preparation, validation, Pivot Table analysis, and exploratory analysis, while Power BI was used for data modeling, DAX calculations, interactive visualization, and dashboard development. 

The final dashboard provides stakeholders with an interactive way to monitor return volumes, refund costs, processing efficiency, return status, refund methods, and product-category performance.
 
