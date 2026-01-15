# Kevin-Cookie-Company-Financial-Analysis-Power-BI-

Using the dataset **"Kevin Cookie Company Financials (1)"**, this repository contains an interactive Power BI dashboard built to analyze the company’s financial performance and cookie sales trends.

## Overview
The dashboard lets you explore revenue and sales trends across cookie types and time. It was built in Power BI following a typical ETL and visualization workflow: load and clean the data with Power Query, model the data, create measures, and build interactive visuals.

## Actions performed
1. Data preparation
   - Loaded the dataset (XLSX) into Power Query.
   - Performed data cleaning and transformations (e.g., corrected data types, handled missing values, normalized cookie type names, parsed dates).
   - Created or prepared date and aggregation fields used for time series analysis.

2. Data modeling & measures
   - There was no need to build relationships in model view.
   - created measures such as Total Revenue (SUM of revenue) etc.

4. Visualizations created
   - Card: Total revenue
   - Slicer: Cookie type (interactive filter)
   - Clustered bar chart: Revenue by cookie type
   - Line chart: Monthly revenue by cookie type
   - Matrix: Years as rows, cookie types as column headers (summaries by year and type)

## Outcomes
- Based on the dashboard, the total revenue for the Kevin Cookie Company was $4.69M*.  
- Chocolate chip cookies generated the highest revenue overall.  
- Fortune cookies were the weakest-performing cookie type in terms of revenue.  
- The month with the lowest total sales overall was September 2018. In that month, fortune cookies contributed the least revenue of any cookie type — note that this does not mean September 2018 was fortune cookies' personal lowest month across the whole timeline; it only indicates they were the smallest contributor for that month.

\*I presented monetary values in US dollars ($).

## How to use
- Open the Power BI (.pbix) file in Power BI Desktop.
- Use the cookie type slicer and date controls to filter and explore revenue and trends.
- Hover over visuals for tooltips and click items to cross-filter other visuals.

## Screenshot
<img width="1177" height="670" alt="Dashboard Homework Power BI" src="https://github.com/user-attachments/assets/9c18106a-9b71-45ba-95ae-851b6357ffb0" />
- Source dataset: Kevin Cookie Company Financials - included in this repo.
