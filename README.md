# Sales Insights Dashboard (Power BI)

A Power BI dashboard for analysing retail sales performance using DAX measures and a star schema data model.

## 🎯 Objectives

- Track key sales KPIs (revenue, quantity, profit).  
- Analyse performance by **date, region, product and customer segment**.  
- Identify top-performing categories/products and declining areas.  

## 🧱 Data & Modelling

- Source: Sample transactional retail dataset (orders, customers, products, regions).  
- Model: Star schema with **FactSales** and dimension tables (Date, Customer, Product, Region).  
- Transformations done using Power Query (data types, relationships, calculated columns).

## 📊 Dashboard Highlights

- Summary page with high-level KPIs and YoY trends.  
- Category and product breakdowns with interactive filters.  
- Region view to compare performance across locations.  
- Top N products and customers by revenue/profit.

## 🛠️ Tools & Tech

- **Power BI Desktop**  
- **DAX** for measures (Total Sales, Profit Margin, % Growth, etc.)  
- **Power Query** for cleaning and shaping the data.

## 🚀 How to Use

1. Clone or download this repository.  
2. Open `Sales_Insights_Dashboard.pbix` in **Power BI Desktop**.  
3. Refresh the data (if a data source is connected) or explore the visuals with existing data.  

## 📁 Project Structure

- `Sales_Insights_Dashboard.pbix` – main Power BI report  
- `data/` – sample dataset (if included)  
- `README.md` – project documentation  

## ✅ Key Outcomes

- Clear view of sales performance across multiple dimensions.  
- Reusable model and layout for similar retail reporting needs.  
