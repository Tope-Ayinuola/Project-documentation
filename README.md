# Project-Documentation

## Project Title: Rental store and Customer Segmentation for a Subscription Service
---

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data Cleaning and Preparations](#data-cleaning-and-preparations)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

### Project Overview
---
The Data analysis project is amied to generate insight into sales and customer performance analysis for a rental store and subscription service over the past years by analysing the various parameters in the data gathered. This data will help to make reasonable decisions which enables the documentation around the data.

### Data Sources
---
The source od data here is sales data for a rental store  and customer segmentation data for a subscription service which was given.

### Tools Used
---
- Microsoft Excel for: [Download Here](https://www.microsoft.com)
  
  i   Data cleaning
  
  ii  Analysis and Visualization
  
- SQL - Structured Query Language for data Querying

- Microsoft Power BI for

  i  Data Cleaning
  
  ii  Analysis
  
  iii  Visualization

- Github for Portfolio Building

### Data Cleaning and Preparations
---
The following steps were oerformed for the data cleaning and preparation:

  1. Data loading and analysis

  2. Imputing missing variables

  3. Data cleaning and formatting such as removing duplicates and null columns

  4. wriring and executing Query

  5. Building and propagating visualization based on the data


### Exploratory Data Analysis
---

This involves analysis data to give anwers to:

   i  What is the total number of customer from each region?

   ii  What is the average sales per product?

   ii  What is the total revenue per product?

### Data Analysis
---

This is where we include some basic lines of codes and visualization used during the analysis;

```SQL

Select product,Sum ([Sales_Amount])
AS Sales_Amount
FROM [dbo].[LITA Capstone Dataset]
GROUP BY product
ORDER BY SUM([Sales_Amount]) DESC;
```

```SQL

SELECT product,
sum(Quantity*[UnitPrice])AS
Sales_Amount
FROM [dbo].[LITA Capstone Dataset]
GROUP BY product
```

### Data Visualization
---



![Screenshot (5)](https://github.com/user-attachments/assets/c3d428ff-c6ce-489f-8715-63695b9b991b)

![Screenshot (2)](https://github.com/user-attachments/assets/2dc6e360-611b-4dab-b007-fc09c70b71d4)

![Screenshot (3)](https://github.com/user-attachments/assets/d40d62db-152f-42f0-a4bd-fd9ad828c38b)

![Screenshot (4)](https://github.com/user-attachments/assets/b96333ba-92df-426c-8536-1eaa6ffad852)

