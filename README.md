# Sales-Performance-Analysis
## OVERVIEW
This project evaluates retail sales performance, customer segments, and profitability trends using Power BI. By cleaning raw data in Power Query and building interactive dashboards, this analysis identifies key drivers of revenue growth while highlighting profit leakage caused by over-discounting across key product categories.
## DASHBOARD
### Customer Analysis Dashboard 
<img width="903" height="503" alt="salesdata1" src="https://github.com/user-attachments/assets/ff8c1c16-9f1e-49d5-adb0-162494a226ee" />

### Product Analysis Dashboard 
<img width="899" height="507" alt="salesdata2" src="https://github.com/user-attachments/assets/963abe96-756c-46dd-b27f-20ce07ce040c" />

### Time Series Dashboard
<img width="900" height="507" alt="salesdata3" src="https://github.com/user-attachments/assets/e156862a-ac0c-4330-a72e-e033ba13e9b9" />

### KEY INSIGHTS

| Category | Sales | Profit | Average Discount | Status |
| -------- | ----- | ------ | ---------------- | ------ |
| Technology | $815.26K | $140.55K | 15% | HIGH PROFIT |
| Office Supplies | $701.04K | $120.43K | 18% | HIGH VOLUME |
| Furniture | $711.35K | $16.44K | 19% | MARGIN LEAK |

### Top performer
Technology delivers the highest revenue and maximum profit while office supplies drives volume (22.9K). 

### Margin Loss
Furniture experiences significant profit reduction due to heavy promotional discounting across specific sub-categories.

### Customer & Regional Breakdown
* **Customer Segments:** Consumer segment drives over half of total revenue ($1.12M), followed by Corporate ($0.69M) and Home Office ($0.42M).
* **Shipping & Top Regions:** Standard Class accounts for 59.4% ($1.32M) of revenue. West Region leads in profitability, generating $700K in revenue and $107K in net profit.
* **Profit Leakage:** Central Region brings the lowest profit despite generating $490.6K in revenue, caused by heavy over-discounting (consuming 35.49% of all discounts).

## Business Recommendations

* **Cap *Furniture* discounts at 20%:** Implement strict discount caps on Furniture (specifically Tables and Bookcases) to eliminate negative margin transactions while maintaining unit volume.
* **Regional Discounting Controls:** Establish strict pricing control in Central Region (specifically Texas and Illinois) to eliminate revenue leakage and protect net margins.
