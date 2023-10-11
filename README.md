# Data-Analytics-Training-Task-two-2-

### Overview
The primary aim of this is to provide insights into the sales performance of the sales company while exploring the basic formulars and functions of excel in data analysis. Using the sales data, we were asked to determine:

- The total revenue and profit generated
- The average revenue and units sold for every order
- The total discount given in $
- Total number of sales recorded
- Highest profit generated
- Create a column named “sales range”, return “High sales” if the sales value is above average, otherwise return “low sales”

### Data Sources
The primary Dataset used for this task is sales dataset containing detailed information about each sales made by the company.

### Tools
Excel

### Data Cleaning

I performed the following tasks:

- I used the sum formular **=SUM(A2:A701)**, on the sales column  to get the total revenue 
- I used the sum formular  **=SUM(L2:L701)** , on the profit column to get the total profit
- I used the sum formular **=SUM(F2:F701)**, on the discount column to get the total discount
- I used the count formular **=COUNT(A2:A701)**, on the sales column to get the total number of sales
- I calculated the average revenue by using the average formular **=AVERAGE(A2:A701)** on the sales column.
- I calculated the average unit sold by using the average formular **=AVERAGE(O2:O701)** on the units column.
- I calculated the highest profit by using the max  formular **=MAX(L2:L701)** on the profit column.

- I also created a column “sales range”, where I returned “high sales” when the sales value is above average and “low sales” when it is below average.

I did this using the IF formular, without failing to reference the cell absolutely. thus this  **=IF(A2>$X$2, "High sales", "Low sales")** was our formular.



### Reference

Data Analytics For Absolute Beginners: 
A Deconstructed Guide to Data Literacy (Second Edition) 
Copyright © 2019 by Oliver Theobald


