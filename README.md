

# 🚗 Car Sales Dashboard – Power BI  

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow.svg)  
![Excel](https://img.shields.io/badge/Excel-Data%20Storage-success.svg)  
![Data Cleaning](https://img.shields.io/badge/Data%20Cleaning-Power%20Query-blue.svg)  
![DAX](https://img.shields.io/badge/DAX-Analysis-orange.svg)  

## 📌 Overview  
This project presents a **Car Sales Analysis Dashboard** built in **Power BI**, designed to provide key insights into sales performance, income distribution, and pricing trends.  

The dataset was **cleaned in Power Query** (handling nulls, formatting, splitting columns, removing duplicates) and analyzed using **DAX measures** including **GROUPBY** and **column splitting** to create meaningful aggregations.  

---

## 📊 Key Metrics & KPIs  

- **Manual Car Price:** $316.41M  
- **Automatic Car Price:** $355.11M  
- **Total Income:** $19.86B  
- **Average Price:** $28.09K  

### 📈 Dashboard Insights  
- **Total Price by Color:**  
  - Pale White: $309.36M  
  - Black: $224.43M  
  - Red: $137.73M  

- **Total Price by Company:**  
  - Oldsmobile: $35.43M  
  - Volkswagen: $34.08M  
  - Toyota: $32.76M  
  - Pontiac: $23.37M  
  - Volvo: $21.93M  

- **Total Annual Income by Company:**  
  - Volkswagen: $1,138.81M  
  - Toyota: $972.90M  
  - Volvo: $660.84M  
  - Saturn: $629.20M  
  - Subaru: $478.73M  

- **Annual Income by Engine Type:**  
  - Double Overhead Cam: **52.87%**  
  - Overhead Cam: **47.13%**  

- **Gender Distribution by Price:**  
  - Male: **78.49%**  
  - Female: **21.51%**  

---

## 🛠️ Data Preparation  
### 🔹 Power Query (ETL Steps)  
- Removed nulls and duplicates  
- Split columns (e.g., customer details, models)  
- Standardized formats for price and income fields  
- Merged queries to build a clean dataset  

### 🔹 DAX (Data Analysis Expressions)  
- **GROUPBY** for company-level aggregation  
- **Calculated Measures** for income, average price, gender split  
- **Splitting logic** for category-wise analysis  

---

## 📂 Repository Structure  
