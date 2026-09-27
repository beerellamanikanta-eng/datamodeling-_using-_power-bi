# Data Modeling Using Power BI 📊

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-blue?logo=github)](https://github.com/beerellamanikanta-eng/datamodeling-_using-_power-bi)
[![Power BI](https://img.shields.io/badge/Power_BI-Desktop-F2C811?logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)

A comprehensive end-to-end repository for mastering **Data Modeling, Power Query transformations, Star Schema architecture, and interactive dashboard creation** in Microsoft Power BI.

🔗 **Project Link:** [https://github.com/beerellamanikanta-eng/datamodeling-_using-_power-bi](https://github.com/beerellamanikanta-eng/datamodeling-_using-_power-bi)

---

## 📁 Repository Structure

```plaintext
datamodeling-_using-_power-bi/
├── datasets/
│   ├── 01_first_dashboard/             # Starter datasets (customers, orders)
│   ├── 02_connection_types/            # Multi-source data (CSVs, JSON, SQL, Excel)
│   │   └── MonthlySales/               # 12-month sales data (Jan - Dec)
│   ├── 03_power_query/                 # Data cleansing and transformation files
│   ├── 04_data_modeling/               # Dimension and Fact tables for Star Schema
│   └── 05_project_clean_model/         # Raw messy tables for model cleaning
├── powerbi_files/                      # Completed Power BI (.pbix) templates
│   ├── My First Dashboard.pbix
│   ├── Data Cleaning (Power Query).pbix
│   ├── Data Modeling.pbix
│   └── Project Clean Model.pbix
└── project_nightmare_datamodel/        # Complex data modeling challenge
    ├── dataset.xlsx
    └── project_datamodel.pbix
```

---

## 🎯 Modules & Topics Covered

### 1. 📊 My First Dashboard (`01_first_dashboard`)
- Importing tabular data from CSV files.
- Basic visual formatting, KPI cards, and bar charts.
- Setting up interactive cross-filtering and slicers.

### 2. 🔌 Connection Types & Data Sources (`02_connection_types`)
- Connecting to diverse data sources:
  - Excel Workbooks (`masterdata_extended_1.xlsx`)
  - Folders of CSVs (`MonthlySales/` - Automated folder ingestion)
  - Semi-structured JSON (`product_new_prices.json`)
  - Unstructured logs (`events_log.txt`)
  - Relational Database scripts (`sql_server_database.sql`)
- Understanding DirectQuery, Import, and Dual modes.

### 3. 🧹 Power Query Data Transformation (`03_power_query`)
- Combining and appending multi-period data (`orders_jan.csv` + `orders_feb.csv`).
- Unpivoting monthly matrix summaries into normalized columnar models.
- Handling missing data, type casting, custom columns, and conditional logic.

### 4. 📐 Data Modeling & Star Schema (`04_data_modeling`)
- Designing optimal analytical models:
  - **Dimension Tables:** `dim_customer`, `dim_product`, `dim_date`, `dim_store`, `dim_manager`, `dim_region`, etc.
  - **Fact Tables:** `fact_sales`, `fact_orders`, `fact_budget`, `fact_sales_monthly`.
- Establishing 1-to-many (`1:*`) single-direction relationships.
- Avoiding bi-directional filters and circular dependencies.
- Implementing Row-Level Security (RLS) with `security.csv`.

### 5. 🧼 Project Clean Model & Challenge (`05_project_clean_model` & `project_nightmare_datamodel`)
- De-normalizing flat multi-tab spreadsheets into clean Dimensional Models.
- Resolving common modeling issues (many-to-many, ambiguous paths, grain mismatches).
- Real-world capstone modeling challenge with complete `.pbix` solution.

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/beerellamanikanta-eng/datamodeling-_using-_power-bi.git
   ```

2. **Open Power BI Desktop:**
   - Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
   - Open any `.pbix` file inside the `powerbi_files/` or `project_nightmare_datamodel/` folder.

3. **Re-link Data Source Paths (if required):**
   - Click `Home > Transform Data > Data source settings`.
   - Update the file path to point to your local `datasets/` folder.

---

## 👤 Author

- **GitHub Profile:** [@beerellamanikanta-eng](https://github.com/beerellamanikanta-eng)
- **Repository:** [datamodeling-_using-_power-bi](https://github.com/beerellamanikanta-eng/datamodeling-_using-_power-bi)
