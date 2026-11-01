# SwiftLog-Logistics-Analysis
Power BI analysis of SwiftLog Logistics’ deliveries, inventory, and supplier performance to improve operational visibility.

## Overview
SwiftLog Logistics is a fast-growing Nigerian logistics company managing warehouses, suppliers, inventory, and nationwide deliveries. Rapid expansion has caused delayed deliveries, inventory challenges, supplier performance issues, and limited executive visibility. This project analyzes its operational data and presents key insights in a Power BI dashboard to support better decisions.

## Business Questions
- Which KPIs require immediate management attention?
- Which products generate the highest revenue?
- Which warehouses operate the most efficiently?
- Which regions experience the most delayed deliveries?
- Which customers contribute the highest revenue

## Dataset
- **Source:** SwiftLog customers, orders, order items, warehouses, inventory, products, delivery performance, shipment, returns, employees, and suppliers data.
- **Size:** 1,000 customers, 5,000 orders, 15,000 order items, 250 products, 15 warehouses, 4,000 inventory, 500 returns, 200 employees, 150 suppliers, 5,000 shipments, and 5,000 delivery performance records.
- **Period:** January, 2026 to September, 2026.
- **Key fields:** CustomerID, OrderID, ProductID, SupplierID, WarehouseID.

## Tools Used
**Tableau** for the 5 pages interactive dashboard.

## Key Findings
- Delivery is the top priority. About 3.2K of roughly 5K deliveries were delayed.
- Delays are driving returns. The return rate is 10% (about 500 returns), and late delivery is the leading cause, ahead of wrong items and damaged goods.
- Revenue risk from customer concentration is low. The ten largest customers contribute only about 3% of revenue.
- Demand is healthy and well spread. Customers are split evenly across Ibadan, Kano, Lagos and Abuja (about 25% each).
- Order volume is even, but staffing is not

## Recommendations
- Break down delays by warehouse, region and delivery days, find the biggest causes, and set a monthly on-time target.
- Add pick-and-pack checks to cut wrong items, and review packaging and handling for damaged goods.
- Rebalance staffing.

## Limitations
- Supplier performance cannot yet be judged. The data shows stock and product counts per supplier, but not delays or returns by supplier.
- Data is fictional.

## ## Repository Structure
```
SwiftLog-Logistics-Analysis/
       
├── images/         # dashboard screenshots and charts
├── dashboard/      # Power BI dashboard

└── README.md
```

## About Me
**[Khairat Olawale]**, Data Analyst
[LinkedIn](www.linkedin.com/in/khairatolawale) | [Email](khairatolawale11@gmail.com)
