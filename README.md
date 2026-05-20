# Databricks-
# Ecommerce Data Pipeline using Databricks

## Project Overview
This project implements an end-to-end big data analytics pipeline for an e-commerce dataset using Databricks and PySpark. The pipeline follows the Bronze, Silver, and Gold architecture to ingest raw data, clean and transform it, and create business-ready analytical tables.

## Tech Stack
- Databricks Community Edition
- PySpark
- Spark SQL
- Delta Lake
- GitHub
- CSV Dataset

## Dataset
The project uses an e-commerce transactions dataset containing customer orders, products, categories, payment methods, quantities, prices, and order dates.

## Pipeline Architecture

### Bronze Layer
Raw CSV data was loaded into Databricks as the Bronze table.

### Silver Layer
Data cleaning and transformation were performed, including:
- Handling missing values
- Correcting data types
- Creating calculated columns
- Preparing structured transaction data

### Gold Layer
Business-level aggregate tables were created, including:
- Category-wise sales
- Monthly sales trends
- Payment method sales
- Top-selling products

## Visualizations
The final Gold tables were used to generate visualizations in Databricks for sales analysis and business insights.

## Project Outcomes
- Built a complete big data ETL pipeline in Databricks
- Used PySpark and Spark SQL for data processing
- Created Bronze, Silver, and Gold tables
- Generated analytical outputs for business decision-making
- Published the project to GitHub for version control and portfolio use
