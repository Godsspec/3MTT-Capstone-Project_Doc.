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
  2. Total Refund Amount; This was analyzed to know to total amount of refunds that was made via the returns.
Others are monthly return requests, refund amount analysis, restocking fee analysis, refund method by refund requests and average processing time.

  <img width="294" height="265" alt="image" src="https://github.com/user-attachments/assets/cf45bf42-7ead-4ed0-b4eb-d77cb88b8995" />

<img width="281" height="271" alt="image" src="https://github.com/user-attachments/assets/3ef4c917-67eb-485c-a7ff-e4fb8b6eaafa" />


  ## Power BI Analysis
  ---------------------
  After the initial analysis and preparation in Excel, the dataset was imported into Power BI for data modeling, DAX calculations and interactive visualization.
 
