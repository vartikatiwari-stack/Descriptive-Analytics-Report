# Nykaa Descriptive Analytics Report (2019–2025)

**Descriptive Analytics Report – Nykaa Product Sales Performance**

**Author:** Vartika Tiwari  
**Roll No.:** 1250258501  
**Course:** BCA D&AI  
**Institution:** Babu Banarasi Das University, Lucknow, Uttar Pradesh  
**Date:** 20-08-2026

---

## Overview

This repository contains a **Descriptive Analytics Report** analyzing a **synthetic Nykaa sales dataset** covering the period **2019–2025**.

The report explores:

- Best-selling products by volume
- Annual sales trends
- Regional demand patterns
- Pricing and profitability by region
- Product rating distribution
- Revenue and profit analysis
- Key performance metrics and actionable recommendations

> **Important Note:** All figures in this report are **synthetic** and created solely for academic descriptive-analytics demonstration. They should **not** be treated as Nykaa’s actual audited financial or operational data.

---

## Objectives

The analysis answers the following key questions:

1. What are the best-selling Nykaa products by volume?
2. How are products rated, and which products have the highest and lowest average ratings?
3. Which year recorded the highest sales volume?
4. Which region generates the highest total unit sales?
5. What is the average retail price by region?
6. Which region is most profitable per unit sold?
7. Is total sales volume growing or declining from 2019 to 2025?
8. Which product–region combination is the biggest revenue driver?

---

## Dataset Scale

| Dimension                  | Value              |
|---------------------------|--------------------|
| Years tracked             | 2019–2025         |
| Products tracked          | 20                |
| Regions tracked           | 4 (North, West, South, East India) |
| Product-region-year records | 560             |
| Total units sold          | ~2.19 million     |
| Rating scale              | 5                 |

---

## Key Findings

- **Volume Leader:** Minimalist Niacinamide Serum (~162,437 units)
- **Revenue Leader:** The Ordinary Niacinamide (~₹10.69 Cr)
- **Strongest Product–Region Combo:** The Ordinary Niacinamide × North India (~₹3.61 Cr)
- **Annual Trend:** Units grew from ~182,000 (2019) to ~558,000 (2025), with a temporary dip in 2020
- **Leading Region (Volume):** North India
- **Highest Profit per Unit:** East India
- **Average Product Rating:** 4.19 / 5

---

## Report Structure

| Section                     | Page |
|----------------------------|------|
| Cover Page                 | 1    |
| Content                    | 2    |
| Objective                  | 3    |
| Real-world Scale Table     | 4    |
| Best-Selling Products      | 5    |
| Annual Sales Trend         | 6    |
| Regional Demand            | 7    |
| Pricing and Profitability  | 8    |
| Rating Distribution        | 9    |
| Revenue and Profit         | 10   |
| Summary of Key Metrics     | 11   |
| Key Findings               | 12   |
| Recommendations & Appendix | 13–14|

---

## How to Use This Report

1. Open the PDF file:  
   `Nykaa_Descriptive_Analytics_Report_Vartika_Tiwari.pdf`

2. Review the visualizations and tables for:
   - Top 10 products by units sold
   - Year-wise sales trend
   - Regional demand distribution
   - Pricing vs profitability matrix
   - Revenue by category

3. Use the **Recommendations** section for inventory, pricing, and campaign insights derived from the analysis.

---

## Tools & Techniques (Conceptual)

The report follows a typical descriptive analytics workflow:

| Layer              | Purpose                                      | Typical Tools                  |
|--------------------|----------------------------------------------|--------------------------------|
| Investigation      | Explore raw data, types, missing values      | pandas, `df.info()`, `df.describe()` |
| Storage            | Hold data for repeated analysis              | CSV / Excel / Database         |
| Batch Aggregation  | Compute yearly sales, ratings, revenue, profit | pandas `groupby`, `pivot_table` |
| Serving / BI       | Present KPIs and charts                      | Matplotlib, Excel, PDF / BI Dashboard |

---

## Recommendations (Summary)

- Protect inventory for **Minimalist Niacinamide Serum** (volume driver)
- Maintain strong visibility for **The Ordinary Niacinamide** (revenue driver)
- Use regional demand patterns for smarter inventory allocation
- Monitor product ratings for sustained declines
- Evaluate regional pricing strategies (higher price ≠ lower profit)
- Prioritize high-value product–region combinations for campaigns

---

## Academic Note

This report is modeled on the structure and analytical framing of a reference report (Haldiram).  
All Nykaa numbers are **synthetic** and generated exclusively for academic practice in descriptive analytics.

---

## License

This project is intended for **educational and academic purposes only**.

---

**Author:** Vartika Tiwari  
**Course:** BCA (Data & Artificial Intelligence)  
**University:** Babu Banarasi Das University, Lucknow
