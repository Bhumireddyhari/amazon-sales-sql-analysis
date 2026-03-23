# amazon-sales-sql-analysis
End-to-end SQL data analytics project analyzing Amazon retail sales across categories, segments, regions and shipping channels


## 📌 Project Overview
Analyzed 9,994 Amazon retail transactions (2014–2017) using SQL to uncover 
revenue drivers, profitability gaps, and customer behavior patterns across 
product categories, customer segments, and geographic regions.

---

## 🎯 Problem Statement
Analyze key aspects of Amazon's sales data including performance by product 
category, customer segment, region, and sales channel to identify trends and 
insights that optimize sales strategies and improve profitability.

---

## 📂 Dataset
| Attribute | Detail |
|-----------|--------|
| Records | 9,994 rows |
| Columns | 20 |
| Period | 2014 – 2017 |
| Domain | US Retail / E-Commerce |
| Source | Amazon Retail Store Dataset |

*Key columns:* Order ID, Order Date, Ship Mode, Segment, Region, 
Category, Sub-Category, Sales, Quantity, Discount %, Profit, Shipment Cost

---

## 🛠️ Tools & SQL Concepts
- *Database:* PostgreSQL
- *Concepts Used:* GROUP BY, Aggregate Functions, CASE WHEN, 
  Window Functions (LAG), Subqueries, Date Arithmetic, 
  CTEs, Derived Columns

---

## 📊 Key Findings

### 1. Product Category
- Technology leads with *17.4% profit margin*
- Furniture is nearly breakeven at *2.5% margin*
- Tables and Bookcases are *loss-making sub-categories*

### 2. Customer Segment
- Home Office has the *highest margin (14%)* despite lowest sales
- Consumer has the most revenue but *lowest margin (11.5%)*

### 3. Regional Performance
- West region leads with *$108K profit and 14.9% margin*
- Central region has the *lowest margin (7.9%)* and *highest losses ($56K)*

### 4. Discount Impact ⚠️
| Discount Band | Profit Margin |
|---------------|--------------|
| 0% | +29.5% ✅ |
| 1–10% | +16.6% |
| 11–20% | +11.6% |
| 21–30% | -10.1% ❌ |
| 30%+ | -48.2% ❌ |

> Discounts above 20% cost the business *$135K+ annually*

---

## 💡 Business Recommendations
1. *Cap discounts at 20%* — recover $135K in annual losses
2. *Audit Central region* — lowest margin + highest loss concentration
3. *Reprice Tables & Bookcases* — consistently unprofitable sub-categories
4. *Target Corporate & Home Office* — highest profit margin customers



Part of my Data Analytics Portfolio | [https://www.linkedin.com/in/harivardhan-reddy-bhumireddy/)(#) | [Portfolio](#)
