# 🏅 Olympic Data Analytics using Microsoft Azure

This project demonstrates a complete end-to-end **ETL pipeline** for analyzing Olympic data using various services from the **Microsoft Azure ecosystem**. It includes data ingestion, processing, storage, querying, and visualization.

---

## 🔧 Tools & Services Used

- **Azure Data Lake Storage** – For storing raw and transformed data
- **Azure Data Factory** – For ingesting CSV files into the data lake
- **Azure Databricks (PySpark)** – For data processing and transformation
- **Azure Synapse Analytics** – For querying data using SQL
- **Power BI** – For data visualization and dashboarding
- **Azure Active Directory App Registration** – For secure mounting and authentication

---

## 🔄 Workflow Summary

1. Ingested raw `athletes.csv` using Azure Data Factory.
2. Mounted ADLS Gen2 in Azure Databricks using app credentials.
3. Processed and cleaned data using **PySpark** in Databricks notebooks.
4. Saved transformed data back to ADLS.
5. Imported transformed data into **Azure Synapse Analytics** as tables.
6. Executed SQL queries to generate insights (e.g., total medals, athlete counts).
7. Connected Power BI to Synapse to create interactive visual dashboards.

---

## 📊 Sample Analyses

- Top countries by number of gold medals
- Total number of athletes by country
- Average entries by gender per discipline

---

## 📈 Highlights

- Built a **scalable and modular ETL pipeline** using cloud-native Azure services.
- Performed real-time transformations using Spark in Azure Databricks.
- Delivered actionable insights through SQL queries and Power BI reports.

---

## 🚀 Future Enhancements

- Automate end-to-end pipeline and dashboard refresh
- Integrate real-time streaming data (e.g., with Azure Event Hubs)
- Add CI/CD for notebooks and deployment

---

Feel free to explore the notebooks and SQL queries included in this repo to learn more!
