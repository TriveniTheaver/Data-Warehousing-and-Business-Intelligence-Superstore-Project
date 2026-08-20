# DWBI Project – Superstore Retail Sales

## 📌 Overview
This project implements a complete Data Warehouse and Business Intelligence solution for a US‑based retail company (Superstore).

## 🏗️ Architecture
- **Source Systems** – SQL Server (orders) + Excel (customers, products)
- **Staging** – Superstore_Staging (SSIS ETL)
- **Data Warehouse** – Star schema with 1 fact table and 5 dimensions (SCD Type 2)
- **BI Layer** – SSAS cube (OLAP) + Excel PivotTables + Power BI dashboards

## 📂 Repository Structure
- `DataWarehouse_IT23563032/` – SQL scripts and backup
- `CubeProject_IT23563032/` – SSAS solution
- `Excel_IT23563032/` – OLAP pivot tables
- `PowerBIReports_IT23563032/` – Power BI dashboards
- `Document_IT23563032/` – Assignment reports

## ✅ Key Features
- ETL pipeline using SSIS (3 packages)
- SCD Type 2 for customer history tracking
- Accumulating snapshot fact for order lifecycle
- SSAS cube with hierarchies (date, location, product)
- Excel OLAP operations (roll‑up, drill‑down, slice, dice, pivot)
- Power BI reports with cascading filters and drill‑through

## 🛠️ Tools Used
- SQL Server (SSMS, SSDT, SSIS)
- SQL Server Analysis Services (SSAS)
- Microsoft Excel (PowerPivot)
- Power BI Desktop / Service
