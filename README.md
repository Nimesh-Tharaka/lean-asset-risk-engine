# LEAN ASSET RISK ENGINE – HEAT MAP

A Power BI manufacturing analytics dashboard designed to monitor plant performance, operational risk, Lean health, and asset-related KPIs through an interactive risk heatmap.

The solution combines Power BI, DAX, Power Query, HTML/CSS-based custom visuals, and structured manufacturing KPI analysis to provide a centralized view of plant operational health.

---

## Dashboard Preview

![Uploading og.png…]()
<img width="1521" height="852" alt="Screenshot 2026-09-27 110055" src="https://github.com/user-attachments/assets/16f3428b-4334-4818-ab5f-f2fc59259a2a" />
<img width="1517" height="847" alt="Screenshot 2026-09-27 110022" src="https://github.com/user-attachments/assets/a4731c58-ec98-4ec9-a980-fbfc89063623" />
<img width="1521" height="850" alt="Screenshot 2026-09-27 110122" src="https://github.com/user-attachments/assets/1e3a3942-3b33-4868-b71a-68f593dceb60" />
---

## Overview

The Lean Asset Risk Engine is an interactive Power BI dashboard designed for manufacturing environments.

The dashboard transforms operational KPI data into an easy-to-understand risk intelligence interface.

It allows users to:

- Monitor plant performance
- Identify high-risk operational areas
- Compare subject-area performance
- Analyze KPI-level risk
- Track monthly changes
- Identify areas requiring attention
- View overall plant health
- Analyze operational and Lean performance

---

## Project Objective

The objective of this project is to create a centralized manufacturing performance dashboard that helps users understand operational risk across different plant areas.

The dashboard converts multiple manufacturing KPIs into:

- Risk levels
- Heatmap indicators
- Plant health scores
- Subject-area trends
- Impact driver rankings
- Overall plant status

This provides a single analytical view of manufacturing performance.

---

# Dashboard Features

## 1. Plant and Date Filters

The dashboard provides interactive filters for:

- Plant
- Year
- Month

Users can select a plant and reporting period to dynamically update the dashboard.

---

## 2. Overall Status

The Overall Status section provides a high-level view of the selected plant.

Risk levels are represented as:

| Risk Score | Status |
|------------|--------|
| 1 | Healthy |
| 2 | Moderate Risk |
| 3 | High Risk |

---

## 3. Risk Heat Map

The main dashboard component is the operational risk heatmap.

The heatmap displays 25 manufacturing KPIs across five major subject areas.

Each KPI is displayed with:

- Metric name
- Metric value
- Risk color
- Risk classification

### Risk Colors

| Color | Meaning |
|-------|---------|
| 🟢 Green | Healthy |
| 🟡 Yellow | Moderate |
| 🟠 Orange | High Risk |
| 🔴 Red | Highest Risk |

The colors are based on the calculated Risk Score rather than simply comparing raw KPI values.

---

# Subject Areas

The dashboard contains five major subject areas.

## 1. Profitability & Financial

This area monitors financial and profitability-related performance.

Metrics include:

- Sales NCL Rate %
- RMC NCL Rate %
- Earnings NCL Rate %
- Overhead NCL Rate %
- NP NCL Rate %

---

## 2. Capacity & Capability

This area monitors manufacturing capacity, utilization, and capability.

Metrics include:

- Loading Rate %
- Value Stream Contribution %
- Machine Utilization %
- MC Availability %
- Product Aging Rate %

---

## 3. Product Risk

This area focuses on product-related operational risks.

Metrics include:

- New-to-Program Ratio %
- Critical Parts NCL %
- No. of High-Risk Parts %
- Capa Parts Ratio %
- Process Compliance %

---

## 4. Operational & Delivery

This area monitors operational and delivery performance.

Metrics include:

- INB NCL Rate %
- NCL OTR %
- RM Ratio %
- Shipment Muda-Risk %
- OBR Muda-Risk %
- QH Muda-Scan %

---

## 5. Process Risk

This area monitors Lean process health and process-related performance.

Metrics include:

- Lean Health Score %
- Quality Process Health %
- Digital Adherence Health %
- Audit Closure

---

# KPI Summary

The dashboard uses 25 operational metrics.

| # | Metric |
|---:|---|
| 1 | Sales NCL Rate % |
| 2 | RMC NCL Rate % |
| 3 | Earnings NCL Rate % |
| 4 | Overhead NCL Rate % |
| 5 | NP NCL Rate % |
| 6 | Loading Rate % |
| 7 | Value Stream Contribution % |
| 8 | Machine Utilization % |
| 9 | MC Availability % |
| 10 | Product Aging Rate % |
| 11 | New-to-Program Ratio % |
| 12 | Critical Parts NCL % |
| 13 | No. of High-Risk Parts % |
| 14 | Capa Parts Ratio % |
| 15 | Process Compliance % |
| 16 | INB NCL Rate % |
| 17 | NCL OTR % |
| 18 | RM Ratio % |
| 19 | Shipment Muda-Risk % |
| 20 | OBR Muda-Risk % |
| 21 | QH Muda-Scan % |
| 22 | Lean Health Score % |
| 23 | Quality Process Health % |
| 24 | Digital Adherence Health % |
| 25 | Audit Closure |

---

# Risk Scoring

Each KPI is associated with a Risk Score.

| Score | Risk Level |
|---:|---|
| 1 | GREEN – Healthy |
| 2 | ORANGE – Moderate Risk |
| 3 | RED – High Risk |

The dashboard uses the Risk Score to determine the heatmap status.

This approach allows KPIs with different measurement directions to be analyzed consistently.

---

# Plant Health Radar

The Plant Health Radar provides a summarized view of the five major subject areas.

The radar compares:

- Current performance
- Target performance

The five radar dimensions are:

1. Profitability & Financial
2. Capacity & Capability
3. Product Risk
4. Operational & Delivery
5. Process Risk

This provides a high-level visual representation of plant health.

---

# Subject Area Trend Analysis

The trend section compares subject-area risk across reporting periods.

The dashboard displays:

- Previous month
- Current month
- Trend direction

Trend classifications include:

```text
IMPROVING
STABLE
WORSENING
