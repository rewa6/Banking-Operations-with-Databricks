# Financial Banking Data Analysis

# Overview

This project focuses on analyzing financial banking data using Databricks, Power BI, and Azure Data Lake Storage Gen2. It implements a robust data pipeline for ingestion, transformation, anomaly detection, and visualization, along with an interactive UI for advanced analytics.

# Architecture

**Data Storage:** Azure Data Lake Storage Gen2 for secure and scalable data storage.

**Data Transformation:** Databricks with Delta Live Tables (DLT) pipeline for ETL and data quality checks.

**Analytics & Visualization:** Power BI dashboards for business insights.

**Machine Learning:** Anomaly detection using Isolation Forest for identifying unusual transactions.

**UI Layer:** Streamlit-based application with:

Chatbot for user queries.

Root Cause Analysis for anomalies.

Counterfactual Analysis for scenario-based insights.




# Key Features

**Data Pipeline:**

Ingest raw banking data from Azure Data Lake.
Transform and clean data using Databricks DLT.


**Anomaly Detection:**

Isolation Forest model to detect fraudulent or unusual patterns.


**Visualization:**

Interactive Power BI dashboards for KPIs and trends.


**Streamlit UI:**

Chatbot for conversational analytics.
Root Cause Analysis for anomaly investigation.
Counterfactual Analysis for “what-if” scenarios.




# Tech Stack

**Cloud:** Azure Data Lake Storage Gen2

**Data Engineering:** Databricks, Delta Live Tables

**Visualization:** Power BI

**Machine Learning:** Scikit-learn (Isolation Forest)

**UI:** Streamlit

**Languages:** Python, SQL, Pyspark


# Setup Instructions
**Prerequisites**

Azure account with Data Lake Gen2

Databricks workspace

Power BI Desktop

Python 3.8+

Required Python libraries:
pip install streamlit scikit-learn pandas numpy


# Steps

**Clone the repository:**
git clone https://github.com/rewa6/Banking-Operations-with-Databricks.git

Configure Azure Data Lake credentials in Databricks.

Deploy DLT pipeline in Databricks for data transformation.

Train Isolation Forest model and save artifacts.

Run Streamlit UI:
streamlit run app.py

Connect Power BI to transformed data for dashboard visualization.


# Future Enhancements

Integration with Azure Synapse for advanced analytics.

Real-time anomaly detection using streaming data.

Enhanced chatbot with LLM-based responses.
