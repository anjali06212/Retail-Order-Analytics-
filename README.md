# End-to-End Retail Order Analytics (Python + SQL)

This project showcases a complete end-to-end analytics workflow using Python and SQL, transforming raw retail order data into business insights. The project demonstrates experience across data extraction, cleaning, modeling, loading, and analytical querying.

---

##  Project Summary

- **Dataset Size:** 9,994 retail order records across 1,862 unique products
- **Geographic Coverage:** 531 cities across 49 states in the United States
- **Analysis Objectives:** Revenue analysis, product performance, customer segmentation, and profitability insights

---

## Architecture & Workflow

1. **Data Extraction**
   - Dataset downloaded programmatically using the Kaggle API.

2. **Data Cleaning & Preprocessing (Python + Pandas)**
   - Standardized column formats
   - Handled missing values
   - Derived key fields including:
     - Discount
     - Sale price
     - Profit
   - Converted date fields to datetime format

3. **Database Integration (SQL Server)**
   - Cleaned data was loaded into SQL Server tables for querying and reporting.

4. **Data Analysis (SQL)**
   - Executed analytical queries for:
     - Category and segment performance
     - Revenue aggregation
     - Profitability analysis
     - Customer purchasing behavior

---

##  Key Metrics Computed

| Metric | Value |
|---|---|
| Total Orders | 9,994 |
| Unique Products | 1,862 |
| Total Revenue | \$11,079,328.20 |
| Total Profit | \$1,039,928.20 |
| States Covered | 49 |
| Cities Covered | 531 |
| Categories | 3 |
| Segments | 3 |

---

##  Tools & Technologies

- **Python:** Pandas, SQLAlchemy
- **SQL:** SQL Server
- **Data Source:** Kaggle Dataset (Retail Orders)
- **ETL Pattern:** Extract → Transform → Load

---

## 📂 Repository Structure

