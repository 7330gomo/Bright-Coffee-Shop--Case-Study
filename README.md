### Bright Coffee Shop Sales Analysis (BRIGHTLEARN)


 ## Overview
This project analyzes transactional sales data from Bright Coffee Shop to uncover insights that can help the newly appointed CEO grow the company’s revenue and improve product performance.
As a Junior Data Analyst, my objective is to transform raw transactional data into actionable business insights using SQL, data analytics, and visualization tools.


## Objective

The purpose of this analysis is to assist Bright Coffee Shop in understanding key performance drivers and sales dynamics by identifying:

1.The products that generate the highest revenue

2.The time of day when the store performs best

3.Sales trends across products and time intervals

4.Actionable recommendations to improve overall sales performance
   

## Tools & Technologies Used

**Planning:**
Miro

**Data Processing Platform:**

Snowflake

**Data Visualization:**

Microsoft Excel

**Presentation:**

Microsoft PowerPoint



## Project Tasks
**Task 1: Planning & Architecture (Miro)**
Designed a mind map in Miro to outline the data structure and workflow.

Identified key insights to be derived from the dataset, including:
Sales by product category and time interval
High- and low-performing products
Monthly revenue per store location
Defined key calculations such as:
total_amount = unit_price * transaction_qty

**Task 2: Data Processing (Snowflake)**
Loaded the Bright Coffee Shop Sales dataset into Snowflake for structured data transformation and analysis.
Executed SQL queries to clean, classify, and aggregate the data.

Created additional fields to support time-based and performance insights, including:
Month and Day Name extraction for temporal trend analysis
Day Classification to distinguish between weekdays and weekends
Time of Day Segmentation (Morning, Afternoon, Evening, Night) based on transaction time
Revenue Calculation using the formula transaction_qty * unit_price


  
**Task 3: Data Analysis & Visualization (Excel)**

Exported the transformed dataset from Snowflake into Microsoft Excel.

Created pivot tables and charts to visualize:
Monthly revenue per store location
Peak sales time intervals
Quantity sold per product category
Best-selling products


**Task 4: Presentation (PowerPoint)**
Compiled all key findings, charts, and insights into a PowerPoint presentation.
Included conclusions and actionable recommendations aimed at improving business performance.

## Deliverables

The GitHub repository includes the following project components:
Miro Diagram: Data flow and architecture plan
Processed Dataset (Excel): Pivot tables and visual charts
PowerPoint Presentation: CEO insights, conclusions, and recommendations
SQL Script/Text File: Transformation and analysis queries
