# US Regional Sales & Product Performance Analytics 📊🌎

An end-to-end Data Analytics project designed to uncover regional sales dynamics, distribution channel efficiencies, and product profitability across the United States. This project bridges deep statistical Exploratory Data Analysis (EDA) using Python with executive-level interactive reporting via Power BI.

---

## 🎯 Project Overview

In multi-channel retail and wholesale operations, understanding the interplay between product price bands, regional preferences, and channel costs is critical to preserving margins. This project analyzes a complex transactional dataset to:
1. **Identify Seasonality & Spending Tiers:** Map consumer behavior and transaction spikes.
2. **Optimize Channels:** Evaluate revenue versus profit margins across Wholesale, Export, and Distributor networks.
3. **Geographic Targeting:** Pinpoint high-performing states and customer accounts to maximize logistical ROI.

---

## 🧠 Exploratory Data Analysis (EDA) Highlights

Before building the presentation layer, extensive data engineering and statistical analysis were performed in Python. Key analyses included:

* **Sales & Seasonality Trends:** Analyzed the monthly sales velocity over time to map seasonal revenue peaks.
* **Product Performance Tiers:** Isolated the **Top 10 Products by Revenue** and cross-referenced them against the **Top 10 Products by Average Profit Margin** to spot volume vs. margin anomalies.
* **Distribution Channel Breakdown:** Evaluated performance metrics across Wholesale, Export, and Distributor networks.
* **Pricing & Margin Distribution:** Built unit price distribution plots and plotted **Profit Margin % vs. Unit Price** to spot ideal pricing sweet spots.
* **Geographic Matrix Analysis:** Analyzed sales across US regions, breaking down the top 10 states by both total revenue and cumulative order counts.
* **Statistical Correlation:** Generated a correlation heatmap matrix focusing on the top and bottom 10 states by revenue to identify volume drivers.

---

## 📂 Repository Structure

The project repository follows a flat architecture with raw data, cleaning logs, and presentation assets readily available:

```text
├── LOGO.jpg                                       # Project logo / theme asset
├── MAIN DASH.pbix                                 # Interactive Power BI dashboard file
├── README.md                                      # Project documentation
├── Regional Sales Dataset.xlsx                    # Original raw dataset
├── Regional_Sales_Analysis(EDA Exported).csv      # Cleaned and processed data exported after EDA
├── Regional_Sales_Analysis.ipynb                  # Jupyter Notebook containing Python EDA & visualizations
├── file.csv                                       # Auxiliary data file
