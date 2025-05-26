# 🛒 Retail Data Engineering Project Portfolio
## 📌 Summary
This project demonstrates a complete data engineering pipeline built to process, model, and visualize retail transaction data. It showcases industry-standard practices for building scalable and maintainable data systems, turning raw transactional data into actionable business intelligence reports.
## Data Pipeline 
![DE-Retail-2](https://github.com/user-attachments/assets/ca9f2ced-a9b4-4b21-8880-be7578b3f3a8)


## 📦 Data Source
The dataset used in this project is the Online Retail Dataset available on Kaggle:
🔗 https://www.kaggle.com/datasets/tunguz/online-retail
This dataset contains transactional data for a UK-based online retail store, including invoice numbers, product codes, quantities, prices, and timestamps.

## 🧱 Data Model
![DE-Retail-3](https://github.com/user-attachments/assets/c0917094-2f28-4101-9f8a-6648e2a6c599)
The data model follows a traditional star schema optimized for analytical queries:
1. Fact Table:
* fact_transactions – contains all transactional-level data (InvoiceNo, Date, Quantity, TotalAmount)
2. Dimension Tables:
* dim_customer – customer information
* dim_product – product details
* dim_date – date dimension for time-based analytics

## 🛠 Technology Stack
| Tool         | Purpose                                  |
| ------------ | ---------------------------------------- |
| **Airflow**  | Workflow orchestration for ETL pipelines |
| **BigQuery** | Cloud data warehouse for storage & query |
| **DBT**      | Data transformation and modeling         |
| **Soda**     | Data quality testing                     |
| **Metabase** | Dashboarding and reporting               |
| **Docker**   | Containerization for reproducible setups |

## 📊 Final Result
The project produces a comprehensive retail sales report delivered via interactive dashboards in Metabase, including KPIs such as:
* Total 10 Product by Quantity
* Total Revenue per Month
* Primary Markets

![Uploading DE-Retail-1.png…]()
