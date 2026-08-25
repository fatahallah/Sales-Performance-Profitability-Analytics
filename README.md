# 📊 Sales Performance & Profitability Analytics (Power BI)

## 📌 Executive Summary
An end-to-end business intelligence solution developed to evaluate sales performance, profit margins, regional target achievements, and product-level efficiency. This interactive two-page dashboard translates raw ERP data into actionable strategic insights for executive decision-making.

---

## 📁 Repository Structure & Datasets
This repository includes all raw datasets, transformation models, and the final interactive report:
* 📄 **Raw Data Files (`.xlsx` / `.csv`):** Original sales records, product catalogs, customer segments, sales rep performance logs, and regional targets.
* 📊 **Power BI Report (`.pbix`):** Full data model, DAX measures, and interactive visuals.
* 🖼️ **Visual Documentation:** High-resolution screenshots of the executive and detailed analytical views.

---

## 🛠️ Tech Stack & Methodology
* **Data Ingestion & Exploration:** Reviewed raw sales, product, regional target, and customer datasets in **Microsoft Excel**.
* **Data Transformation (ETL):** Utilized **Power Query Editor** to adjust data types, handle orphan/null records, apply string trimming, and validate primary-foreign keys.
* **Data Modeling:** Built an optimized **Star Schema** establishing clean `1-to-Many` relationships between Fact and Dimension tables.
* **Calculations:** Formulated custom **DAX** metrics including `Total Sales`, `Total Profit`, `Profit Margin %`, `AOV`, and `Target Achievement`.
* **UI/UX Design:** Implemented a unified top navigation header, consistent color schemes, card margins, and synchronized regional slicers across pages.

---

## 📸 Dashboard Screenshots

### Page 1: Executive Overview
![Executive Overview](Executive_Overview.png)

### Page 2: Detailed Analytics
![Detailed Analytics](Detailed_Analytics.png)

---

## 💡 Key Business Insights

* **Product Category Performance:** Smartphones and Monitors drive the highest revenue volume. Low-margin categories like Accessories (~12% margin) require contract renegotiations or bundling strategies.
* **Seasonality Trends:** Identified a significant revenue spike in **May**, driven by seasonal campaign traction.
* **Sales Rep & Customer Segmentation (80/20 Rule):** The top 20% of sales representatives generate >65% of total revenue. Corporate/Enterprise clients exhibit an **18% higher Average Order Value (AOV)** than retail customers.
* **Data Governance Audit:** Isolated unmapped orphan records resulting in `(Blank)` categories, triggering recommendations for ERP-level validation enforcement.

---

## 👤 Author
**Mr. Fathallah Saied**  
*Data Analyst & BI Developer*
