Sales Insights Report

Project Overview
This project aims to create a comprehensive sales dashboard, assembling data from various sources to provide insightful visualizations on a single page. The report will utilize resilient mechanisms for loading data, data transformations, and DAX calculations to present key sales metrics

Data Gathering and Loading

Data Modeling and Transformations

DAX Calculations

Visualizations and Report Assembly

Conclusion

Future Enhancements

Introduction
The goal of this project is to assemble sales reports with various visuals to best showcase the Sales Insights. The data sources include yearly sales files, categories, geography, products, sales representatives, and subcategories.

Data Gathering and Loading
Task 1.1: Created a resilient mechanism to load all files from the sales folder into a single Sales fact table.

Ensure missing files do not create errors.

Automatically load new yearly sales files upon refresh.

Data Modeling and Transformations
Task 2.1: Transformed the Sales fact table by splitting the "Location" field into Country and City, and ensure correct data types for Geo maps.

Updated the Date field for proper formatting.

Task 2.2: Created a unique key (GeoKey) in both Sales and Geography tables.

Task 2.3: Created a function to clean IDs in SalesRep and SubCategory tables by removing the “ID - ” part.

Task 2.4: Built the Data Model by connecting all tables and integrating the Calendar table.

DAX Calculations
Task 3.1: Calculate Total Revenue: Total Revenue = Units * Product’s Retail Price

Task 3.2: Calculate Total Cost: Total Cost = Units * Product’s Standard Cost

Task 3.3: Calculate Gross Profit: Gross Profit = Total Revenue - Total Cost

Task 3.4: Calculate Gross Profit MoM Growth Change% for decision-making.

Task 3.5: Calculate Average Sales per Day: AVG Sales per Day = Total Revenue / Number of Sales Days

Task 3.7: Performed Breakdown Analysis by Product (drop or increase).

Calculated QoQ Growth for the QBR Report.

Visualizations and Report Assembly
Created various visualizations (bar charts, line graphs, etc.) to represent key metrics.

Assembled the sales reports and visualizations

Ensured months are sorted from Jan-Dec if plotted on the x-axis.

Conclusion

The Report effectively presents key sales insights, helping stakeholders make informed decisions. The findings indicate opportunities for revenue growth, cost management, and targeted marketing.
