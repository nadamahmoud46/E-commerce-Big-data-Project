## Project Overview
This is an end-to-end ecommerce analytics project that demonstrates a complete **data pipeline**, from data generation to interactive dashboards. The project is designed to showcase modern data engineering and analytics workflows using **Python, Amazon S3, Airbyte, Snowflake, dbt, and Power BI**.

**Objectives:**
- Generate realistic ecommerce data (**>1 million rows**)
- Store data in Amazon S3
- Extract and load data into Snowflake using Airbyte
- Transform and model data with dbt
- Perform analytics in Snowflake
- Create professional dashboards in Power BI




## Tech Stack
| Layer                  | Technology/Tool        |
|------------------------|-----------------------|
| Data Generation        | Python (Faker)        |
| Data Storage           | Amazon S3             |
| ETL/ELT                | Airbyte               |
| Data Warehouse         | Snowflake             |
| Data Transformation    | dbt                   |
| Analytics & Dashboard  | Power BI              |
| Scripting/Queries      | SQL, Python, DAX      |

---



## Project Workflow

```text
Python Data Generation (>1M rows)
          │
          ▼
      Amazon S3 (CSV/Parquet)
          │
          ▼
       Airbyte ETL
          │
          ▼
   Snowflake RAW Layer
          │
          ▼
     dbt Transformations
(staging -> dim/fact marts)
          │
          ▼
   Analytics Queries in Snowflake
          │
          ▼
     Power BI Dashboards
(Sales Overview, Customer Insights, Product Performance)

```

# Dashboards

## Sales Overview Dashboard
<img width="1052" height="588" alt="dash1Capture" src="https://github.com/user-attachments/assets/346befbe-28f7-44fc-89f1-bb662522e3f9" />


## Customer Insight Dashboard
<img width="1063" height="584" alt="dash2Capture" src="https://github.com/user-attachments/assets/66cbec2b-886a-4684-882e-31960ef958fc" />


