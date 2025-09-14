# 📊 SQL Data Warehouse & Analytics Project  

Welcome to the **SQL Data Warehouse & Analytics Project** 🚀  
This project demonstrates how to design and implement a **modern data warehouse** using the **Medallion Architecture** (Bronze, Silver, Gold layers) and leverage **ETL pipelines** for analytics and reporting.  

Designed as a **Data Engineering portfolio project**, it highlights **data modeling, ETL pipeline development, and SQL-based analytics** skills.  



## 🏗️ Data Architecture  

This project follows the **Medallion Architecture** approach:  

![Data Architecture](docs/data_architecture.png)  

1. **Bronze Layer** → Raw data ingestion (CSV → SQL Server Staging Tables).  
2. **Silver Layer** → Data cleaning, normalization, and transformations.  
3. **Gold Layer** → Star Schema (Fact & Dimension tables) optimized for analytics and reporting.  



## 📖 Project Overview  

This project demonstrates:  

- **Data Ingestion**: Loading ERP & CRM CSV datasets into SQL Server.  
- **ETL Pipelines**: SQL scripts & transformations across Bronze → Silver → Gold.  
- **Data Modeling**: Star Schema with **Fact (sales)** and **Dimension (customer, product, date, region)** tables.  
- **Analytics & Reporting**: SQL queries for sales trends, product performance, and customer insights.  
- **Dashboard Ready Data**: Gold layer optimized for BI tools (Power BI / Tableau).  



## 🎯 Skills Showcased  

- SQL Development (DDL, DML, Joins, Aggregations)  
- Data Modeling (Star Schema, Fact & Dimensions)  
- ETL Pipeline Design (Bronze → Silver → Gold)  
- Data Quality & Cleansing  
- Analytics & Business Reporting  



## 🛠️ Tools & Tech Stack  

- **SQL Server Express** – Data warehouse environment  
- **SQL Server Management Studio (SSMS)** – Database management  
- **DrawIO** – Architecture & schema diagrams  
- **Python / Airflow (Optional)** – ETL automation (future scope)  
- **Power BI / Tableau** – BI dashboards  


## 🚀 Project Requirements  

### Data Engineering Goals  
- Consolidate **ERP (Products, Sales)** and **CRM (Customers)** data into a single SQL Server Data Warehouse.  
- Implement **Bronze, Silver, and Gold layers** for transformation.  
- Build **Fact & Dimension tables** for analytics.  
- Maintain **data quality & consistency**.  

### Analytics Goals  
Deliver insights using SQL queries:  
- Top-performing products by revenue  
- Sales by region & time period  
- Customer segmentation analysis  
- Monthly & quarterly sales trends  


## 📂 Repository Structure  

```bash
sql-data-warehouse-project/
│
├── datasets/                     # ERP & CRM source CSV files
│
├── docs/                         # Documentation & diagrams
│   ├── data_architecture.png      # Architecture diagram
│   ├── data_models.png            # Star schema diagram
│   ├── etl_flow.png               # ETL pipeline flow
│
├── scripts/                      # SQL Scripts
│   ├── bronze/                   # Raw data load scripts
│   ├── silver/                   # Cleaning & transformations
│   ├── gold/                     # Fact & Dimension modeling
│
├── tests/                        # SQL test queries (data quality checks)
│
├── README.md                     # Project documentation
└── requirements.txt              # Tools & dependencies
