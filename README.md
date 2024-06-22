# Marketing Customer Data Warehouse
## 1. Dataset
- Data: [Marketing Campaign](https://github.com/YuehHanChen/Marketing_Analytics/blob/main/marketing_data.csv)
- The data on marketing campaigns is collected for 2 years and published in 12/2020 (2012-2014).
- Throughout the dataset, we can claim customers information, the money spent for each kind of products, the purchases of different ways, customers responses,...
- The dataset includes 28 columns, 2240 rows.
------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 2. Dimension and Fact Table
### a. DimDate Table
- Contains information about recorded timestamps.
- Includes attributes such as year, quarter, day, month.
- Primary key of this table is "Datekey".
### b. DimCustomer Table
- Contains information about recorded customers.
- Includes attributes such as income, marital status, amount paid for each type of prods,...
- Primary key of this table is "CustomerKey".
### c. Fact_MarketingAnalytic Table
- Contains information about customer influences on Marketing campaigns.
- Includes attributes such as complaints, total approved campaigns, total spent,...
- This table will refer to the previous two Dimension tables to establish relationships.
