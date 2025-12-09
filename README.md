# Global Beverage Sales & Profitability Dashboard (Power BI)

## 1. Background & Overview
This project delivers a comprehensive **Power BI sales intelligence dashboard** for a global beverage company operating across **North America, Europe, and the Middle East**. The organization previously relied on fragmented Excel reports, which limited real-time visibility into performance.

The objective of this project was to build a **centralized, executive-ready analytics solution** to track:
- Sales vs target performance  
- Profitability  
- Product and regional trends  
- Retail channel effectiveness  
- Sales manager performance  

The dashboard analyzes performance from **2023 to 2025** and supports **strategic, data-driven decision-making**.

---

## 2. Data Structure Overview
The dataset represents a simulated but realistic global sales environment and follows a **star-schema data model**.

### 🔹 Fact Table
- `Sales`  
  - Order Date  
  - Country  
  - Region  
  - Product  
  - Sub-Category  
  - Customer Type  
  - Sales Manager  
  - Sales Amount  
  - Cost  
  - Profit  

### 🔹 Dimension Tables
- `Date` (Year, Quarter, Month)
- `Country` (Country, Region)
- `Product` (Category, Sub-Category)
- `Customer` (Hypermarket, Supermarket)
- `Manager` (Sales Representative)

### 🔹 Coverage
- **Countries:** USA, KSA, UAE, UK, Canada, Oman, Qatar  
- **Regions:** North America, Europe, Middle East  
- **Product Categories:** Still Water, Sparkling Water, Flavoured Water, Coolers, Accessories  
- **Customer Types:** Hypermarket, Supermarket  

---

## 3. Executive Summary
From 2023–2025, the company generated:

- **Total Sales:** $270.4M  
- **Target Sales:** $282.1M  
- **Gross Profit:** $131.2M  
- **Net Profit:** $101.8M  
- **Gross Margin:** 48.5%  
- **Net Profit Margin:** 37.6%  

Performance shows **strong profitability despite falling slightly short of the overall revenue target**. Sales are highly concentrated in a few top markets and heavily driven by water-based products, especially **Still Water**.

---

## 4. Insight Deep Dive

### Regional & Country Performance
- **USA** is the top-performing market.
- **KSA and UAE** are strong secondary contributors.
- **Qatar and Oman** show the weakest sales performance.

This highlights a **geographic revenue concentration risk**.

---

### Product Performance
- **Still Water** is the dominant revenue driver.
- **Sparkling Water** is the second-highest contributor.
- **Accessories** generate minimal revenue.

This shows that product diversification is limited and growth is highly dependent on core beverage products.

---

### Retail Channel Performance
- Some countries operate almost entirely through **one retail channel** (Hypermarket or Supermarket).
- Others show a balanced channel mix (e.g., USA, Canada, KSA).

This presents an opportunity to **optimize retail distribution strategies by market**.

---

### Time-Series Trend Analysis
- Sales show **consistent growth from 2023 to 2025**.
- Peak quarterly sales reached approximately **$31M in 2025**.
- Seasonality is visible across multiple years.

---

### Sales Manager Performance
- Top performers generate **8x more revenue** than the lowest performer.
- This supports **performance-based compensation, coaching, and territory optimization**.

---

## 5. Recommendations
Based on the dashboard insights, the following recommendations are proposed:

1. **Expand High-Performing Markets**  
   Increase investment in the USA, KSA, and UAE where demand is already validated.

2. **Reduce Revenue Concentration Risk**  
   Develop growth strategies for underperforming markets (Qatar, Oman) or reconsider allocation.

3. **Diversify Product Portfolio**  
   Strengthen promotion of Sparkling and Flavoured Water to reduce reliance on Still Water.

4. **Optimize Retail Channel Strategy**  
   Expand underutilized retail channels within each country for better market penetration.

5. **Leverage Sales Manager Benchmarking**  
   Use top performers as models for training underperforming sales teams.

---

## 🛠 Tools & Technologies
- Power BI  
- Power Query (ETL)  
- DAX  
- Star Schema Data Modeling  
- Excel / CSV  

---
