# ecommerce-SQL-Project

## Executive Summary
In this SQL project, I conducted an extensive analysis of e-commerce sales data, focusing on key objectives and additional insights. The project encompassed the following:

- Utilized SQL to analyze sales figures and identify stores with the highest and lowest sales performance.
- Explored and evaluated the performance of various departments within these stores, providing a comprehensive understanding of sales distribution.
- Investigated the potential influence of key variables, such as unemployment rates, temperature, fuel prices, consumer price index (CPI), and holiday seasons, on sales.
- Leveraged SQL to perform statistical analysis and assess the correlation or significance of these variables with sales performance.

   
## Data Dictionary

This dataset contains 3 tables - features data table, sales data table and stores data table. 
- The Features table contains 12 coluns and 8191 rows.
- The sales table contains 5 columns and 421571 rows.
- The stores table contains 3 columns and 64 rows.

**Features Table** 

| Column                  | Description                             | Data Type      |
| :---------------------- | :-------------------------------------- | :------------- |
| store                   | Invoice of the sales made               | VARCHAR(30)    |
|date                     | Branch at which sales were made         | VARCHAR(5)     |
| temprature              | The location of the branch              | VARCHAR(30)    |
| fuel price              | The type of the customer                | VARCHAR(30)    |
| markdown 1              | Gender of the customer making purchase  | VARCHAR(10)    |
| markdown 1              | set of related products                 | VARCHAR(100)   |
| markdown 1               | The price of each product               | DECIMAL(10, 2) |
| markdown 1                | The amount of the product sold          | INT            |
| markdown 1                    | The amount of tax on the purchase       | FLOAT(6, 4)    |
| CPI               | The total cost of the purchase (sales)  | DECIMAL(10, 2) |
| unemployment                    | The date on which the purchase was made | DATETIME       |
| IsHoliday                   | The time at which the purchase was made | TIME           |



**Sales Table**
| Column                  | Description                             | Data Type      |
| :---------------------- | :-------------------------------------- | :------------- |
| store                   | Invoice of the sales made               | VARCHAR(30)    |
|dept                    | Branch at which sales were made         | VARCHAR(5)     |
| date              | The location of the branch              | VARCHAR(30)    |
| weekly_sales             | The type of the customer                | VARCHAR(30)    |


**Stores Table**

| Column                  | Description                             | Data Type      |
| :---------------------- | :-------------------------------------- | :------------- |
| store                   |                                         | VARCHAR(30)    |
|type                     |                                          | VARCHAR(5)     |
| size                    | The location of the branch              | VARCHAR(30)    |


 ### Query types used:
- Count(distinct)
- Create table
- Insert into
- min/max
- SUM
- AVG
- Row_Number()
- Partition by
- ROUND
- Where between
- Joins
- CTEs
- Case statement
- Group by
- Order by



By examining these multiple factors, I aimed to gain comprehensive insights into the sales patterns and dynamics of the e-commerce business. This project showcases my proficiency in SQL and demonstrates my ability to perform advanced analysis to uncover valuable correlations and trends.
