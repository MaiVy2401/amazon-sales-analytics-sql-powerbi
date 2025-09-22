# Customer & Sales Analysis (PostgreSQL + Power BI)

## 📌 Overview
This project explores an e-commerce dataset using **PostgreSQL** for data analysis and **Power BI** for visualization.  
The goal is to derive insights on **customer behavior, product performance, seller activity, and shipping efficiency**.  

Key highlight: **RFM Segmentation Dashboard** to categorize customers into groups like *Champions, Loyal, At-Risk*, etc.

---

## 🗂 Project Structure
- `sql/` → All SQL scripts (EDA, analysis queries, procedures, views)
- `powerbi/` → Power BI dashboard file
- `docs/` → Documentation & screenshots
- `README.md` → Project explanation

---

## 🔍 Analysis Tasks Implemented
### Customer Insights
- **RFM Segmentation** (Recency, Frequency, Monetary analysis)
- CLTV (Customer Lifetime Value)
- Top 5 customers in each state
- New vs. Returning Customers

### Product Insights
- Top-selling products overall and per category
- Profit margins by product
- Most returned products and categories
- Inventory stock alerts

### Seller Insights
- Top-performing sellers with success rate
- Inactive sellers (last 6 months)

### Order & Shipping Insights
- Monthly sales trends (2022–2024)
- Revenue by shipping provider + avg delivery time
- Shipping delays (>3 days after order)

### Financial Insights
- Payment success rate
- Average Order Value (AOV)

---

## 📊 Power BI Dashboard
The Power BI dashboard provides:
- **Total revenue, avg delivery time by shipping provider**
- **RFM segmentation visuals**
- **Sales trends over time**
- **Category performance breakdown**


---

## 🛠 Tech Stack
- PostgreSQL (SQL, Window functions, CTEs, Stored Procedures)
- Power BI (DAX, dashboards)
- GitHub for version control

---

## 🚀 How to Run
1. Run the scripts in `sql/` on PostgreSQL.
2. Load sample data (CSV or backup if provided).
3. Open the `.pbix` file in `powerbi/`.
4. Update the PostgreSQL connection string.
5. Explore dashboards & visuals!
