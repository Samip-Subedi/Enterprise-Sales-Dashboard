📊 Enterprise Sales Intelligence Dashboard (TPC-H)

Power BI + Snowflake | End-to-End Business Intelligence Project

📌 Project Overview

This project presents a comprehensive multi-page Business Intelligence dashboard built using the TPC-H sample dataset from Snowflake. The objective was to transform raw enterprise-scale transactional data into meaningful insights through structured data modeling, advanced DAX calculations, and executive-level visual storytelling.

The report is designed to support strategic decision-making by providing visibility into revenue trends, product performance, customer segmentation, supplier insights, and geographic distribution.

🗂 Data Source

Database: SNOWFLAKE_SAMPLE_DATA

Schema: TPCH_SF1

Data Warehouse: Snowflake

Fact Table: LINEITEM

Dimension Tables: ORDERS, CUSTOMER, PART, SUPPLIER, NATION, REGION

🏗 Data Modeling

Designed a star-schema data model

Integrated 7 relational tables

Established many-to-one relationships

Implemented optimized cross-filtering

Created a Date hierarchy (Year → Quarter → Month → Day)

📈 Key Metrics (DAX Measures)

Total Revenue

Total Orders

Average Order Value

Total Quantity Sold

Number of Customers

Number of Suppliers

Advanced DAX calculations were implemented to ensure accurate aggregation and business reporting.

📊 Dashboard Pages
1️⃣ Executive Summary

KPI Cards (Revenue, Orders, AOV, Quantity)

Monthly Revenue Trend

Top 10 Customers

Revenue by Region

Global Year & Region slicers

2️⃣ Product Analysis

Product Performance Table

Revenue by Product Type

Quantity vs Revenue Scatter Plot

Top 5 Parts by Revenue

Product Type page-level slicer

3️⃣ Customer & Supplier Insights

Customer Market Segmentation

Top Supplier Performance

Customer Distribution Map

Order Priority Breakdown

Cross-filtering enabled across visuals

🎯 Key Features

Interactive slicers and filters

Drill-down date hierarchy

Cross-page filtering

Conditional formatting

Executive-ready dashboard design

Clean, consistent formatting & branding

🛠 Tools & Technologies

Power BI Desktop

Snowflake (Cloud Data Warehouse)

DAX (Data Analysis Expressions)

Power Query

Star Schema Data Modeling

