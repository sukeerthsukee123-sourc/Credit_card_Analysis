# 💳 Credit Card Analytics & Performance Dashboard

An end-to-end business intelligence and data analytics solution that processes high-volume transaction data using Tableau's high-performance `.hyper` data engine. This project translates raw credit infrastructure parameters into actionable, executive-level insights covering revenue optimization, dynamic demographic spend patterns, and credit risk mitigation.

---

## 🎯 Executive Objectives

*   **Financial Performance Tracking:** Monitor structural revenue streams (interest collection, swipe fees, annual fees) against quarterly targets.
*   **Customer Segmentation Architecture:** Map spending volume and transactional velocity across diverse consumer demographics, income brackets, and professional sectors.
*   **Credit Risk Triage:** Identify anomalies and escalating default patterns by analyzing delinquency rates and card utilization matrixes.

---

## 🛠️ Infrastructure & Tech Stack
*   **Visualization Layer:** `Tableau Desktop` / `Tableau Public`
*   **Data Pipeline Engine:** `Tableau Hyper API` (High-performance SQL-based analytical database engine)
*   **Data Structure:** Relational transactional ledger parameters merged with historical customer demographic master tables.

---

## 📈 Dashboard Architecture & KPIs

The included `.twb` workbook compiles a multidimensional financial story categorized into three core analytical vectors:

### 💰 1. Revenue & Performance Matrix
*   **Gross Transaction Volume (GTV):** Total currency throughput across the entire merchant network.
*   **Interest Income Capture:** Revenue derived from revolving credit balances, segmented by tier ratings.
*   **Fee Structure Analysis:** Granular analysis of transaction-level margins, annual subscription retention, and late fee velocity.

### 👥 2. Strategic Demographic Spend Mapping
*   **Utilization by Category:** Real-time visibility into shifting wallet shares across high-volume categories (e.g., Bills, Entertainment, Fuel, Grocery).
*   **Age & Income Cohorts:** Spending behaviors cross-referenced by generational groups and economic tiers to pinpoint high-value customer acquisitions.
*   **Card Tier Distribution:** Market penetration and swipe velocity variances across Blue, Silver, Gold, and Platinum card structures.

### ⚠️ 3. Credit Risk & Operations
*   **Delinquency Rate Tracking:** Early-warning indicators classifying active accounts by aging buckets (30/60/90+ days past due).
*   **Credit Utilization Ratio (CUR):** Programmatic alerts tracking customers with elevated risk profiles (CUR > 70%).

---

## 🚀 Deployment Instructions

### Prerequisites
*   Tableau Desktop (Version 2020.4 or newer recommended to support hyper engine integration).

### Execution Steps
1.  Clone this repository locally.
2.  Keep the `.hyper` data extraction files in their relative directories (`Data/TableauTemp/`).
3.  Open `Dashboard - Credit Card Analytics.twb` using Tableau Desktop.
4.  If prompted for a missing data source, redirect the connection path to the localized path of the extraction files.

---
*Disclaimer: All financial data, structural metrics, and consumer details contained within this extraction setup are synthetically generated or anonymized for business simulation mapping purposes.*
# Credit_card_Analysis
A dynamic Tableau dashboard and Hyper data engine pipeline analyzing card issuer economics, transaction trends, and consumer credit risk profiles.
