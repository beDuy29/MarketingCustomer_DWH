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
------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 3. Schema
- Star Schema ![image](https://github.com/beDuy29/MarketingCustomer_DWH/assets/117710630/252e01f2-5ddd-410d-8bcf-1f9351a9ae75)
------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 4. ETL Process
- Using Microsoft Tool: SSIS Tool
- Includes 3 stages:
  + Step 1: Clean Data Lake and Load Dataset ![image](https://github.com/beDuy29/MarketingCustomer_DWH/assets/117710630/48951081-214f-45e7-a307-eefc387d99f8)
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------
  + Step 2: Staging ![image](https://github.com/beDuy29/MarketingCustomer_DWH/assets/117710630/eeaa3d3c-4d9e-495e-a0db-65f73b082fbf)
  + Step 3: ETL Staging to Dimension and Create Fact Table, then set Foreign Key ![image](https://github.com/beDuy29/MarketingCustomer_DWH/assets/117710630/f15920b2-6033-48e8-ba1e-d155cbb1e4dc)
------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 5. SSAS Process
- Using Microsoft Tool: SSAS Tool
- Cubes ![image](https://github.com/beDuy29/MarketingCustomer_DWH/assets/117710630/6dffd27e-e0c5-4b2e-aa61-38c6f6c8eba6)
- Hierachies for DimDate ![image](https://github.com/beDuy29/MarketingCustomer_DWH/assets/117710630/cf70584b-0441-49f5-9a49-26bdf2606c7b)
------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 6. Dashboard with Power BI
![image](https://github.com/beDuy29/MarketingCustomer_DWH/assets/117710630/156f19b5-b925-4a60-8275-d8cbeff404f7)
------------------------------------------------------------------------------------------------------------------------------------------------------------------
**If you have any questions about the assignment, please contact me via the following email:** 
💬︎ lehoangducduykt@gmail.com





