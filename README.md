# Supply Chain & Inventory Optimization Engine

---

### Project Overview:
In fast-paced retail and e-commerce environments, stockouts mean lost revenue, while overstocking bleeds capital. The goal of this project was to transition from historical data reporting to predictive operational intelligence. I built an end-to-end data pipeline to analyze supply chain metrics, automatically calculate safety stock, and dynamically generate product reorder points based on lead times and sales velocity.

---

### Tools & Technologies Used:
| Tools | Use |
|---|---|
| **Python (Pandas, NumPy)** | Ingested raw warehouse data and engineered custom operational features |
| **Operations Mathematics** | Programmatically calculated Safety Stock and Reorder Points using standard supply chain formulas (Avg Daily Sales × Lead Time) + Safety Stock |
| **DAX & Power BI** | Designed a real-time, interactive "Inventory Command Center" for warehouse management to visually track SKU health and prioritize purchasing decisions |

---

### Key Business Insights:

• Automated Risk Flagging: Engineered a custom Python function to continuously monitor stock levels against calculated reorder points, automatically tagging SKUs with actionable alerts (e.g., "Out of Stock", "Reorder Immediately").

• Visual Triage: Implemented strict color-coded KPI logic in Power BI, allowing supply chain directors to instantly identify the most critical stock shortages without parsing raw tables.

• Lead Time Profiling: Cross-referenced supplier lead times against category volume to identify potential bottlenecks in the procurement pipeline.

---

### Repository Contents:

• supplychainanalysisproj.py: The Python script containing the supply chain mathematics and feature engineering.

• inventory4bi.csv: The clean, structured dataset exported for the visualization layer.

• inventoryoptimizedash.pbix: The core Power BI dashboard file.

• Screenshot 2026-02-26 143057.png: A high-resolution export of the final interactive dashboard. <img width="1275" height="718" alt="Screenshot 2026-02-26 143057" src="https://github.com/user-attachments/assets/036f9148-03be-46b5-b284-cb7e3017e3d6" />
