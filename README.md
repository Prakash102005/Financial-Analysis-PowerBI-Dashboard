# 💰 Finance Analysis Dashboard — Power BI

> Real-time insights into Transactions, Customers & Risk — an end-to-end financial analytics dashboard built in Power BI.

---

## 📌 Project Overview

**FinSight — Finance Analysis** is an interactive Power BI dashboard that delivers real-time visibility into financial transactions across customers, segments, geographies, and risk categories. Built for financial analysts and business stakeholders, the dashboard enables data-driven decision-making through dynamic KPIs, transaction-level drill-downs, and multi-dimensional segmentation.

---

## 🎯 Objective

- Monitor and track key financial KPIs — transaction volume, revenue, fees, and tax in real time
- Analyze transaction patterns across customer segments, states, and transaction types
- Identify risk signals through transaction status breakdown (Success / Failed / Pending)
- Enable stakeholder-level reporting with dynamic filtering by Year, Occupation, and Category

---

## 📊 Dashboard Pages

### Page 1 — Overview Analysis
A high-level executive summary of all financial activity.

| Visual | Description |
|--------|-------------|
| **KPI Cards** | Total Amount, Total Transactions, Avg Transaction Value, Total Fee, Total Tax — all with YoY % change |
| **Total Amount by Month** | Line area chart tracking monthly transaction volume across Jan–Dec 2024 |
| **Total Amount by Transaction Status** | Donut chart — Success (85%), Failed (10.5%), Pending (4.4%) |
| **Total Amount by Customer Segment** | Horizontal bar — Retail ₹74M, Premium ₹26M, SME ₹21M, Corporate ₹9M, Wealth ₹6M |
| **Total Amount by State** | Geographic bar chart — Top states: Maharashtra ₹19.7M, Karnataka ₹15.8M, Gujarat ₹14.8M |
| **Transaction Type Analysis** | Detailed table — Amount, Fee, Tax, Count across 10 transaction types |
| **Total Amount by Gender** | Donut — Female 51.3% (₹69M) vs Male 48.7% (₹66M) |

### Page 2 — Transactions
A granular transaction-level drill-down table with full record details.

| Column | Description |
|--------|-------------|
| Transaction_ID | Unique identifier per transaction |
| Transaction_Date | Date of transaction (2024) |
| Customer_Name | Individual customer name |
| Transaction_Type | Transfer, Deposit, Loan EMI, Investment, etc. |
| Transaction_Status | Success / Failed / Pending |
| Gender | Male / Female |
| Customer_Segment | Retail, SME, Premium, Corporate, Wealth |
| State | Indian state of transaction origin |
| Total Amount | Transaction value in ₹ |
| Total Fee | Fee charged per transaction |
| Total Tax | Tax applied per transaction |

---

## 📈 Key KPIs (2024)

| Metric | Value | YoY Change |
|--------|-------|-----------|
| Total Amount | ₹ 135.62M | -1.06% |
| Total Transactions | 15,030 | -0.03% |
| Avg Transaction Value | ₹ 9,020 | -1.02% |
| Total Fee | ₹ 217,300 | +0.34% |
| Total Tax | ₹ 39,140 | +0.42% |

---

## 💡 Key Insights

- **85% of total transaction volume** is successful — 10.5% failed transactions represent a significant risk/ops concern worth investigating
- **Loan EMI (₹39.9M) and Transfer (₹35.7M)** are the two highest-value transaction types, together accounting for ~56% of total volume
- **Retail segment dominates** at ₹74M — more than all other segments combined, signaling heavy dependence on a single customer tier
- **Maharashtra leads geographically** at ₹19.7M, followed by Karnataka and Gujarat — suggesting regional concentration risk
- **Female customers contribute marginally more** (51.3%) than male — indicating near-equal gender distribution in the customer base
- **Fee and Tax revenue are growing YoY** (+0.34%, +0.42%) even as transaction volume declines — suggesting fee structure optimization

---

## 🛠️ Tools & Features Used

| Category | Details |
|----------|---------|
| **Tool** | Microsoft Power BI Desktop |
| **Data Source** | Financial transactions dataset (India, 2024) |
| **Visuals** | KPI Cards, Line Chart, Donut Chart, Bar Chart, Matrix Table |
| **Interactivity** | Year Slicer, Dynamic Metric Selector, Occupation Filter, Category Filter |
| **DAX** | YoY % change measures, dynamic metric switching, aggregations |
| **Pages** | Overview Analysis, Transactions Drill-down |


## 👤 Author

**Saiprakash Yamsani**
Data Science | Power BI | Financial Analytics
📧 [email2saiy@gmail.com] | 🔗 [LinkedIn]
