# Project 4: E-commerce Data Visualization

## Overview
This project analyzes a cleaned e-commerce orders dataset using Python and visualizations to communicate revenue and order-status patterns.

## Dataset
- **Rows:** 1,200 orders
- **Columns:** 14
- **Period:** January 2023 – June 2025
- **Main fields used:** `Date`, `Product`, `TotalPrice`, `ReferralSource`, `OrderStatus`, and `PaymentMethod`

## Tools
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / VS Code

## Key Findings
- Total revenue: **1,264,761.96**
- Number of orders: **1,200**
- Average order value: **1,053.97**
- Chair and Printer are the leading products by revenue, at approximately **196K** each.
- Instagram is the leading referral source, generating approximately **275K** (about **21.8%** of revenue).
- Monthly revenue is variable; the peak month is **June 2024 (68,069)**.
- January–June revenue declined **19.1%** from 2023 to 2025.
- Cancelled and Returned orders represent **41.4%** combined; Delivered orders account for **19.2%**.
- Credit Card has the highest average order value (**1,128**).

## Recommendations
1. Investigate cancellation and return patterns by product, payment method, and referral source.
2. Diagnose monthly revenue fluctuations using campaign, product-mix, and order-volume context.
3. Test improvements to acquisition and payment experiences, measuring completed orders and conversion as well as revenue.

## Project Files
- `DECODE_LABS_PROJECT4.ipynb` — analysis notebook
- `charts/` — saved chart images
- `Project4_Ecommerce_Insights.pptx` — presentation

## Source
Cleaned E-commerce Orders Dataset, January 2023 – June 2025.
