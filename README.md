# Enterprise Data Warehouse for Business Intelligence

## 🚀 Data Warehouse and Analytics Project
Welcome to the **Enterprise Data Warehouse for Business Intelligence** repository! This project demonstrates a comprehensive data warehousing solution, covering data ingestion, transformation, modeling, and analytics.

---

## 📖 Project Overview
This project focuses on:

- **Data Architecture:** Implementing a **Modern Data Warehouse** using the **Medallion Architecture (Bronze, Silver, Gold layers).**
- **ETL Pipelines:** Extracting, transforming, and loading data from ERP and CRM source systems.
- **Data Modeling:** Designing optimized **star schema models** with fact and dimension tables.
- **Analytics & Reporting:** Developing SQL-based insights into **customer behavior, product performance, and sales trends.**

This repository serves as a **portfolio project** for professionals aiming to showcase expertise in:
- SQL Development
- Data Architecture
- Data Engineering
- ETL Pipeline Development
- Data Modeling
- Data Analytics

---

## 🛠️ Tools & Resources
All tools used in this project are **free**:

- **Datasets:** CSV files containing ERP and CRM data.
- **SQL Server Express:** Lightweight database server for hosting the data warehouse.
- **SQL Server Management Studio (SSMS):** GUI for managing and interacting with databases.
- **GitHub Repository:** Version control and collaboration.
- **Draw.io:** Designing data architecture, ETL workflows, and star schema models.
- **Notion:** Project management and documentation.
- **Notion Project Steps:** Access all project phases and tasks.

---

## 🚀 Project Requirements
### **Building the Data Warehouse (Data Engineering)**
**Objective:** Develop a modern **SQL Server** data warehouse to consolidate **sales data** for analytical reporting and business intelligence.

**Specifications:**
- **Data Sources:** Import data from **ERP and CRM** systems (CSV files).
- **Data Quality:** Cleanse and resolve data integrity issues before analysis.
- **Integration:** Combine both sources into a **user-friendly analytical data model.**
- **Scope:** Focus on the latest dataset (historization not required).
- **Documentation:** Provide a **clear data model** for business and analytics teams.

### **BI: Analytics & Reporting (Data Analysis)**
**Objective:** Develop **SQL-based analytics** to uncover:
- **Customer Behavior Trends**
- **Product Performance Insights**
- **Sales Metrics & Business Growth Analysis**

These insights support strategic decision-making by providing key business intelligence metrics.

---

## 🏗️ Data Architecture
This project follows the **Medallion Architecture**:

![Data Architecture](docs/data_architecture.png)

### **🔹 Bronze Layer:**
- Stores **raw** ERP and CRM data **as-is**.
- Data is ingested from CSV files into **SQL Server tables**.

### **🔸 Silver Layer:**
- Cleanses and standardizes data.
- Normalization and transformations for enhanced quality.

### **🏅 Gold Layer:**
- Business-ready **star schema models**.
- Optimized for reporting and analytics.

---

## 📂 Repository Structure
```
data-warehouse-project/
│
├── datasets/                           # Raw datasets (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # ETL pipeline workflow
│   ├── data_architecture.png           # Data warehouse architecture diagram
│   ├── data_catalog.md                 # Dataset field descriptions & metadata
│   ├── data_flow.drawio                # Data flow diagram
│   ├── data_models.drawio              # Star schema modeling
│   ├── naming-conventions.md           # Table & column naming standards
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for raw data ingestion
│   ├── silver/                         # Scripts for data cleansing & transformation
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts for data validation & quality checks
│
├── README.md                           # Project documentation and instructions
├── LICENSE                             # License information
├── .gitignore                          # Files ignored by Git
└── requirements.txt                    # Project dependencies
```

---

## 🛡️ License
This project is licensed under the **MIT License**. You are free to use, modify, and share this project with proper attribution.

---

## 📢 Contributions & Feedback
Feel free to contribute or provide feedback! Create a **pull request** or open an **issue** if you have suggestions or improvements.

---

🚀 **Happy Coding!** 🚀
