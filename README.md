# Global Beverage Sales & Profitability Dashboard (Power BI)

---

## 1. Background & Overview
This project delivers an executive-level **Power BI sales intelligence dashboard** for a global beverage company operating across **North America, Europe, and the Middle East**. Prior to this solution, reporting was fragmented across spreadsheets, delaying insights and limiting strategic visibility.

The objective was to build a **centralized analytics platform** to monitor:
- Sales vs Target
- Profitability
- Product & Regional Performance
- Customer Channel Mix
- Sales Manager Performance
- Year-over-Year & Quarter-over-Quarter Change

The dashboard analyzes performance from **2023 to 2025** and supports **strategic, data-driven decision-making**.

---

## 2. Data Structure Overview

### Fact Table
**Sales**
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

### Dimension Tables
- **Date:** Year, Quarter, Month  
- **Country:** Country, Region  
- **Product:** Category, Sub-Category  
- **Customer:** Hypermarket, Supermarket  
- **Manager:** Sales Representative  

### Coverage
- **Countries:** USA, KSA, UAE, UK, Canada, Oman, Qatar  
- **Regions:** North America, Europe, Middle East  
- **Product Categories:** Still Water, Sparkling Water, Flavoured Water, Coolers, Accessories  
- **Customer Types:** Hypermarket, Supermarket  

Data was modeled using a **Star Schema** and transformed using **Power Query (ETL)**.

---

## 3. Executive Summary

| Metric | Value |
|--------|--------|
| **Target Sales** | $282.1M |
| **Actual Sales** | $270.4M |
| **Variance** | **–$11.7M (–4.1%)** |
| **Gross Profit** | $131.2M |
| **Gross Margin** | 48.5% |
| **Net Profit** | $101.8M |
| **Net Margin** | 37.6% |

Despite missing the revenue target by **4.1%**, the company maintains **very strong profitability**, indicating a **highly efficient operating model**.

---

## 4. Insight Deep Dive (By Dashboard Page)

---

## A. Sales Overview Dashboard

<img width="553" height="317" alt="Sales Overview" src="https://github.com/user-attachments/assets/3106cc54-b219-4f8f-b166-40d186e35660" />

### Key Metrics
- Target: **$282.1M**
- Actual: **$270.4M**
- Gross Profit: **$131.2M**
- Net Profit: **$101.8M**
- Gross Margin: **48.5%**
- Net Margin: **37.6%**

### Historical Trend Story (2023–2025)
- **2023:** $15M–$21M per quarter  
- **2024:** $17M–$25M per quarter  
- **2025:** Peaks at **$31M per quarter**

✅ Sales show **consistent year-over-year growth**, with **strong acceleration in 2025**.

---

### Country Contribution
| Country | Sales |
|----------|--------|
| USA | $81M |
| KSA | $68M |
| UAE | $43M |
| UK | $36M |
| Canada | $20M |
| Oman | $12M |
| Qatar | $9M |

✅ **USA, KSA, and UAE contribute over 71% of total revenue**, indicating **geographic concentration risk**.

---

### Product Sub-Category Contribution
| Product | Sales | Share |
|----------|--------|--------|
| Still Water | $154.2M | 57% |
| Sparkling Water | $77.0M | 28% |
| Flavoured Water | $27.4M | 10% |
| Coolers | $10.8M | 4% |
| Accessories | $0.9M | <1% |

✅ The business is **heavily dependent on Still Water**, creating **product portfolio risk**.

---

### Retail Channel Mix
Examples:
- **USA:** 84% Supermarket / 16% Hypermarket  
- **UAE:** 100% Supermarket  
- **UK:** 70% Supermarket / 30% Hypermarket  
- **Qatar:** 72% Hypermarket / 28% Supermarket  

✅ Several countries operate with **single-channel dependency**, limiting **distribution scalability**.

---

### Sales Manager Performance
| Manager | Sales |
|----------|--------|
| Qaseem | $40M |
| Nijoe | $38M |
| Rajiv | $34M |
| Azeez | $21M |
| Tahir | $14M |
| Jayson | $5M |

✅ The top performer generates **8x more revenue than the lowest performer**, revealing **major productivity variance**.

---

## 👥 B. Customer Dashboard

<img width="556" height="311" alt="Customers" src="https://github.com/user-attachments/assets/d8d415f0-67c2-468a-bf80-28eb5c45d1e9" />

### Customer Trends (2023–2025)
- Customer volume increases year-over-year
- Hypermarkets drive **higher transaction volume**
- Supermarkets generate **higher revenue per transaction**

✅ The business benefits from a **dual-channel growth model**:
- Hypermarkets = volume engine  
- Supermarkets = profit engine  

---

## 💰 C. Profitability Dashboard

<img width="554" height="311" alt="Profitability" src="https://github.com/user-attachments/assets/fae0f41d-e6e1-4afe-85b6-5c568fdeb58c" />

### Profitability Metrics
- Gross Profit: **$131.2M**
- Net Profit: **$101.8M**
- Gross Margin: **48.5%**
- Net Margin: **37.6%**

### Historical Profit Story
- Profit rises consistently from **2023 → 2025**
- No margin erosion observed
- Profit growth closely tracks revenue growth

✅ The company operates with a **high-margin, scalable business model**.

---

## 📉 D. Change Analysis Dashboard

<img width="557" height="314" alt="Change Analysis" src="https://github.com/user-attachments/assets/81463727-820a-4f5b-9595-d688d202f956" />

### Growth Behavior
- 2024 significantly outperformed 2023
- 2025 delivered record-breaking quarters
- Growth driven mainly by:
  - USA
  - KSA
  - Still & Sparkling Water

✅ Growth is **unevenly distributed**, requiring **focused investment strategies**.

---

## 5. Recommendations

1. **Reduce 57% reliance on Still Water** by accelerating Sparkling & Flavoured Water marketing.
2. **Expand retail channels** in single-channel countries.
3. **Replicate top manager strategies** across low-performing teams.
4. **Double down on USA, KSA, and UAE for growth investment.**
5. **Use Change Analysis for demand forecasting and inventory planning.**

---

## 6. Tools & Technologies
- Power BI  
- Power Query (ETL)  
- DAX  
- Star Schema Data Modeling  
- Excel / CSV  

---

