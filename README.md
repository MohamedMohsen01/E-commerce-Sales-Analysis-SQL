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


## Methodology 

1. **Data Understanding:**

   > Familiarized myself with the dataset's structure, including the available columns, data types, and data dictionary.
  Gained an understanding of the specific business questions or objectives that need to be addressed using the dataset.

2. **Data Assessment:** 
   > I assessed the quality and structure of the data to identify any issues or inconsistencies that needed to be addressed. This involved checking for missing        values, outliers, inconsistent formatting, or data entry errors.

3. **Data Cleaning and Preprocessing:**
    my role in data wrangling and cleaning involved several tasks to ensure the data was in a usable and reliable format. Here are some key steps I took:
  > - I employed techniques like imputation or deletion, depending on the nature of the missing data.
  > - I eliminated any duplicate records or entries to ensure data integrity.
  > - I standardized the formats of data fields, such as dates, currencies, and units, to ensure consistency.
     
4. **Data Transformation:**
  > I conducted data transformations to derive meaningful insights or facilitate analysis. This involved tasks like:
   > - Aggregating Data: I aggregated data at different levels, such as weekly, yearly, and by categories, to enable analysis and reporting.

5. **Data Integration:** 
  > After cleaning and transforming the data, I validated the results to ensure accuracy and integrity. I worked with multiple data sources, I merged or joined datasets based on common identifiers or keys to combine relevant information into a unified dataset.




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
