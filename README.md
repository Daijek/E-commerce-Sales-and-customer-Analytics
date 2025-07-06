# Brazilian E-Commerce Analytics Pipeline

![Workflow Diagram](https://via.placeholder.com/800x400.png?text=Architecture+Diagram) _Replace with actual diagram_

Automated ETL pipeline extracting Kaggle e-commerce data into PostgreSQL for Power BI reporting. Features monthly revenue tracking, product analysis, and customer segmentation.

## Key Performance Indicators (KPIs)

### 🚀 Revenue Analysis

- **Monthly Revenue Trend**: Sales performance over time
- **YoY Growth**: Year-over-year revenue comparison
- **Revenue by Category**: Top-performing product categories

### 📦 Product Performance

- **Top Selling Products**: Best-selling items (units sold)
- **Category Performance**: Revenue distribution by category
- **Price Optimization**: Average price vs. sales volume

### 👥 Customer Insights

- **Customer Retention Rate**: New vs. Repeat vs. Loyal customers
- **Geographic Distribution**: Top purchasing regions
- **Lifetime Value (LTV)**: Revenue per customer segment

### 💳 Order Analysis

- **Average Order Value (AOV)**: Revenue per transaction
- **Payment Method Distribution**: Credit vs. debit vs. voucher
- **Delivery Performance**: Actual vs. estimated delivery times

## Architecture Overview

```mermaid
graph LR
A[Kaggle Dataset] --> B(Python ETL)
B --> C[PostgreSQL]
C --> D[Power BI]
D --> E{{Business Insights}}
```
