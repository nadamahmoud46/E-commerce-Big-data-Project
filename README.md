# Ecommerce Big-Data Analytics Project

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


<img width="1920" height="1080" alt="Blue and White Modern Data Analysis Presentation" src="https://github.com/user-attachments/assets/021f269b-936e-41b2-b293-87b0cdc8909e" />

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
