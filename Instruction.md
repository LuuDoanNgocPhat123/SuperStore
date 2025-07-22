# Superstore Sales Analysis & Data Visualisation

#### Project Description
This project will train you how to use SQL to analyze a real-world database, how to extract the most useful information from the dataset, how to pre-process the data using Python for improved performance, how to use a structured query language to retrieve useful information from the database, and how to visualize the data using the PowerBI tool.

This project is divided into three modules: 
## Module 1: Data Pre-processing
In this Module you will be working on how to perform pre-processing of data and working on handling null values, deletion or transformation of irrelevant values, data type transformation, removing duplicates and data validations to get refined and cleaner data to perform further analysis. 

#### Steps to perform Data Pre-processing: 

Step 1: Removing duplicate rows ( there could be duplicate rows excluding Row_ID column ).

Step 2: Removing rows for which few values are missing.

Step 3: Remove irrelevant values from each column if any. Validation of all values for a column( order date and ship date value must be in correct date format ). For each entry in dataset ship date >= order date

Step 4: Export the cleaned dataset as a .csv file: prefer UTF-8 encoding.

Step 5: Convert the pre-processed dataset into an SQL file and import it to table named "superstore".
## Module 2 Data Analysis using SQL
In this module, you will be working on performing data analysis on the pre-processed data from the previous module and conducting Data Analysis using SQL. You will generate queries for given problem statements. 
#### Write an SQL query to solve the given problem statement. 

#1. What percentage of total orders were shipped on the same date?

#2. Name top 3 customers with highest total value of orders.

#3. Find the top 5 items with the highest average sales per day.

#4. Write a query to find the average order value for each customer, and rank the customers by their average order value.

#5. Give the name of customers who ordered highest and lowest orders from each city.

#6. What is the most demanded sub-category in the west region?

#7. Which order has the highest number of items? And which order has the highest cumulative value?

#8. Which order has the highest cumulative value?

#9. Which segment’s order is more likely to be shipped via first class?

#10. Which city is least contributing to total revenue?

#11. What is the average time for orders to get shipped after order is placed?

#12. Which segment places the highest number of orders from each state and which segment places the largest individual orders from each state?

#13. Find all the customers who individually ordered on 3 consecutive days where each day’s total order was more than 50 in value. **

#14. Find the maximum number of days for which total sales on each day kept rising.


## Module 3 : Data Visualization with Power BI

In this module, you will use Power BI to create interactive dashboards and insightful visualizations from the cleaned and analyzed dataset. This module focuses on helping you develop practical skills in presenting your data analysis results visually for business insights and decision-making.

### Objectives:
Load the cleaned dataset (or SQL-based queries) into Power BI.

Create multiple visuals to represent key metrics and trends.

Design an interactive dashboard for management-level insights.

### Steps to perform Data Visualization:
#### Step 1: Load the dataset into Power BI

Import the cleaned .csv file from Module 1, or connect Power BI directly to your SQL database using native connectors.

Ensure data types (especially Date and Number fields) are correctly interpreted.

#### Step 2: Create basic visualizations

Total Sales over Time (Line Chart)

Profit by Region and State (Map or Bar Chart)

Sales vs. Profit by Category and Sub-Category (Stacked Bar Chart or Treemap)

Quantity Sold by Product (Bar Chart)

#### Step 3: Advanced insights

Top N Customers by Sales and Profit (Card or Table visual)

Most/Least Profitable Cities

Delivery Delay Trends: Average Shipping Time per Region

Order Volume by Segment and Shipping Mode (Stacked Column Chart)

#### Step 4: Interactivity and Filters

Add Slicers for: Date Range, Region, Category, Segment

Add Filters: City, Customer Name, Product ID

#### Step 5: Design your dashboard

Organize visuals into logical sections: Overview, Customers, Products, Shipping

Add Titles, Tooltips, and Descriptions for user-friendliness

Use consistent color schemes and formatting

#### Step 6: Export and Share

Publish your report to the Power BI service (if applicable)

Export to PDF or share the .pbix file with stakeholders