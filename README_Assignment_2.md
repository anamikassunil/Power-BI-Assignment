Power BI Assignment 2 – DAX and Data Visualization

Project Overview

This project is the second Power BI assignment completed as part of my Data Analytics course. The assignment focuses on data visualization, calculated columns, and creating DAX measures using Microsoft Power BI.

The objective is to analyze different datasets, create meaningful visualizations, perform calculations, and explore data using DAX.

---

Datasets Used

The following datasets were used in this assignment:

- Amazingcart.xlsx
- Customer_Data.xlsx
- Employee_Layoffs.csv
- FlightData.csv

The datasets were imported into Power BI for analysis and visualization.

---

Tasks Completed

1. Countries with the Highest Order Placements

Dataset: Amazingcart.xlsx
Table Used: ListOfOrders
Visualization: Clustered Column Chart

A clustered column chart was created to analyze the number of orders placed in different countries.

- X-axis: Country
- Y-axis: Count of Order ID
- Chart Title: Countries with the Highest Order Placements

This visualization helps compare order placements across countries and identify countries with the highest number of orders.

---

2. Orders Received per Date

Dataset: Customer_Data.xlsx
Visualization: Line Chart

A line chart was created to show the count of orders received over different dates.

- X-axis: Date
- Y-axis: Count of Order ID
- Chart Title: Count of Orders Received per Date

This visualization helps understand the order trend over time.

---

3. Employee Layoffs by Location

Dataset: Employee_Layoffs.csv
Visualization: Pie Chart

A pie chart was created to analyze employee layoffs by location.

- Legend: Location
- Values: Sum of Total_Laid_Off
- Chart Title: Locations with the Highest Number of Layoffs

This visualization helps compare the distribution of layoffs across different locations.

---

4. Calculated Column

A new calculated column was created in the Customer Data table to replicate the existing Total Price column.

Column Name: Calculated Total Price

DAX Formula:

Calculated Total Price =
'Customer Data'[Quantity] *
VALUE(
    SUBSTITUTE(
        'Customer Data'[Price Per Unit],
        "$",
        ""
    )
)

The formula multiplies the Quantity by the Price Per Unit after removing the dollar symbol and converting the price into a numeric value.

The calculated values were compared with the existing Total Price column to verify the results.

---

5. DAX Measures

The following DAX measures were created:

Total Sales

Total Sales =
SUM('Customer Data'[Total Price])

Calculates the total sales amount.

Total Rows

Total Rows =
COUNTROWS('Customer Data')

Calculates the total number of rows in the Customer Data table.

Valid Records

Valid Records =
COUNT('Customer Data'[Order ID])

Counts the non-blank Order ID records.

Missing Values

Missing Values =
COUNTBLANK('Customer Data'[Order ID])

Counts blank values in the Order ID column.

Total Quantity

Total Quantity =
SUM('Customer Data'[Quantity])

Calculates the total quantity of products ordered.

Minimum Quantity

Minimum Quantity =
MIN('Customer Data'[Quantity])

Returns the smallest quantity value.

Maximum Quantity

Maximum Quantity =
MAX('Customer Data'[Quantity])

Returns the largest quantity value.

---

Data Preparation

Data preparation was performed using Power Query.

- Removed unnecessary blank rows from the Customer Data dataset.
- Promoted the first row as headers.
- Checked the datasets before creating visualizations.
- Applied the changes using Close & Apply.

---

Tools and Technologies Used

- Microsoft Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- Data Visualization

---

Skills Demonstrated

- Data loading and preparation
- Data cleaning
- Data visualization
- Clustered Column Chart
- Line Chart
- Pie Chart
- Calculated Columns
- DAX Measures
- Aggregation functions
- COUNTROWS
- COUNT
- COUNTBLANK
- SUM
- MIN
- MAX

---

Conclusion

This assignment helped me practice data analysis and visualization using Power BI. I learned how to create different charts, prepare datasets using Power Query, create calculated columns, and write DAX measures to analyze data.

The project improved my understanding of data visualization, data preparation, and basic DAX calculations.

---

Author: Anamika
Course: Data Analytics
