# 🚀 Customer Churn & Retention Analytics  
**PostgreSQL · SQL · Power BI · Python**

> *An end-to-end, business-driven churn monitoring system designed to identify revenue at risk and simulate retention impact.*

---

## 📌 Project Overview

This project builds a **full customer churn & retention analytics pipeline** using **PostgreSQL and SQL**, with insights visualized in **Power BI**.

The objective is **not predictive modeling**, but **business decision support**:
- Identify **high-risk customer segments**
- Quantify **monthly & annual revenue exposure**
- Simulate **retention strategies** and their financial impact

The project is designed specifically for **Data Analyst / Business Analyst internship roles** and mirrors how churn analysis is handled in real companies.

---

## 🧠 Business Questions Answered

- How many customers are at **high churn risk**?
- Which **plans and acquisition channels** contribute most to revenue?
- How much **revenue is exposed** to churn each month?
- What is the **financial upside** of improving retention?

---

## 📊 Dataset

Synthetic but **business-realistic** data generated to simulate a subscription-based company.

| Component | Scale |
|---------|------|
| Customers | **10,000** |
| Time Span | Up to **24 months** |
| Usage Records | **200K+ rows** |
| Tables | customers, subscriptions, usage_metrics, payments, support_tickets |

Synthetic data was chosen to:
- Control schema realism  
- Avoid privacy issues  
- Focus on **analytics logic and business impact**

---

## 🔍 Methodology

### 1️⃣ Data Generation & Storage
- Generated customer, subscription, usage, payment, and support data
- Loaded into a **relational PostgreSQL database**
- Designed for **analytics-friendly joins and KPIs**

### 2️⃣ SQL Analytics & Risk Scoring
- Aggregated behavioral, payment, and support signals
- Engineered a **churn risk score** using SQL
- Segmented customers into **Low / Medium / High risk**

### 3️⃣ Revenue Impact Analysis
- Calculated **monthly revenue at risk**
- Identified **high-risk MRR exposure**
- Simulated retention uplift scenarios

### 4️⃣ Visualization (Power BI)
- Built an executive-style dashboard for monitoring churn and revenue exposure

---

## 📈 Key Results

| Metric | Value |
|------|------|
| High-risk Monthly Revenue (Risk Score ≥ 2) | **$108,623.78** |
| Retention Uplift Simulated | **15%** |
| Monthly Revenue Saved | **$16,293.57** |
| **Annual Revenue Saved** | **$195,522.80** |

These metrics demonstrate how even small improvements in retention can generate significant financial impact.

---

## 📊 Power BI Dashboard

The Power BI dashboard provides an executive overview of churn risk and revenue exposure.

### Included Visuals:
- KPI cards (Customers, Revenue, Churn Rate)
- Revenue by risk category
- Customer distribution by plan type
- Revenue by acquisition channel
- Geographic customer distribution
- High-risk customer segmentation

📁 Dashboard file:  
- `Churn-retention-dashboard.pbix`  
*(Power BI file included in the repository)*

📸 Preview images available in `/assets`

---

## 🛠 Tools & Technologies

- **PostgreSQL** – relational database & analytics
- **SQL** – aggregations, joins, risk scoring, KPIs
- **Python** – data generation & loading
- **Power BI** – dashboard & visualization
- **VS Code** – development environment

---

## ▶️ How to Run the Project

1. Generate data using notebooks in `/notebook`
2. Load data into PostgreSQL
3. Run SQL analysis in `sql/queries.sqlbook`
4. Open `Churn-retention-dashboard.pbix` in Power BI

---

## 📌 Key Takeaways

- Built a realistic **end-to-end analytics project**
- Demonstrated **business-oriented SQL thinking**
- Quantified churn impact in **financial terms**
- Delivered insights using **professional dashboards**

---

## 👤 Author

**Fizuli Hasanov**  
Aspiring Data Analyst | SQL · Analytics · Business Intelligence
