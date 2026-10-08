# Customer Analytics — Python Portfolio Project

![Python](https://img.shields.io/badge/Python-3.x-blue) ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458) ![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)

## Overview
A portfolio-ready exploratory data analysis project using Python to understand customer demographics, purchasing behavior, customer tiers, geography, and revenue concentration.

## Business Questions
- How large is the customer base and how much revenue does it generate?
- Which customer segments contribute the most value?
- Which age groups and locations have the highest spending?
- Does order frequency relate to spending?
- How concentrated is revenue among high-value customers?

## Dataset
The original dataset contains customer-level information such as age, gender, city, state, registration date, customer tier, total orders, and total spending. **Direct personal identifiers (name, email, and phone) have been removed from the public copy in this repository.**

## Headline KPIs
| Metric | Value |
|---|---:|
| Customers | 40,000 |
| Total Orders | 200,139 |
| Total Revenue | 4,741,566,354.41 |
| Average Customer Spend | 118,539.16 |
| Average Orders / Customer | 5.00 |
| Average Order Value | 23,691.37 |
| Zero-Order Customers | 274 |

## Revenue Concentration
- Top 1%: **4.65%** of revenue
- Top 5%: **17.55%**
- Top 10%: **29.92%**
- Top 20%: **48.89%**

## Skills Demonstrated
Python, Pandas, NumPy, Matplotlib, Seaborn, exploratory data analysis, data cleaning, feature engineering, KPI development, segmentation, correlation analysis, geographic analysis, and business storytelling.

## Project Structure
```text
customer-analytics-github-project/
├── data/
│   └── customers.csv
├── notebooks/
│   └── customer_analysis.ipynb
├── outputs/
│   ├── customer_analysis.xlsx
│   └── charts/
├── README.md
├── requirements.txt
└── .gitignore
```

## Key Business Recommendations
1. Protect and retain high-value customers because revenue is concentrated among them.
2. Increase customer value through repeat-purchase and average-order-value strategies.
3. Use geographic segmentation to prioritize acquisition and retention.
4. Monitor order frequency and order value together rather than relying on orders alone.

## Important Analytical Note
Customer tier appears closely tied to total spending. Therefore, the tier-versus-spending relationship should not be interpreted as causal; tier may have been assigned using spending thresholds.

## Author
**Alex Mwashighadi**
