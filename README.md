# Sales KPI Analysis using PySpark

This project demonstrates end-to-end sales data analysis using PySpark on Databricks.  
Key features:
- Data cleaning, type conversion, timestamp parsing, duplicate removal
- Calculation of daily and product-level KPIs (revenue, margin, units sold) using Spark SQL
- Stored results in Databricks metastore
- Power BI dashboard created for interactive KPI visualization

# Tools Used
- Python (PySpark)
- Databricks
- SQL
- Power BI

This project uses the "sales orders" dataset from Kaggle:
https://www.kaggle.com/datasets/vincentcornlius/sales-orders/data

# How to Replicate
1. Download the dataset from the Kaggle link above  
2. Upload the CSV into your Databricks workspace (DBFS)  
3. Open the included 'sales_analytics_pyspark.ipynb' notebook  
4. Run the cells in order:
   - Load and clean data with PySpark
   - Register a temporary SQL view
   - Compute KPIs using Spark SQL
   - Save results to the Databricks metastore

# Outputs
- **analytics_daily_kpis** - daily revenue, margin, units sold, and order count
- **analytics_product_kpis** – total revenue, total margin, and units sold by product

Power BI Dashboard Preview:
<img width="1318" height="741" alt="image" src="https://github.com/user-attachments/assets/77d0e233-db5c-4f57-a4dd-c9c5455e56d3" />
<img width="1310" height="738" alt="image" src="https://github.com/user-attachments/assets/fe9b2b3f-3353-45ea-98c6-f0b53ed2f11f" />
