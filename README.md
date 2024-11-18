# Parker-products-sales-data-analysis-using-power-bi

## Project Overview
The Parker Product Sales Data Analysis project involves analyzing and visualizing sales, purchases, and organizational data to provide actionable insights for stakeholders. This project was implemented using MySQL Workbench for database management and Power BI for data visualization and reporting. The primary objective is to deliver an interactive and dynamic dashboard suite for comprehensive data exploration and decision-making.

## Table of Contents
Project Objectives
Dataset Details
Tools and Technologies Used
Tickets and Implementation Details
Key Features of the Dashboards
Challenges and Solutions
Future Enhancements

## Project Objectives
Create a robust database from the provided Excel datasets.
Build interactive dashboards using Power BI for detailed sales, purchase, and organizational reporting.
Enable dynamic filtering and drill-through capabilities to empower users with deep insights into sales trends, representative performance, and item categories.
Provide actionable data through intuitive visualizations and advanced filtering mechanisms.

## Dataset Details
The dataset includes multiple Excel sheets containing details about:
product category table
Sales detail table
Purchase Orders table
Store Items table
warehouse table
Organizational Data table 
Sales Representatives details table etc

Each sheet was imported into MySQL Workbench, cleaned, and used to create tables for Power BI reporting.

## Tools and Technologies Used
MySQL Workbench: Database creation and management.
Power BI: Dashboard creation, data modeling, and visualization.
Microsoft Excel: Initial data preparation and inspection.
DAX (Data Analysis Expressions): Advanced calculations and measures in Power BI.

## Tickets and Implementation Details
Ticket 1: Database Setup
Installed and set up MySQL Workbench.
Created the ParkerProd database and imported data from the provided Excel sheets into tables.
Ensured accurate data types and relational integrity.
Ticket 2: Sales Details Dashboard
Created a dynamic filter to view sales from the last 3, 6, 9, or 12 months based on the invoice date.
Calculated the extended sell price with tax and discounts.
Added a sales status field for better filtering.
Ticket 3: Sales Details - Sales Rep Dashboard
Built a dashboard to show sales item details based on sales representative status.
Included representative numbers and names in a card visualization.
Added a bar diagram filtering dynamically by shipment month, quarter, and week.
Ticket 4: Sales Item - On Customer Dashboard
Displayed sales amount, count, and the ability to filter by custom day ranges (e.g., last 12 days).
Focused on active customers only.
Included customer details and discounts provided.
Ticket 5: Item Sales Trend Report
Showed sales trends for items across past years.
Incorporated a production line-based filter for GTI and PM IAF.
Ticket 6: Sales Report Summary
Summarized item sales totals with drill-through functionality to transaction-level details.
Allowed filtering based on selected date columns (e.g., Booked Date, Need By Date).
Displayed sales by payment type, including Card Pay, Online, Cheque, Physical Currency, and Bitcoin.
Ticket 7: Purchase Order Report
Displayed purchase item details, quantities ordered and received.
Highlighted whether ordered quantities were met (green) or not met (red).
Showed the received-to-ordered gap in a card visual.
Included filters for warehouse name, organization name, and buyer name.
Ticket 8: Purchase Quality Report
Evaluated quality ratings of purchases by item name and warehouse.
Sorted visuals from highest to lowest ratings.
Ticket 9: Store Items Report
Created a bar diagram of unit item cost against creation month.
Included slicer filters for item categories.
Focused on active indirect records only.
Ticket 10: Organization Details Report
Provided details of organizations with created date and status filters.
Ticket 11: Category-Based Report
Displayed categories (e.g., GTI, PM, IF) in separate visuals.
Combined cat1 to cat3 as a single record separated by dots.
Sorted reports by category name in descending order.
Ticket 12: Sales Rep Dashboard
Highlighted the most recently added 30 sales representatives.
Separated details for part-time and full-time representatives.
Created separate pages for onsite (rep_type = 1) and offsite (rep_type = 0) representatives.
Key Features of the Dashboards

Dynamic Filtering: Filters for date ranges, customer activity, and specific columns.
Interactive Visuals: Drill-through capabilities and dynamic slicers for enhanced exploration.
Conditional Formatting: Color-coded statuses for clear and immediate insights.
Separation of Views: Detailed and high-level summaries on separate pages.
Challenges and Solutions

Data Cleaning:
Issue: Inconsistent data formats in the Excel sheets.
Solution: Cleaned and transformed data during MySQL import using proper data types and validation.
Dynamic Filters in Power BI:

Issue: Implementing user-defined date ranges.
Solution: Used DAX measures and slicers to enable flexible date filtering.
Performance Optimization:

Issue: Handling large datasets in Power BI.
Solution: Used aggregations and optimized data models to improve performance.

## Future Enhancements
Incorporate predictive analytics for sales forecasting.
Automate data refresh for real-time updates.
Add advanced customer segmentation analysis.
Integrate mobile-friendly views for dashboards.

## Folder Structure
MySQL Workbench Scripts: Database creation and data import scripts.
Power BI Files: PBIX files for each dashboard.
Documentation: User guides and README files.
## Conclusion
The Parker Product Sales Data Analysis project successfully provided a robust framework for sales, purchase, and organizational insights using MySQL and Power BI. 
The dashboards created are intuitive, flexible, and provide actionable insights to stakeholders, paving the way for improved decision-making and strategic planning.
