# 🛒 End-to-End E-Commerce(Olist) Project using PySpark, Databricks & Delta Lake

## 📌 Project Objective

To design and implement an end-to-end data engineering workflow for a large-scale e-commerce dataset using **PySpark**, **Databricks**, and **Delta Lake**. The project focuses on data ingestion, quality validation, cleaning, transformation, feature engineering, and optimized data storage to create reliable datasets for downstream analytics and reporting.

---

## 📁 Data Source

- Public E-Commerce transactional datasets
- Data includes:
  - Customer information
  - Orders and order status
  - Order items
  - Products and categories
  - Sellers
  - Payments
  - Customer reviews
  - Geolocation information

---

## 🛠 Tools & Technologies Used

- PySpark
- Databricks
- Delta Lake
- SQL
- Git & GitHub
- Databricks Volumes

---
## 🏗️ Project Architecture

```text
Source Files (CSV)
        ↓
Databricks Volumes
        ↓
PySpark DataFrames
        ↓
Data Quality Validation
        ↓
Data Cleaning & Standardization
        ↓
Data Transformation & Integration
        ↓
Feature Engineering
        ↓
Delta Lake Storage
        ↓
Analytics Layer
```
---

## 🔄 Data Engineering & Processing

### Data Ingestion

- Uploaded raw CSV datasets into Databricks Volumes.
- Loaded datasets into PySpark DataFrames.
- Performed schema validation and record count verification.

### Data Quality Validation

- Identified missing values across datasets.
- Detected duplicate records.
- Validated dataset completeness and consistency.
- Performed data profiling and quality assessment.

### Data Cleaning & Standardization

- Handled missing values using PySpark transformations.
- Removed duplicate records.
- Standardized payment categories and attributes.
- Applied data type conversions for efficient processing.

### Data Transformation & Integration

- Joined customer, order, payment, product, seller, review, and geolocation datasets.
- Created consolidated order-level datasets.
- Applied business rules and transformation logic.
- Built reusable datasets for downstream analytics.

### Feature Engineering

- Customer Segmentation
- Product Size Classification
- Order Revenue Calculation
- Delivery Time Metrics
- Weekday vs Weekend Order Classification

### Data Storage & Optimization

- Stored processed datasets in Delta Lake format.
- Applied Delta Lake optimization techniques.
- Implemented Z-Ordering to improve query performance.
- Created optimized datasets for analytical workloads.

---

## ⚙️ PySpark Concepts Applied

- DataFrame API
- Aggregations & GroupBy
- Inner & Left Joins
- Conditional Transformations (`when`, `otherwise`)
- Missing Value Handling
- Duplicate Removal
- Feature Engineering
- Outlier Detection using Quantiles
- Date & Time Functions
- Delta Lake Operations
- Data Quality Validation
- Delta Optimization & Z-Ordering

---

## 📊 Data Processing & Modeling

### Data Integration

- Combined multiple datasets into a unified analytical model.
- Established relationships between customers, orders, products, sellers, payments, and reviews.
- Built a consolidated dataset for efficient querying.

### Data Quality Improvements

- Eliminated duplicate records.
- Standardized inconsistent values.
- Improved dataset reliability through validation and cleansing processes.

### Dataset Optimization

- Optimized storage using Delta Lake.
- Improved query performance through Z-Ordering.
- Prepared datasets for scalable analytics workloads.

---

## 📈 Key Engineering Challenges Addressed

- Processing and integrating multiple interconnected datasets.
- Handling missing and inconsistent data.
- Creating reusable and scalable transformation logic.
- Building optimized datasets for analytical consumption.
- Improving query performance using Delta Lake optimization techniques.
- Managing version-controlled development through Git and GitHub.

---

## 🚀 Project Outcomes

- Built an end-to-end data processing workflow using PySpark and Databricks.
- Processed and transformed multiple interconnected e-commerce datasets.
- Implemented data quality validation and cleansing procedures.
- Created a consolidated analytical data model.
- Stored processed datasets in Delta Lake format.
- Applied optimization techniques to improve data retrieval performance.
- Integrated GitHub version control with Databricks for collaborative development and code management.
