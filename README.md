# 🛍️ Retail Sales Insight System with Data Warehouse & BI Dashboard

A full-scale analytics and business intelligence project focused on retail sales data. This project demonstrates the complete data pipeline — from raw data ingestion and ETL, to dimensional modeling and interactive dashboards — to provide key insights into sales trends, profits, customer behavior, and product performance.

## 📌 Objectives

- Design and implement a star schema-based data warehouse
- Perform ETL using Python
- Load data into BigQuery/PostgreSQL
- Build interactive dashboards using Power BI
- Analyze trends, KPIs, and derive actionable insights

---

## 🧱 Architecture Overview

**Tech Stack:**
- **ETL:** Python (Pandas, SQLAlchemy)
- **Database:** BigQuery / PostgreSQL
- **Modeling:** Star Schema (Fact & Dimension tables)
- **Visualization:** Power BI
- **Data Source:** Superstore Sales Dataset

---

## 📂 Folder Structure

retail-sales-insight-bi/ │ ├── data/ # Sample or raw data files ├── etl/ # Python scripts for ETL processes ├── schema/ # Star schema design and table creation scripts ├── dashboard/ # Power BI reports (.pbix) or screenshots ├── analysis/ # EDA, forecasting, and advanced analytics ├── report/ # Report, documentation, or research paper ├── README.md # Project overview and usage instructions └── requirements.txt # Python libraries



---

## 📊 Key Features

- 📦 **ETL Pipeline**: Clean, transform, and load retail data
- 🧮 **Star Schema**: Design includes `Sales Fact` and dimensions for customer, product, order, date
- 📈 **Power BI Dashboards**:
  - Monthly Sales Trend
  - Profit by Region and Category
  - Top Products and Customers
  - KPI Cards and Filters
- 📡 **BigQuery Integration**: Efficient querying on cloud-based data warehouse

---

## 🚀 Getting Started

### 1. Clone this repo
git clone https://github.com/purnatummala/retail-sales-insight-bi.git
cd retail-sales-insight-bi
2. Install Python dependencies
pip install -r requirements.txt
3. Run the ETL script
python etl/etl_pipeline.py

📌 Future Enhancements
Automate ETL using Apache Airflow

Add ML forecasting for next-month sales

Integrate Google Looker Studio dashboards

Publish a research whitepaper based on this project

🧠 Author
Purna Chandrika
👩‍🎓 Master’s in Data Science, Florida State University
📧 purnatummala2003@gmail.com

