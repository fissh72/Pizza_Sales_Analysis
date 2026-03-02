# Pizza_Sales_Analysis
A data analytics project using SQL and Power BI to analyze pizza business performance
# Pizza Business Performance Analysis
## 📊 Dashboard Visuals

### Home Page
![Dashboard Home](Screenshot%202026-03-02%20072909.png)

### Best/Worst Sellers Analysis
![Best and Worst Sellers](Screenshot%202026-03-02%20073132.png)

---

## 📄 Project Documentation
For a detailed look at the full report and the underlying SQL logic, you can view the files directly:
* [📂 View Full Dashboard (PDF Version)](sales(!)%20analysis.pdf)
* [📝 View SQL Documentation (Word Doc)](Pizza%20Sales%20SQL%20Queries.docx)

## 📌 Project Overview
This project provides a 360-degree view of a pizza store's sales performance. I used **SQL** to extract and calculate key business metrics and **Power BI** to visualize these insights for data-driven decision-making.

## 📊 Key Performance Indicators (KPIs)
Extracted via SQL and verified in Power BI:
* **Total Revenue:** $817.86K
* **Total Orders:** 21,350
* **Total Pizzas Sold:** 49,574
* **Average Order Value:** $38.31
* **Average Pizzas Per Order:** 2.32

## 🔍 SQL Analysis Highlights
The SQL queries focused on calculating essential sales metrics. Examples include:
* **Total Revenue:** `SELECT SUM(total_price) AS Total_Revenue FROM pizza_sales;`
* **Average Order Value:** `SELECT SUM(total_price) / COUNT(DISTINCT order_id) AS Avg_order_value FROM pizza_sales;`
* **Average Pizzas per Order:** `SELECT ROUND(SUM(quantity) / COUNT(DISTINCT order_id), 2) AS Avg_Pizza_per_Order FROM pizza_sales;`

## 📈 Dashboard Insights
* **Peak Times:** Weekends (Friday and Saturday evenings) show the highest order volumes.
* **Seasonal Trends:** Sales peaks occur in **July** and **May**.
* **Product Performance:** The **Thai Chicken Pizza** is the top revenue generator, while the **Brie Carre Pizza** is the lowest seller.

## 🛠️ Tools Used
* **SQL:** For data querying and KPI extraction.
* **Power BI:** For data modeling and visualization.
* **MS Word:** Used for detailed documentation of the SQL process.
