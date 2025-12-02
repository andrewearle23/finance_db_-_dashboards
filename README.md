# SAP B1 → MySQL ETL & Power BI Dashboards

This project provides a lightweight ETL pipeline that extracts core business data from SAP Business One (SQL Server), transforms it into a clean reporting model, and loads it into a MySQL analytics database. The resulting datasets are used to build interactive Power BI dashboards for sales, inventory, purchasing, and finance.

## 🚀 Features

Extract SAP B1 tables and views directly from SQL Server

Transform and clean data using SQL/Python

Load into a structured MySQL reporting database

Connect Power BI directly to MySQL for analytics

Modular design for easy extension and custom objects

## 📁 Repository Structure
```bash
/etl/
  extract/        # SQL Server extraction scripts
  transform/      # Data cleaning and transformation
  load/           # Load processes for MySQL

/mysql/
  schema/         # MySQL DDL for reporting model

/powerbi/
  dashboards/     # PBIX files and data model

/docs/
  architecture/   # Optional diagrams and notes

```

🔧 Requirements

SQL Server access to SAP B1 database

MySQL server (8.0+)

Python 3.x (optional, if using Python ETL scripts)

Power BI Desktop

## ▶️ Getting Started

Configure connection settings in the ETL scripts

Run extraction and load jobs to populate the MySQL DB

Open Power BI dashboards and update the MySQL connection

Refresh to view live analytics

## 📊 Output

A clean analytics database powering fast, flexible Power BI dashboards without impacting SAP performance.
