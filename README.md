# Sales Analytics Data Lake using AWS Glue and Power BI

## Project Overview

This project demonstrates an end-to-end Data Engineering pipeline using AWS services and Power BI.

The pipeline ingests sales data into Amazon S3, catalogs metadata using AWS Glue Crawler, performs transformations using AWS Glue Visual ETL, stores processed data in S3, and visualizes insights through Power BI dashboards.

---

## Architecture

![Architecture](architecture/architecture.png)

---

## Technology Stack

- Python
- AWS S3
- AWS Glue Crawler
- AWS Glue Data Catalog
- AWS Glue Studio (Visual ETL)
- Power BI

---

## Data Flow

Sales CSV
↓
S3 Raw Layer
↓
Glue Crawler
↓
Glue Data Catalog
↓
Glue ETL
↓
S3 Processed Layer
↓
Power BI Dashboard

---

## Dashboard KPIs

- Total Revenue
- Total Profit
- Units Sold
- Revenue by Region
- Sales Channel Distribution
- Product Performance

---

## Screenshots

### S3 Bucket

![S3](screenshots/s3-bucket.png)

### Glue Crawler

![Crawler](screenshots/glue-crawler.png)

### Glue ETL

![ETL](screenshots/glue-etl-job.png)

### Dashboard

![Dashboard](screenshots/dashboard.png)

---

## Business Metrics Created

- Shipping Days
- Profit Margin %

---

## Author

Maitree Pimple
