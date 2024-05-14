# Ecommerce-Sales-Dashboard-Using-Power-BI
Problem Statement:

A US Based Ecommerce Sales Company wants us to create a Sales Dashboard showing information of YTD Sales and generate insights for below scenarios-

•	Create a KPI Banner showing YTD Sales, YTD Profit, YTD Quantity sold, YTD Profit Margin

•	Find Year on Year growth for each KPI and show a YTD sparkline for each measure in the KPI to understand the monthly trend for each fact.

•	Find YTD Sales, PYTD Sales, YoY Sales growth for different customer category. Add a trend icon for each category.

•	Find YTD Sales performance by each State

•	Top 5 and Bottom 5 Products by Sales

•	YTD Sales by Region to know best and worst performing region all over country

•	YTD Sales by Shipping Type to get the best shipping type percentage

POWER BI FUCNTIONALITIES USED
•	Connect Power BI to MS SQL server and Flat Files

•	Data Modelling with three tables

•	Data cleaning in Power Query

•	Date Table in Power BI

•	Time Intelligence function (TOTALYTD, SAMEPERIODLASTYEAR, etc)

•	 Created Dynamic and Complex KPI's

•	Basic to Advanced Dax Queries

•	 Conditional Formatting's, Adding dynamic icons in Power BI

•	 Different DAX functions like Calculate, Sum, Sumx, Filter, values, selectedvalue, return, concatenate, divide, var, etc

•	 Creating different charts, maps and formatting then

•	Generating insights from charts

•	Export report

Software Used:

1) MS SQL Server
   
2) Power BI


Procedure
Created a database called Ecommerce_Database in MS SQL server. Added Two Tables ecommerce_data and us_state_lon_lat_codes.

Used the below Flat files to create database in SQL server.

1) ecommerce_data.csv file 

2) us_state_long_lat_codes.csv file

Imported the tables from SQL server to Power BI.

Created a relationship between customer_state and name


Calculate the required measures using DAX queries.

[E Commerce Sales KPI DAX queries.pdf](https://github.com/Kajol0810/Ecommerce-Sales-Dashboard-Using-Power-BI/files/15307821/E.Commerce.Sales.KPI.DAX.queries.pdf)   



<img width="670" alt="E-Commerce Sales Dashboard " src="https://github.com/Kajol0810/Ecommerce-Sales-Dashboard-Using-Power-BI/assets/59485729/177f6b6d-95de-4504-bf10-ef5fb0a1f2ef">


Working Dashboard

https://github.com/Kajol0810/Ecommerce-Sales-Dashboard-Using-Power-BI/assets/59485729/c6f27726-7dcd-4c71-87b5-a8ccbf5292a7


