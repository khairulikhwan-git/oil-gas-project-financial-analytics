# 📊 Oil & Gas Corporate Performance & Financial Variance Analytics

## 🎯 Executive Summary
This project provides an enterprise-level Power BI reporting solution tracking operational quality, audit compliance, and financial variance across major energy sector projects (BP, Petronas, Shell).

By combining **Operational Quality Metrics** (NCR tracking, welding repair rates) with **Financial Governance** (Plan vs. Actual cost & revenue variance), this dashboard enables executives to pinpoint operational bottlenecks and budget overruns in real time.

---

## 📸 Dashboard Previews

### 1. Project Quality & Audit Performance Dashboard
![Project Quality Dashboard](screenshots/Monthly_Project_Performance_Graph.png)
![Project Quality Dashboard](screenshots/Monthly_Project_Performance_Report.png)

### 2. Financial Plan vs. Actual Variance Analysis
![Financial Variance Dashboard](screenshots/Plan_vs_Actual_Financial_Report.png)

---

## 💡 Key Business Insights

### 🛠️ 1. Quality & Risk Metrics (Operational)
* **Non-Conformance Report (NCR) Spikes:** Overdue NCR closure rates peaked heavily in **April and May at 40.82%**, far exceeding the corporate threshold target of `< 10%`.
* **Welding Repair Rate (WRR):** Process Piping welding repair rates surged in **July (33.23%)** and **August (31.07%)**, signaling quality control issues during peak fabrication phases.
* **Audit Compliance:** PMT External Audits maintained a **100% schedule compliance** rate across evaluated project cycles.

### 💰 2. Financial & Revenue Variance (Corporate)
* **Revenue Outperformance:** Actual monthly revenue significantly exceeded planned forecasts during **May (RM11.2M actual vs. RM6.6M plan)**, **June (RM10.3M vs. RM4.0M)**, and **July (RM9.8M vs. RM2.6M)**.
* **Cost Variance Analysis:** Identified operational budget discrepancies during Q2 and Q3, enabling leadership to reallocate capital effectively.

---

## 🛠️ Tech Stack & Power BI Features Implemented
* **Tool:** Power BI Desktop
* **Data Modeling:** Relational Star Schema connecting project timelines, metrics, and financials.
* **DAX Formulas:** Custom measures created for `% Overdue NCR Closure`, `Cumulative WRR %`, and `Plan vs. Actual Variance`.
* **Visualizations:** Dual-axis combo charts, multi-row KPI cards, dynamic slicers (Project & Month filtering), and conditional formatting alerts.

---

## 🚀 How to View
1. Download the `.pbix` files from the `dashboards/` directory.
2. Open using **Power BI Desktop**.
3. Use the top slicers to filter dynamically between **BP Petroleum**, **Petronas**, and **Shell** performance metrics.
