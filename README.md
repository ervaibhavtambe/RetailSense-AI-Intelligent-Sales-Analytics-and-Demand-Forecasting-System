# RetailSense AI: Intelligent Sales Analytics and Demand Forecasting System

## 📌 Project Overview

**RetailSense AI** is an AI-powered retail analytics platform designed to help retail businesses understand their sales data and make data-driven decisions.

The system processes retail transaction data and provides three major functionalities:

* 📊 **Sales Analytics** – Analyze sales trends, products, regions, and business performance.
* 👥 **Customer Segmentation** – Identify valuable and at-risk customers using **RFM Analysis and K-Means Clustering**.
* 📈 **Demand Forecasting** – Predict future product demand using **ARIMA and Prophet**.

The results are presented through an **interactive dashboard**, making complex data easy to understand.

## 🎯 Objectives

* Automate data ingestion and cleaning.
* Analyze retail sales trends.
* Identify valuable and at-risk customers.
* Perform customer segmentation using RFM + K-Means.
* Forecast future product demand using ARIMA/Prophet.
* Provide an interactive dashboard.
* Support portable deployment using Docker.

## 🏗️ System Workflow

```text
Retail Transaction Data
          ↓
   Data Pre-processing
          ↓
        ETL
          ↓
     PostgreSQL
          ↓
   ┌──────┼─────────┐
   ↓      ↓         ↓
Analytics Customer  Demand
          Segmentation Forecasting
   ↓      ↓         ↓
   └──────┼─────────┘
          ↓
       FastAPI
          ↓
    Interactive Dashboard
```

## 🧠 Technologies Used

| Technology        | Purpose                      |
| ----------------- | ---------------------------- |
| Python            | Main programming language    |
| Pandas            | Data processing and cleaning |
| PostgreSQL        | Database                     |
| SQL               | Database operations          |
| Scikit-learn      | Machine Learning             |
| K-Means           | Customer segmentation        |
| RFM               | Customer value analysis      |
| ARIMA             | Demand forecasting           |
| Prophet           | Time-series forecasting      |
| FastAPI           | Backend API                  |
| Streamlit / React | Frontend dashboard           |
| Plotly / Recharts | Data visualization           |
| Docker            | Deployment                   |
| Docker Compose    | Multi-container management   |
| Git & GitHub      | Version control              |

## 📊 Main Features

### 1. Sales Analytics

* Sales trend analysis
* Product/category analysis
* Regional performance
* Business insights

### 2. Customer Segmentation

The system uses **RFM Analysis**:

* **Recency** – How recently the customer purchased
* **Frequency** – How often the customer purchases
* **Monetary** – How much the customer spends

K-Means clustering is then used to group customers into meaningful segments such as **Champions, Loyal, At-Risk, and Lost**.

### 3. Demand Forecasting

Historical sales data is used to predict future demand using:

* **ARIMA**
* **Prophet**

Forecast performance can be evaluated using **MAPE and RMSE**.

### 4. Interactive Dashboard

The dashboard can display:

* Sales performance
* Sales trends
* Customer segments
* Future demand forecasts
* Charts and KPI information

## 🚀 Future Scope

* Real-time POS and e-commerce integration
* LSTM / BiLSTM forecasting
* Personalized product recommendations
* Weather, holiday and promotion data integration
* Natural-language analytics
* Multi-store support
* Automated model retraining using Airflow

## ⚠️ Current Limitations

* Mainly depends on historical data.
* Direct live POS integration is not currently included.
* External market data is not currently included.
* Forecast accuracy depends on data quality.
* Advanced deep-learning models are not currently included.

## 👥 Team

* **Vaibhav Dattatray Tambe**
* **Aditya Gorakhnath Unde**
* **Rupesh Ramnath Patare**
* **Mehul Praful Patil**

**Department of Artificial Intelligence & Data Science**
**Amrutvahini College of Engineering, Sangamner**

## 📌 Project Status

🚧 **Project under development**

---
