# 🏠 Greater Manchester Domestic Energy Performance Certificate Analysis

This project analyzes the **Energy Performance Certificates (EPCs)** of domestic properties in Greater Manchester using SQL queries.  
It focuses on extracting insights related to property energy efficiency, costs, and environmental impact.

## 📂 Project Structure

- **SQL Script**: `SQLQuery2.sql` (Contains all queries)

## 🛠️ Methods and Techniques

- Data extraction and filtering from EPC datasets.
- Aggregation of energy cost components (lighting, heating, hot water, total cost).
- Year-wise analysis of property types and their energy performance.
- Preparation of data for visualization in BI tools like Power BI.

## 📋 Requirements

- A database management system (e.g., Microsoft SQL Server, MySQL) containing EPC-related data.
- A table structure that includes fields like:
  - `LODGEMENT_DATE`
  - `PROPERTY_TYPE`
  - `ENERGY_COST`
  - `LIGHTING_COST`
  - `HEATING_COST`
  - `HOT_WATER_COST`
  - `TOTAL_COST`
- Basic SQL knowledge to modify and extend queries if needed.

## 🚀 How to Run

1. Load your EPC dataset into your SQL database.
2. Open `SQLQuery2.sql` in your preferred SQL client (e.g., SQL Server Management Studio, MySQL Workbench).
3. Execute the queries step-by-step to:
   - Filter relevant records
   - Perform aggregations
   - Extract trends for reporting and analysis

## 📊 Key Insights

- Total energy costs by property type and year.
- Identification of properties with higher heating, lighting, or hot water costs.
- Trends in energy performance improvements over time.

## ✨ Notes

- Make sure your dataset structure matches the fields referenced in the queries.
- This SQL script was designed for **energy performance analysis** and can be customized for more detailed exploration or visualization.

---

Feel free to fork this repository, adapt the SQL queries, and extend the analysis to other regions or more recent data!
