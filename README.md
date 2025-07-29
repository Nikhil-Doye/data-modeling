# 🧱 Databricks Data Modeling: Medallion Architecture Implementation

This repository contains the Databricks `.dbc` notebook used in the **“Data Modeling”** Medium article series.

📖 **Read the full article here →** [Data Modeling (Part 2)](https://nikhil-datasolutions.medium.com/practical-data-modeling-medallion-architecture-on-databricks-c524f6de0cbb)

---

## 📂 What’s Inside

The `.dbc` notebook in this repo includes:

✅ Simulated **source table** creation  
✅ **Bronze Layer** setup with transient staging and incremental loading  
✅ **Silver Layer** transformations and UPSERT logic  
✅ **Gold Layer** dimensional modeling with:
  - Star & Snowflake schemas
  - Fact and dimension tables
  - One Big Table (OBT)  
✅ Handling of **Slowly Changing Dimensions (SCD Type 1 and 2)**

---

## 📦 How to Use

1. **Login** to Databricks Free Edition
2. Navigate to your **Workspace**
3. Right-click your user folder → Click **Import**
4. Upload the `.dbc` file from this repository
5. Open the notebook and run each cell step by step

---

## 🛠️ Requirements

- Databricks Community Edition (or any Databricks environment)
- Basic understanding of SQL and Spark
- Familiarity with Medallion Architecture (Bronze → Silver → Gold)

---

## 🧠 Key Learning Concepts

- Data Modeling in cloud-native environments
- Incremental data loading
- UPSERTs and deduplication
- Star and Snowflake schema design
- Understanding facts and dimensions
- Implementing Slowly Changing Dimensions (SCD)
