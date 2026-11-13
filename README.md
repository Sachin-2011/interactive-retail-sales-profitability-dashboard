# Retail Sales & Profitability Dashboard (Microsoft Excel)

An interactive executive dashboard built in Microsoft Excel to analyze **1,951 retail order records** across shipping modes, customer segments, product categories, and U.S. regions—separating top-line sales volume from true bottom-line profitability.

---

## 📌 Project Overview

High sales numbers don't always guarantee healthy margins. Rather than relying on static spreadsheets, this project transforms raw order-level data into a dynamic, macro-free self-service Business Intelligence (BI) tool. By wiring four dedicated Pivot Tables to interactive Slicers, stakeholders can slice regional performance, fulfillment reliance, and product-level profit leaks in seconds.

<img width="2206" height="993" alt="IMG20261105133319" src="https://github.com/user-attachments/assets/38361d8f-5b1a-4940-9501-f0a20795374a" />

---

## 📊 Key Analytical Findings

* **Fulfillment Mix:** Out of **1,951 total orders**, **Regular Air** handles **73.6%** (1,436 orders), compared to **14.1%** via **Delivery Truck** (275 orders) and **12.3%** via **Express Air** (240 orders).
* **Top-Performing States:** **California** leads state profitability at **$37,421.96**, followed by **Texas** (**$28,078.85**), **New York** (**$27,611.94**), **Ohio** (**$23,410.84**), and **Oregon** (**$17,931.04**).
* **Top-Performing Cities:** **Washington** leads city-level returns (**$11,677.36**), ahead of **Thornton** (**$9,300.34**) and **New City** (**$9,243.26**).
* **Major Margin Leaks:** Just three underperforming products account for **-$51,169.72** in cumulative losses:
  1. *Polycom ViewStation™ ISDN Videoconferencing Unit* (`-$27,621.25`)
  2. *Product 5165* (`-$12,548.95`)
  3. *Okidata Pacemark 4410N Wide Format Dot Matrix Printer* (`-$10,999.53`)

---

## 🛠️ Tools & Methodology

* **Microsoft Excel:** Core analytical engine and dashboard canvas.
* **Data Modeling & Aggregation:** Structuring raw order records into multi-dimensional summaries without duplicating source tables.
* **Pivot Tables & Shared Pivot Caches:** Building four linked Pivot Tables (`Shipment Mode`, `Top 5 Profitable States`, `Top 10 Profitable Cities`, `Top 3 Least Profitable Products`).
* **Interactive Slicers & Cross-Filtering:** Connecting `Ship Mode`, `Customer Segment`, and `Product Category` Slicers across all charts for instant one-click filtering.
* **Data Cleaning & Validation:** Standardizing geographic hierarchies, shipping categories, and financial fields (`Sales`, `Profit`).
* **KPI & Metric Engineering:** Pairing volume (`Count of Sales`) with margin (`Sum of Profit`) to expose hidden profit drains.
* **Exploratory Data Analysis (EDA) & Outlier Ranking:** Isolating top geographic profit hubs alongside bottom-performing SKUs.
* **Executive Dashboard Design:** Designing a clean, scannable visual layout without VBA/macros for seamless cross-device compatibility.

---

## 📂 Repository Structure

```text
├── Dashbaord Analysis.xlsx   # Complete Excel workbook (Pivot Tables + Interactive Dashboard)
├── dashboard-preview.png     # Screenshot of the interactive dashboard view
└── README.md                 # Project documentation and key insights

🚀 How to Use
Download Dashbaord Analysis.xlsx and open it in Microsoft Excel (Desktop or Excel for the Web).

Navigate to the Dashboard worksheet.

Click any filter button inside the Ship Mode, Customer Segment, or Product Category Slicers to dynamically update all four charts.

Click the Clear Filter icon in the top-right corner of any slicer to reset the view.

👤 Author
Sachin Rajak

Data Analyst | Business Intelligence · SQL · Excel · Power BI · Google Cloud Data Analytics


*(Tip: Save a high-resolution PNG screenshot of your `Dashboard` tab as `dashboard-preview.png` i
