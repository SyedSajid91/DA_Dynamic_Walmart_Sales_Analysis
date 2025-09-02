# 🛒 Dynamic Walmart Sales Analysis – Excel Dashboard

## 📌 Project Overview
This project focuses on **Exploratory Data Analysis (EDA)** and building a **Dynamic Excel Dashboard** for Walmart’s global sales dataset.  

The dashboard provides **interactive insights** into Sales, Profit, Quantity, and Orders across **Segments, Categories, Markets, and Regions**, enabling stakeholders to track KPIs and make data-driven decisions.

🔗 **Repo**: [DA_Dynamic_Walmart_Sales_Analysis](https://github.com/SyedSajid91/DA_Dynamic_Walmart_Sales_Analysis)  
📊 **Dataset Source**: [Excel Dataset (GitHub Raw)](https://raw.githubusercontent.com/starlordali4444/Acciojob-Excel/refs/heads/master/common_notes/data/excel_dataset.xlsx)

---

## 🎯 Business Objective
Walmart leadership needs a dashboard to **monitor business performance** and **identify growth opportunities**. The key requirements were:

1. Track **important KPIs** (Sales, Profit, Orders, Quantity, Profit Margin).  
2. Analyze **Segment, Category, and Market performance**.  
3. Identify **Top 5 & Bottom 5 performers** in Sales, Profit, and Orders.  
4. Display **Top 10 Countries by Sales** on a World Map.  
5. Highlight **Top Sub-Categories** and their contribution to total Sales.  
6. Show **Market Share of Regions** using visual breakdowns.  

---

## 📂 Dataset Information
The project uses **three datasets**:

### 1. Orders Table  
Contains all order-level details such as customer, product, region, and financial metrics.  
**Key Fields:** `Order ID`, `Order Date`, `Ship Mode`, `Customer Name`, `Segment`, `Market`, `Region`, `Category`, `Sales`, `Profit`, `Quantity`, `Shipping Cost`, `Order Priority`  

### 2. People Table  
Mapping of salespersons and their assigned **Regions**.  

### 3. Returns Table  
Indicates whether an order was **Returned** (`Yes/No`).  

---

## 📊 KPI Table
| KPI                 | Name           | Symbol |
|----------------------|----------------|--------|
| Sum of Sales         | Total Sales    | 📈     |
| Sum of Profit        | Total Profit   | 💰     |
| Sum of Quantity      | Total Quantity | 📦     |
| Sum of Orders        | Total Orders   | 🛒     |
| Profit Margin        | Profit Margin  | 🔍     |

---

## 📖 Data Dictionary
| Field Name    | Description |
|---------------|-------------|
| Row ID        | Unique identifier for each row |
| Order ID      | Unique identifier for each order |
| Order Date    | Date when the order was placed |
| Ship Date     | Date when the order was shipped |
| Ship Mode     | Shipment type (e.g., Same Day, First Class) |
| Customer ID   | Unique identifier of the customer |
| Customer Name | Name of the customer |
| Segment       | Customer segment (Consumer, Corporate, Home Office) |
| City, State, Country | Shipping location |
| Market        | Market of the order (US, EU, APAC, etc.) |
| Region        | Regional division of the market |
| Product ID    | Unique identifier for the product |
| Category      | Product category (Technology, Furniture, Office Supplies) |
| Sub-Category  | Subdivision of the product category |
| Product Name  | Full product name |
| Sales         | Total sales revenue |
| Quantity      | Number of units sold |
| Discount      | Discount applied |
| Profit        | Profit earned |
| Shipping Cost | Shipment charges |
| Order Priority| Priority of the order (Critical, High, Medium, Low) |

---

## 📈 Dashboard Features
✅ Dynamic slicers for **Market, Segment, Region, and Category**  
✅ KPI cards with **visual icons** 📈💰📦🛒🔍  
✅ **Top 5 & Bottom 5 analysis** for Sales, Profit, and Orders  
✅ 🌍 **World Map** showing Top 10 countries by Sales  
✅ 📦 Sub-Category breakdown & contribution analysis  
✅ 🗺️ Regional **Market Share distribution**  

---

## 📷 Dashboard Preview
<img width="969" height="658" alt="mainCapture" src="https://github.com/user-attachments/assets/dcf6fb35-475b-41b9-bd44-d40ad0348ea3" />
<img width="962" height="416" alt="m2" src="https://github.com/user-attachments/assets/e623f22b-c1dc-43d0-b768-5dcd3c240554" />
<img width="971" height="277" alt="Capture" src="https://github.com/user-attachments/assets/1b5d8d4e-4395-415a-83ea-2f7cd203f8e6" />
<img width="314" height="195" alt="Capture1" src="https://github.com/user-attachments/assets/77f361af-445f-4437-a541-2d8471c51ed4" />  

---

## 🚀 Project Workflow
1. **Data Loading**: Connected Excel to the GitHub dataset.  
2. **Data Cleaning**: Used Power Query to handle missing values & formatting.  
3. **Data Modeling**: Built relationships between `Orders`, `People`, and `Returns` tables.  
4. **EDA**: Performed descriptive analysis of KPIs.  
5. **Dashboard Design**: Created interactive charts, KPIs, and maps.  
6. **Insights**: Highlighted key business takeaways for Walmart leadership.  

---

## 🔑 Key Insights
- **Top-performing regions**: US & EU dominate in total sales.  
- **Profitability varies**: High-discount orders often resulted in **negative profits**.  
- **Sub-category leaders**: Phones & Chairs contributed a significant share of revenue.  
- **Returns analysis**: LATAM and EU markets recorded higher return percentages.  

---

## 🛠️ Tools & Skills
- **Microsoft Excel**: Pivot Tables, Slicers, Conditional Formatting, Maps  
- **Power Query**: Data cleaning & transformation  
- **Data Visualization**: Dynamic dashboards & KPI cards  
- **GitHub**: Version control & dataset hosting  

---

## 📌 How to Use
1. Clone/download this repo.  
2. Open the Excel file (`Walmart_Dashboard.xlsx`).  
3. Enable content & refresh Power Query connections.  
4. Explore the dashboard with filters and slicers.  

---

## 📢 Author
👤 **Syed Sajid**  
📍 Passionate about Data Analytics, Visualization, and Business Intelligence.  

🌐 [GitHub](https://github.com/SyedSajid91) | 🔗 [LinkedIn](https://www.linkedin.com/)  

---



🔥 *If you like this project, don’t forget to ⭐ star the repo!*  
