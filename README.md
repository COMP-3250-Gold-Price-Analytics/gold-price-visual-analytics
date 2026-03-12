# Visual Analytics of Gold Price Trends Over the Past Decade
**Course:** COMP.3250 - Data Analytics I  
**Professor:** Dr. Andreas S. Maniatis  
**Institution:** University of Windsor

## 📢 Project Status Update
**[View Live Project Status Report](https://comp-3250-gold-price-analytics.github.io/gold-price-visual-analytics/Project%20Status%20Report/Project%20Status%20Report.html)** *This report provides a real-time overview of our technical progress, completed Hive milestones, and upcoming development phases.*

## 👥 Team Members
* **Aakanksha Mandal** (Project Coordinator & Technical Lead)
* **Abhishek Chaparala** (Project Organization Support)
* **Brett Adams** (Visualization Development Lead)

## 📊 Project Overview
This project focuses on identifying trends, patterns, and economic factors influencing gold price fluctuations from 2016–2026. Using Power BI and the Data Analytics Lifecycle (DAL) methodology, we transform raw historical data into actionable visual insights.

## 📂 Data Sources
This project utilizes a multi-source dataset strategy to ensure a comprehensive 10-year view of gold price behavior.

1. **Primary Historical Dataset:** [Gold Price Analysis - 10 Year Historical Data (Kaggle)](https://www.kaggle.com/datasets/sanaijlalshahrukh/gold-price-analysis-10-year-historical-data)
   * **Purpose:** Provides the core daily trading metrics (Open, High, Low, Close, Volume) used for long-term trend identification.
   * **Scope:** 2016 – 2026.

2. **Supplementary Market Data:** [Yahoo Finance - COMEX Gold Futures (GC=F)](https://finance.yahoo.com/quote/GC%3DF/history)
   * **Purpose:** Used for cross-referencing and validating Adjusted Close values and recent market volatility against COMEX futures standards.
   * **Format:** Time-series daily intervals.

## 🛠️ Tech Stack
* **Visual Analytics:** Microsoft Power BI
* **Data Handling:** Power Query & DAX
* **Version Control:** GitHub
* **Project Management:** Hive

## 📂 Repository Structure
* `/data`: Contains raw and cleaned datasets (CSV).
* `/dashboards`: The .pbix Power BI files.
* `/docs`: Project proposal, final report, and certifications.
* `/scripts`: Any auxiliary Python or Excel validation scripts.

## 🚀 How to Run
1. Clone the repository.
2. Open the `.pbix` file in `/dashboards` using Power BI Desktop.
