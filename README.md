# Advanced SQL Analytics Project

This project showcases advanced SQL analytical techniques by building an analytical database from cleaned gold-layer datasets. The database was initialized from prepared customer, product, and sales data outputs generated in a prior Data Warehouse project using the Medallion Architecture (Bronze → Silver → Gold).

The SQL scripts in this project explore multiple advanced analysis patterns including:
- Database & dimensions exploration
- Date range filtering and aggregation
- Measures analysis
- Magnitude and ranking analysis
- Change-over-time and cumulative analyses
- Part-to-whole and segmentation analyses
- Customer and product reporting

## Project Context

This project is a continuation of a **Data Warehouse Project** where raw datasets were cleaned, standardized, and stored in a structured gold layer. The outputs from that project are used as inputs here for advanced analytics.

**Datasets used:**
- `gold.dim_customers.csv`
- `gold.dim_products.csv`
- `gold.fact_sales.csv`

**Reports generated:**
- `gold.report_customers.csv`
- `gold.report_products.csv`

## How to Run

1. Initialize the database using `00_init_database.sql`.
2. Sequentially execute the exploration and analysis scripts (`01_` to `13_`) inside the `scripts/` folder.
3. Review output tables or generate CSV reports based on query outputs.

## Skills Demonstrated

- Advanced SQL Querying
- Data Aggregation and Transformation
- Window Functions
- Date and Time Analysis
- Segmentation and Ranking
- Reporting and Insights Generation

---



