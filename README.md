# 🚚 Porter Delivery Analysis Dashboard

An interactive operations and business performance dashboard analyzing order fulfillment, revenue metrics, driver workloads, and delivery speed for Porter delivery logistics.

---

## 📊 Business Metrics & KPIs

- **Total Orders Processed:** 75
- **Average Delivery Time:** 34.45 mins
- **Average Partner Load:** 77.05
- **Average Outstanding Orders:** 35.29
- **Average Order Size:** 3.8 items

---

## 🔑 Key Dashboard Features & Visualizations

1. **Revenue Analysis**
   - **Top Revenue By Day Wise:** Highlights peak demand dates (e.g., Feb 15 generating ~24.4k in revenue) to assist in inventory and fleet allocation.
   - **Hourly Wise Revenue:** Identifies peak revenue hours (strong spikes around 2 AM reaching ~53k revenue), helping optimize shift planning for drivers.

2. **Delivery & Logistics Performance**
   - **Avg Delivery Time By Day:** Tracks day-of-week efficiency, identifying Saturday as the peak delivery time day (42.5 mins) vs. Tuesday as the fastest (22.17 mins).
   - **Avg Delivery Time By Market Wise:** Evaluates geographic market performance (Markets 1–6) to pinpoint fulfillment bottlenecks.
   - **Avg Delivery Time By Number Of Quantity:** Analyzes how order volume impacts fulfillment times, showing higher delivery durations for orders containing 8+ items.

3. **Store & Pricing Performance**
   - **Store ID Wise Max & Min Prices:** Item price distribution across different store IDs to track order value ranges.

---

## 🛠️ Tech Stack & Tools Used

- **Excel / Power BI:** Dashboard design, KPI cards, and interactive slicers (Month, Day, Cuisine/Store Filters).
- **Data Modeling & Analysis:** Data aggregation, time-series analysis, and operational load metrics calculations.

---

## 📁 Project Structure

```text
├── data/
│   └── porter_delivery_data.xlsx   # Cleaned dataset
├── dashboard/
│   └── Porter_Delivery_Analysis.xlsx # Main dashboard file
├── screenshots/
│   └── dashboard_preview.png       # Dashboard screenshot
└── README.md
