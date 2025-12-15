**Project Name : Diwali Sales Analysis using PowerBI**


**overview**
The objective of this project is to analyze customer purchasing behavior during the Diwali festival and identify key factors such as marital status, gender, age group, occupation, state, and product category that influence sales.
This analysis helps businesses improve targeted marketing, inventory planning, and customer segmentation during festive seasons.

**Business Problem**

During festive seasons like Diwali, businesses struggle to:
Identify high-value customer segments
Understand which regions and categories generate maximum revenue
Track sales performance across demographics
This report solves these problems by presenting interactive and data-driven insights in a single dashboard.

**Dataset Overview**
Dataset Name: Diwali Sales Data
Total Records: 11,251 rows
Total Columns: 15
Data Type: Transactional sales data
Source: CSV file

**Key Columns Description**

User_ID – Unique customer identifier
Cust_name – Customer name
Gender – Male / Female
Age / Age Group – Customer age segmentation
Marital_Status – 0 = Unmarried, 1 = Married
State – Customer location
Zone – Regional zone (North, South, West, Central)
Occupation – Customer profession
Product_Category – Product type purchased
Orders – Number of orders placed
Amount – Total purchase value

**Data Cleaning & Preparation**
Removed blank and unnecessary columns (Status, Unnamed)
Checked and handled missing values
Ensured correct data types for Amount, Orders, Age
Created additional calculated columns for analysis where required

**Data Model**

Single fact table with optimized relationships
Implemented star-schema-friendly structure
Ensured fast report performance

**Key DAX Measures Used**
Total Sales = SUM('Sales'[Amount])

Total Orders = SUM('Sales'[Orders])

Average Order Value = DIVIDE([Total Sales], [Total Orders])


**Dashboard KPIs**

Total Sales Amount
Total Orders
Average Order Value (AOV)

**Key Visual Analysis**

Sales by Marital Status (Married vs Unmarried)
Sales by Gender
Sales by Age Group
Sales by State
Sales by Occupation
Sales by Product Category
Interactive slicers for deeper analysis

**Key Insights Derived**

Married customers contribute higher total sales during Diwali
Female customers show stronger purchasing behavior
Age group 26–35 generates maximum revenue
Top-performing states include Maharashtra, Uttar Pradesh, and Karnataka
Categories like Clothing, Food, and Auto dominate festive sales

**Business Impact**

This dashboard enables stakeholders to:
Run targeted festive marketing campaigns
Focus on high-revenue customer segments
Improve regional sales strategies
Make faster, data-driven business decisions


