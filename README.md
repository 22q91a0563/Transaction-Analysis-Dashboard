#  Transactions Analysis Dashboard

##  Project Overview

The **Transactions Analysis Dashboard** is an interactive Power BI report designed to analyze transaction data and provide meaningful insights into transaction amounts, trends, categories, and transaction types.

The dashboard enables users to monitor financial activities, identify spending patterns, compare transaction performance across different time periods, and make data-driven decisions through interactive visualizations.

---

##  Objectives

- Analyze overall transaction performance.
- Track transaction amounts across different months and days.
- Compare debit and credit transactions.
- Identify transaction trends and patterns.
- Enable interactive filtering for deeper analysis.
- Provide key business metrics through KPI cards.

---

##  Dataset Structure

The dashboard is built using a transactional dataset containing the following information:

| Column | Description |
|----------|-------------|
| Date | Transaction Date |
| Day Name | Day of the Week |
| Month Name | Month of Transaction |
| Transaction Type | Debit / Credit |
| Category | Transaction Category |
| Amount | Transaction Amount |

---

##  Dashboard Components

### KPI Cards

The dashboard includes the following KPIs:

-  Total Transaction Amount
-  Average Transaction Amount
-  Maximum Transaction Amount
-  Minimum Transaction Amount
-  Total Transaction Count

---

### Interactive Slicers

Users can dynamically filter the dashboard using:

- Month Name
- Day Name
- Transaction Type
- Transaction Category

---

##  Visualizations

### 1️. Monthly Transaction Analysis (Column Chart)

**Purpose:** Analyze transaction trends across months.

**Metrics:**
- Sum of Transaction Amount
- Month-wise Comparison

---

### 2️. Day-wise Transaction Distribution (Donut Chart)

**Purpose:** Understand transaction activity across weekdays.

**Metrics:**
- Transaction Amount by Day

---

### 3️. Maximum Transaction Analysis (Funnel Chart)

**Purpose:** Identify months with the highest transaction values.

**Metrics:**
- Maximum Transaction Amount

---

### 4️. Month vs Day Performance (Ribbon Chart)

**Purpose:** Compare transaction rankings and trends over time.

**Metrics:**
- Transaction Amount by Month and Day

---

### 5️. Transaction Type Analysis (Treemap)

**Purpose:** Analyze Debit and Credit transaction contributions.

**Metrics:**
- Average Transaction Amount
- Transaction Type Distribution

---

##  Data Modeling

### Fact Table

#### Transactions_Fact

Contains:

- Transaction Details
- Transaction Amount
- Transaction Type

### Dimension Tables

#### Calendar_Dim

Contains:

- Date
- Month Name
- Day Name
- Year

#### Category_Dim

Contains:

- Transaction Categories

---

##  Key Insights Generated

The dashboard helps answer:

- What is the total transaction amount?
- Which month recorded the highest transactions?
- Which day has maximum transaction activity?
- What is the average transaction amount?
- How do Debit and Credit transactions compare?
- Which categories contribute the most to overall transactions?

---

##  Tools & Technologies

- Power BI Desktop
- Power Query
- Data Modeling
- Interactive Visualizations

---

##  Dashboard Development Workflow

1. Import transaction dataset.
2. Perform data cleaning using Power Query.
3. Create Calendar and Category dimensions.
4. Establish table relationships.
5. Design dashboard visuals.
6. Add slicers and interactions.
7. Publish and share insights.

---

##  Dashboard Preview
<img width="1033" height="593" alt="image" src="https://github.com/user-attachments/assets/e963f46d-85e4-4d0d-9cd3-f31d60b06cc4" />

---

##  Business Value

This dashboard provides:

- Better visibility into transaction activities.
- Improved financial monitoring.
- Faster decision-making through interactive reporting.
- Trend analysis for identifying spending and earning patterns.
- Easy-to-understand visual insights.

---
