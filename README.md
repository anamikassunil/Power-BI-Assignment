Power BI Data Analytics Assignment

Project Overview

This project focuses on data preparation, data transformation, grouping, aggregation, and data modeling using Microsoft Power BI.

The objective of this assignment is to clean and organize the given datasets, perform data transformations using Power Query Editor, calculate aggregated values, and establish relationships between tables to prepare the data for analysis.

Tools & Technologies Used

- Microsoft Power BI Desktop
- Power Query Editor
- Microsoft Excel

Dataset Description

This assignment includes the following five tables:

1. List of Orders – Contains customer details, order dates, locations, and Order IDs.
2. Order Details – Contains order information, categories, sub-categories, amounts, profits, profit margins, and quantities.
3. Sales Target – Contains sales targets based on categories and monthly order dates.
4. Orders Data – Contains additional order-related information.
5. Grouped Tables – Created using Power Query for aggregation and analysis.

Tasks Performed

1. Data Preparation and Transformation

- Imported datasets into Power BI.
- Used Power Query Editor to prepare and transform the data.
- Changed data types where required.
- Renamed columns and performed necessary data transformations.
- Added custom and conditional columns.

2. Grouping and Aggregating Data

A. Order Details Table

Duplicated the Order Details table and performed the following operations:

- Calculated the count of each Order ID.
- Calculated average profit by Category.
- Calculated total amount by Sub-Category.

B. Sales Target Table

Duplicated the Sales Target table and performed the following operation:

- Grouped data by Month of Order Date.
- Calculated the total target amount for each month.

3. Data Modeling and Relationships

Created relationships between tables using the following columns:

Relationship 1:

- From Table: Order Details
- To Table: List of Orders
- Common Column: Order ID
- Relationship: Many-to-One
- Status: Active

Relationship 2:

- From Table: Order Details
- To Table: Sales Target
- Common Column: Category
- Relationship: Many-to-Many
- Status: Active

Used the Manage Relationships option in Power BI to establish and verify the relationships.

Key Learning Outcomes

Through this assignment, I gained practical experience in:

- Data preparation and cleaning.
- Power Query Editor.
- Data transformation techniques.
- Grouping and aggregation.
- Count, Average, and Sum operations.
- Creating custom and conditional columns.
- Data modeling and table relationships.
- Using GitHub to document and maintain project work.

Conclusion

This Power BI assignment helped me understand the fundamentals of data analytics and data modeling. It provided hands-on experience in transforming raw datasets into structured information and preparing data for further analysis and visualization.

---

Project: Power BI Data Analytics Assignment
Tool: Microsoft Power BI Desktop
Repository: Power-BI-Assignment
