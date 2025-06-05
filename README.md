# Tableau-Dashboard-Project

Tableau Dashboard Project: Regional Sales Comparison

Project Overview
In this project, I built an interactive Tableau dashboard to compare sales performance between two regions using the Sample Superstore dataset provided by Fortray Global. My goal was to enable users to select any two regions and view key performance indicators (KPIs) side by side, making it easier to analyse sales performance and identify areas for improvement.

Project Objectives
•	To compare sales performance between two user-selected regions.
•	To create a clean, interactive dashboard that allows flexible data exploration.
•	To support decision-making by presenting key sales insights clearly and effectively.

Dataset Summary
•	Source: Sample Superstore (public dataset)
•	Contents: Sales records with fields such as Order ID, Customer Name, Product Category, Region, Sales, Profit, Quantity, etc.
•	Purpose: Used to simulate a real-world business case for sales comparison between regions.

How I Built It

1. Data Preparation
I imported the Sample Superstore dataset into Tableau and organised the data by:
•	Creating folders for better structure (e.g., grouping Customer Name and Order ID).
•	Creating a hierarchy called Location that includes Country, State, and City to support geographic analysis.

2. Parameters and Calculated Fields
To allow dynamic region comparison:
•	I created two parameters: Primary Region and Secondary Region, containing all available regions.
•	I built calculated fields to filter data based on selected regions.
•	I also created calculated metrics for:
o	First Order Date
o	Total Sales
o	Average Sales per Order
o	Number of Customers
o	Number of Orders
o	Number of Products Sold

3. Dashboard Design
I designed the dashboard with a side-by-side comparison layout:
•	The left panel shows KPIs for the Primary Region and the right panel for the Secondary Region.
•	Users can use dropdown menus to change regions and instantly see updated insights.
•	I used KPI cards and bar charts to visualise the data clearly and effectively.

Key Features
•	Interactive Parameters: Users can compare any two regions.
•	Clear KPIs: Each region displays the same set of metrics to make comparisons easier.
•	User-Friendly Design: The dashboard is structured to be intuitive and easy to interpret.

Insights and Value
With this dashboard, I can:
•	Quickly spot differences in sales volume and performance between regions.
•	Identify which region has more customers or a higher average sales per order.
•	Understand the timeline of each region’s first recorded sale.

Conclusion
This project helped me strengthen my Tableau skills, especially in parameter creation, calculated fields, and dashboard interactivity. I believe this dashboard could be a useful tool for sales managers or business analysts looking to monitor and compare regional sales performance.

View My Live Dashboard:
Regional Sales Comparison – Tableau Public


Thank you!
https://public.tableau.com/app/profile/roman.shrestha5221/viz/Tableau_Project_1_17491562330570/Dashboard1?publish=yes
