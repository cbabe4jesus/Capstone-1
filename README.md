# Capstone-1

### Project Title:  Sales Performance Analysis for a Retail Store


### Project Overview
This project is aimed at analyzing the sales performance of a retail store,
to explore its sales data and uncover key insights such as top-selling products,
regional performance, and monthly sales trends. 
To bring about a comprehensive report to enable better running of the store. 

### Data Sources
The primary source of data used here is SalesData.csv this is a closed source data 

### Tools Used
- Microsoft Excel for data cleaning, analysis and visualization.
- SQL - Structured Query Language for quering of data.
- PowerBI for data anaiysis and visitualization.
- GitHub for portfolio building.


### Data Cleaning and preparations
In the initial phase of the data cleaning and preparations, we performed the following actions;
1. Uploading of data and inspection
2. Handling missing variables
3. Data cleaning and formatting

### Exploratory Data Anaysis
This involved data exploration to give insights and answers to some questions about the data such as;
- Total sales for each product category.
- The highest-selling product by total sales value.
- identify products with no sales.
- The total revenue per product e.t.c.

### Data Analysis
This is where we include some basic lines of codes or queries or even some of the DAX expression used during the analysis;

~~~SQL
select top 5 Customer_Id,
	  sum(Sales) as totalpurchaseamount
	  FROM [CAPSTONE_DB].[dbo].[capstone 1]
	  GROUP BY Customer_Id
	  order by sum (Sales)
	  DESC
~~~

### Data Visualisation
