📊 Vendor Performance Analysis

📌 Introduction

Efficient vendor management plays a crucial role in supply chain and business performance. This project focuses on analyzing vendor and brand-level performance using sales and inventory data. The analysis goes beyond just identifying vendors with high or low sales—it also captures inefficiencies within individual brands supplied by a vendor.

The ultimate goal is to help businesses minimize capital blockage, optimize inventory, and make data-driven decisions for procurement and vendor negotiations.

🏷️ Problem Statement

Businesses often face challenges when evaluating vendor performance solely at an aggregate level. A vendor with overall good performance might still have certain brands that contribute heavily to unsold inventory and locked capital. Ignoring these hidden inefficiencies leads to:

Poor inventory turnover

Increased holding costs

Ineffective vendor negotiations

Hence, a granular analysis is necessary to capture performance at both vendor and brand levels.

🔍 Approach & Methodology

Data Cleaning & Preprocessing

Handling missing or inconsistent values

Standardizing column formats

Preparing structured datasets for analysis

Exploratory Data Analysis (EDA)

Grouping and aggregating sales/unsold items data by vendor and brand

Computing key metrics like Total Unsold Items and Total Amount Locked

Identifying outliers and anomalies

Performance Metrics

Total Unsold Items → measures the quantity of products left unsold.

Total Amount Locked → monetary value stuck in unsold inventory.

Vendor & Brand Performance Comparison → highlights both strong and weak contributors.

Visualization

Matplotlib & Seaborn used for plots and charts

Clear visual representation of vendor-wise and brand-wise trends

Optional integration with Power BI dashboards for interactive exploration

💡 Key Insights

Vendors with overall negative unsold inventory (good performance) may still have specific brands underperforming.

Certain vendors disproportionately contribute to capital lock-up, affecting cash flow.

Brand-level inefficiencies often remain hidden unless analyzed separately from vendor aggregates.

Actionable insights help businesses in:

Deciding which vendors to retain or negotiate with

Identifying underperforming brands to reduce losses

Improving inventory allocation

🛠️ Tools & Technologies

Python: pandas, numpy, matplotlib, seaborn

Jupyter Notebook: interactive coding & documentation

Power BI (optional): dashboard creation for better storytelling

🚀 Applications

Procurement Optimization: Strengthen vendor negotiations with data-backed insights.

Inventory Management: Minimize capital blockage in unsold items.

Business Intelligence: Provide decision-makers with vendor and brand-specific performance analytics.

Supply Chain Efficiency: Improve turnover ratio and reduce costs.

📌 Future Work

Build a predictive model to forecast vendor/brand performance trends.

Automate data pipeline for real-time vendor analysis.

Develop a dashboard-first approach (Power BI/Tableau/Streamlit) for better stakeholder usability.

Incorporate profitability analysis in addition to unsold inventory metrics.

📂 Repository Structure
├── data/                # Raw and cleaned datasets (if shareable)  
├── notebooks/           # Jupyter Notebooks with analysis  
├── visuals/             # Plots, charts, and reports  
├── README.md            # Project documentation  
└── requirements.txt     # Python dependencies  

🙌 Acknowledgment

This project was developed as part of a learning and exploratory exercise to apply data analytics techniques to real-world business problems.
