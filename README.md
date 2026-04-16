# pc_sales_analysis_pipeline_project
This project focuses on building an end-to-end data analysis pipeline for personal computer (PC) sales and performance data. The goal is to transform raw, unstructured data into meaningful insights that support business decision-making, pricing strategies, and inventory optimization.

# 📌 Overview
The PC Analysis Pipeline Project is an end-to-end data solution designed to transform raw PC sales and performance data into actionable business insights. This project demonstrates both data engineering and data analysis capabilities by building a structured pipeline that supports efficient querying, reporting, and decision-making.
The solution follows a real-world data workflow — from data ingestion and cleaning to transformation, modeling, and analysis.

# 🎯 Problem Statement
Businesses selling personal computers often deal with scattered and unstructured data, making it difficult to:
Track product performance
Monitor sales per employee
Analyze repair costs and profitability
Compare market pricing across different PC configurations
This project solves these challenges by creating a centralized, structured dataset that enables efficient analysis and reporting.

# 🎯 Project Objectives
Build a clean and structured dataset from raw PC data
Design a scalable data model (Star Schema)
Perform data transformation and validation
Analyze key business metrics using SQL
Generate insights to support business decisions

# 🏗️ Project Architecture
The pipeline follows these stages:

Data Ingestion:
Load raw PC dataset into the database

Data Cleaning & Transformation:
Handle missing values
Standardize formats (e.g., RAM, storage, pricing)
Ensure data consistency

Data Modeling:
Create a Fact Table (Sales/Transactions)
Create Dimension Tables (Product, Employee, Channel, etc.)
Establish relationships using primary and foreign keys

Data Analysis:
Perform SQL queries to extract insights
Calculate KPIs and performance metrics
