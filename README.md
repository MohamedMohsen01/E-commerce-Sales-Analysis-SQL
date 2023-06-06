# ecommerce-SQL-Project

In this SQL project, I conducted an extensive analysis of e-commerce sales data, focusing on key objectives and additional insights. The project encompassed the following:

- Utilized SQL to analyze sales figures and identify stores with the highest and lowest sales performance.
- Explored and evaluated the performance of various departments within these stores, providing a comprehensive understanding of sales distribution.
- Investigated the potential influence of key variables, such as unemployment rates, temperature, fuel prices, consumer price index (CPI), and holiday seasons, on sales.
- Leveraged SQL to perform statistical analysis and assess the correlation or significance of these variables with sales performance.

   
## Data Dictionary

This dataset contains 3 tables - features data table, sales data table and stores data table. 
- The Feature table contains 12 coluns and 8191 rows.
- The sales table contains 5 columns and 421571 rows.
- The stores table contains 3 columns and 64 rows.

**Feature Table**

| Column                  | Description                             | Data Type      |
| :---------------------- | :-------------------------------------- | :------------- |
| invoice_id              | Invoice of the sales made               | VARCHAR(30)    |
| branch                  | Branch at which sales were made         | VARCHAR(5)     |
| city                    | The location of the branch              | VARCHAR(30)    |
| customer_type           | The type of the customer                | VARCHAR(30)    |
| gender                  | Gender of the customer making purchase  | VARCHAR(10)    |
| product_line            | set of related products                 | VARCHAR(100)   |
| unit_price              | The price of each product               | DECIMAL(10, 2) |
| quantity                | The amount of the product sold          | INT            |
| VAT                     | The amount of tax on the purchase       | FLOAT(6, 4)    |
| Revenue                 | The total cost of the purchase (sales)  | DECIMAL(10, 2) |
| date                    | The date on which the purchase was made | DATETIME       |
| time                    | The time at which the purchase was made | TIME           |
| payment_method          | The total amount paid                   | DECIMAL(10, 2) |
| cogs                    | Cost Of Goods sold                      | DECIMAL(10, 2) |
| Profit                  | Net Income                              | DECIMAL(10, 2) |
| Profit Margin           | percentage of Profit                    | FLOAT(11, 9)   |
| rating                  | Rating                                  | FLOAT(2, 1)    |


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
