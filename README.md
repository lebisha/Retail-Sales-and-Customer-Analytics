# Retail Sales & Customer Analytics Dashboard for Strategic Decision-Making

## 🚀 Project Objective
Design and implement a comprehensive retail analytics dashboard using **MySQL** and **Power BI** to provide actionable insights into sales performance, customer behavior, product trends, and payment preferences. This project enables strategic decisions for inventory optimization, marketing campaigns, and revenue growth.

---

## 1️⃣ Database Design & Normalization
- Converted a single sales table into a fully normalized relational database with:
  - **Customers, Products, Payments, Orders, Order_Items** tables
- Handled foreign key dependencies and optimized structure by converting shopping mall into a column rather than a separate table
- Ensured data integrity by:
  - Checking for nulls and duplicates
  - Validating referential integrity: all Orders reference existing Customers; all Order_Items reference valid Products
- Solved MySQL warnings during calculations using **CAST** to avoid truncation errors  

**💡 Key Takeaway:** Structured and clean data ensures reliable analytics and enables complex queries for KPI calculation and dashboards.

---

## 2️⃣ KPI & Sales Analysis
- **Total Revenue:** ₹1.51bn
- **Total Orders:** 99k+  
- **Average Order Value:** ₹15k 
- Monthly revenue trend analysis shows:
  - Seasonal peaks in **March, July, October**
  - Slow months in **February, November**
  - Anomalous drop in **March 2023** → highlighted for operational investigation  

**💡 Key Takeaway:** Seasonality trends enable timely marketing campaigns and inventory planning to maximize revenue.

---

## 3️⃣ Customer Insights
- **Age group contribution:** 50+ age group drives highest revenue, followed by 20s and 30s
- **Top categories by age:**
  - Clothing & Shoes: Across all age groups
  - Technology: 30s–50+
  - Cosmetics & Toys: Teens & 20s
- **Customer frequency:** Majority are one-time buyers → opportunity to implement loyalty programs  

**💡 Key Takeaway:** Age-targeted campaigns can boost category sales, while loyalty initiatives increase repeat purchase rate.

---

## 4️⃣ Product & Category Performance
- **Top-selling categories (by revenue):** Clothing > Shoes > Technology > Cosmetics  
- Units sold vs revenue indicates high-value categories for promotions  
- **Seasonality per category:**
  - Cosmetics: Peaks in Dec
  - Electronics/Technology: Peaks in festival months
  - Clothing & Shoes: Consistent demand  

**💡 Key Takeaway:** Enables inventory prioritization and seasonal promotions tailored to high-demand categories.

---

## 5️⃣ Mall & Location Insights
- Revenue ranking of malls:
  - Top 3: Mall of Istanbul, Kanyon, Metrocity → ~50% of total revenue
  - Lower-performing malls: Zorlu, Viaport, Forum → focus on targeted campaigns
- Revenue vs transactions consistent → average basket size stable across locations  

**💡 Key Takeaway:** Strategic focus on high-performing malls for premium launches; optimize campaigns at underperforming locations.

---

## 6️⃣ Payment Preferences
- Cash: 45%  
- Credit Card: 35%  
- Debit Card: 20%  
- Insights suggest potential for digital payment campaigns or cashless incentives  

**💡 Key Takeaway:** Align payment methods with customer behavior; consider promotions to encourage digital transactions.

---

## 7️⃣ Dashboard Implementation (Power BI)
- **Yearly Sales Trend:** Line chart shows growth, dips, and seasonality  
- **Top Performing Malls:** Horizontal bar chart highlights mall revenue ranking  
- **Best-Selling Categories:** Pie chart for revenue distribution  
- **Age Group vs Category Spending:** Stacked Bar Chart to identify high-value segments  
- **Seasonality (Best Month per Category):** Line charts (small multiples) for category-specific trends  
- **Payment Method Preferences:** Pie chart for quick view of payment behavior  

**💡 Key Takeaway:** Enables executive-level visualization for strategic decision-making in marketing, inventory, and revenue optimization.

---

## 8️⃣ Strategic Business Insights
- **Revenue Growth Opportunities:** Focus marketing and premium launches in Mall of Istanbul, Kanyon, Metrocity; implement seasonal campaigns during peak months (Mar, Jul, Oct)  
- **Customer Retention:** Introduce loyalty programs for one-time buyers; personalize promotions based on age group and category preference  
- **Product Strategy:** Prioritize high-value categories: Clothing, Shoes, Technology; optimize inventory based on seasonality trends  
- **Payment Optimization:** Encourage digital payments with incentives; maintain convenience for cash-preferred segments  


---

## 9️⃣ Tools & Techniques Highlighted
- **Database:** MySQL (normalization, foreign keys, data integrity)  
- **Data Cleaning & Transformation:** CAST, NULL filtering, date format conversion  
- **Analytics:** SQL views, window functions, CTEs for KPI, growth, and high-value customers  
- **Visualization:** Power BI dashboards with line, bar, pie, and heatmap charts  

---
## ✅ Outcome
This project demonstrates **end-to-end retail analytics capability**: from database normalization, advanced SQL queries, to interactive dashboards. 

