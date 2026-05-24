# Data Analytics Dashboard 

## 📌 Overview
This repository contains a Microsoft Power BI project (`DataAnalytics.pbix`) focused on data transformation, analytical modeling, and interactive visualization. The dashboard is designed to provide clear, actionable insights through a refined user interface and automated data pipelines.

## 🛠️ Technology Stack
* **Business Intelligence:** Microsoft Power BI Desktop
* **Data Processing:** Power Query (M)
* **Analytical Engine:** DAX (Data Analysis Expressions)
* **Data Sources:** Google Sheets / Cloud-based CSVs

## ⚙️ Core Features & Architecture

### 1. Data Extraction & Transformation (ETL)
* **Live Connections:** Integrated directly with Google Sheets for streamlined data ingestion.
* **Automated Refreshes:** Configured scheduled data refreshes to ensure dashboard metrics remain up to date.
* **Power Query Processing:** Cleaned and transformed raw data, including the splitting and parsing of complex comma-separated values into structured columns.

### 2. Data Modeling & DAX
* **Dimensional Modeling:** Established a robust relational data model optimized for filtering and cross-filtering.
* **Custom Date Dimension:** Implemented a dedicated Date table using DAX to support complex time-intelligence calculations (e.g., Year-to-Date, Month-over-Month).
* **Measures:** Authored custom DAX expressions to aggregate data accurately and handle dynamic context transitions.

### 3. Visualizations & UI/UX
* **KPI Tracking:** Utilized Card visualizations to highlight high-level metrics at a glance.
* **Trend Analysis:** Deployed custom-formatted bar charts (with adjusted widths and bespoke titles) to display categorical comparisons and historical trends.
* **Interactive Elements:** Implemented slicers and interactive chart filtering to allow users to drill down into specific data segments.

## 🚀 How to Use

1. **Prerequisites:** Ensure you have the latest version of [Power BI Desktop](https://powerbi.microsoft.com/desktop/) installed.
2. **Clone the Repository:**
   ```bash
   git clone https://github.com/vindyacharuni/data_visualization.git
