# Retail Sales Performance Dashboard

An interactive **Microsoft Power BI** portfolio project for analysing retail sales performance across **2024–2025**, with a focus on revenue, profitability, product performance, regional performance, returns and customer loyalty.

## Project Overview

This project presents a three-page business intelligence dashboard designed to turn retail transaction data into a clear management view of commercial performance.

The report is structured around three analytical areas:

1. **Executive Overview** — high-level sales and profitability KPIs
2. **Product & Margin Analysis** — category and product-level profitability
3. **Returns & Customer Analysis** — return behaviour and customer loyalty performance

The Power BI semantic model is organised using separate fact and dimension tables, allowing the report to analyse sales, returns, targets, products, customers, dates and stores in a structured way.

## Dashboard Pages

### 1. Executive Overview

Provides a management-level snapshot of business performance.

**KPIs**
- Total Sales
- Gross Profit
- Profit Margin
- Total Orders

**Visual analysis**
- Monthly Sales Trend
- Sales by Category
- Sales by Region
- Year slicer for interactive filtering

### 2. Product & Margin Analysis

Focuses on product-level commercial performance and profitability.

**Visual analysis**
- Gross Profit by Category
- Profit Margin by Category
- Top Products by Sales
- Product-level Sales, Gross Profit and Profit Margin
- Category slicer

### 3. Returns & Customer Analysis

Explores the financial impact of returns and customer purchasing behaviour.

**KPIs**
- Returned Sales
- Return Rate
- Return Quantity

**Visual analysis**
- Returned Sales by Return Reason
- Return Rate by Category
- Sales by Loyalty Tier
- Top Returned Products

## Data Model

The report contains the following fact and dimension tables:

### Fact tables
- `factSales`
- `factReturns`
- `factTargets`

### Dimension tables
- `dimCustomer`
- `dimDate`
- `dimProduct`
- `dimStore`

This structure separates transactional data from descriptive dimensions and supports reusable measures across report pages.

## Measures Used in the Report

The report layer uses dedicated measures including:

- `M_Total Sales`
- `M_Gross Profit`
- `M_Profit Margin`
- `M_Total Orders`
- `M_Returned Sales`
- `M_Return Rate`
- `M_Return Quantity`

## Business Questions Addressed

The dashboard is designed to help answer questions such as:

- How are total sales and gross profit performing over time?
- Which product categories contribute the most sales and profit?
- Which regions generate the most sales?
- Which products perform best based on sales and margin?
- What is the value and rate of returned sales?
- What are the most common return reasons?
- Which product categories experience higher return rates?
- How does sales performance differ across customer loyalty tiers?

## Tools & Skills Demonstrated

- Microsoft Power BI Desktop
- DAX measures
- Fact and dimension data modelling
- KPI design
- Interactive slicers
- Business intelligence reporting
- Sales and profitability analysis
- Product performance analysis
- Returns analysis
- Customer segmentation analysis
- Data visualisation and dashboard design

## Repository Structure

```text
PowerBI-Retail-Sales-Performance-Dashboard/
│
├── README.md
└── Retail-Sales-Performance-Dashboard.pbix
```

## How to View the Dashboard

1. Download `Retail-Sales-Performance-Dashboard.pbix`.
2. Open the file using **Microsoft Power BI Desktop**.
3. Navigate through the three report pages.
4. Use the available slicers and visual interactions to explore the data.

> GitHub cannot render `.pbix` files directly. Opening the file in Power BI Desktop provides the full interactive dashboard experience.

## Suggested Future Enhancement

The semantic model already includes a `factTargets` table. A future extension could surface **Actual vs Target**, variance and target-achievement KPIs to further strengthen the performance-management view.

## Author

**Ismail Md Zani**  
Final-Year Mathematics Undergraduate, Universiti Teknologi Malaysia (UTM)

- GitHub: https://github.com/ismailmdzani
- LinkedIn: https://www.linkedin.com/in/ismail-md-zani-4b169a395/
