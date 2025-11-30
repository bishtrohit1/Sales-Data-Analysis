# Sales Data Analysis

A comprehensive project for exploring, analyzing, and visualizing sales data using SQL queries and Power BI dashboards.

## Project Overview

This repository enables you to perform deep-dive sales insights via SQL-based exploration and interactive dashboards. It provides the necessary database dumps and Power BI resources required to get you started with your own analysis or extend the provided work.

## Features

- **SQL Analysis**  
  - Query templates for extracting actionable insights from sales data.
  - Multiple database dump versions for flexible experimentation.

- **Data Visualization**  
  - Complete Power BI dashboard included for sales insight.
  - PDF export of the dashboard for quick sharing.

## Repository Structure

| File/Folders                       | Description                                                    |
|-------------------------------------|----------------------------------------------------------------|
| `Sales_db_Initial_Insights.sql`     | SQL queries for initial insights and analysis                  |
| `db_dump_version_2_main.sql`        | Full sales database dump (version 2)                           |
| `db_dump_without_ProfitMarginColumns.sql` | Database dump without profit margin columns             |
| `Sales Insight.pbix`                | Power BI dashboard file                                        |
| `Sales Insight Dashboard.pdf`       | Exported visualization as PDF                                  |
| `README.md`                        | This documentation file                                        |

## Getting Started

1. **Database**:  
   - Use `db_dump_version_2_main.sql` or `db_dump_without_ProfitMarginColumns.sql` to restore the sales database in your SQL server.
   - Run the queries in `Sales_db_Initial_Insights.sql` to analyze core sales insights.

2. **Visualization**:  
   - Open `Sales Insight.pbix` in Power BI Desktop to interact with the dashboard.
   - Review `Sales Insight Dashboard.pdf` for a static snapshot.

## Usage Example

- Restore one of the provided `.sql` files to your local or cloud SQL server.
- Execute analytics queries from `Sales_db_Initial_Insights.sql`.
- Connect Power BI to your database if you wish to refresh the dashboard with different data.

## Requirements

- Microsoft SQL Server or compatible database to load `.sql` files
- Power BI Desktop (for `.pbix` dashboard viewing)
