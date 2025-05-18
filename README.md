# 📊 AtliQ Grands – Revenue Insights Dashboard

## 🧩 Problem Statement  
AtliQ Grands, a premium five-star hotel chain across India, is experiencing a decline in revenue and market share due to rising competition and poor decision-making. Lacking an in-house data analytics team, the company has outsourced data analysis to uncover valuable business insights.  
**Role**: As a data analyst, create metrics, build a dashboard, and provide strategic insights to support the revenue team’s decision-making.

---

## ✅ Key Metrics Overview (Week 27)

- **Revenue:** ₹1.69B ⬆ 0.2%
- **RevPAR (Revenue Per Available Room):** ₹7,337 ⬆ 0.2%
- **ADR (Average Daily Rate):** ₹12.70K ⬆ 0.2%
- **Occupancy Rate:** 57.8% ➖
- **DSRN (Daily Stay Room Nights):** 2,528 ⬆ 0.2%
- **Realisation Rate:** 70.1% ⬇ 0.0%

> % values indicate week-over-week change.

---

## 📅 Day Type Performance

| Metric        | Weekend   | Weekday   |
|---------------|-----------|-----------|
| RevPAR        | ₹7,972    | ₹7,083    |
| Occupancy %   | 62.6%     | 55.8%     |
| ADR           | ₹12,725   | ₹12,682   |
| Realisation % | 70.6%     | 69.9%     |

> Weekends are performing better across all key metrics.

> 📝 **Note**: In the hospitality industry, **Fridays and Saturdays are considered weekends**, while **Sundays through Thursdays are considered weekdays**.


---

## 🏙️ Revenue by Category

- **Luxury Segment:** 61.62%
- **Business Segment:** 38.38%

> Majority of revenue comes from luxury hotels; business segment shows potential for targeted growth.

---

## 🏨 Property-Level Insights

- **Top Earning Property:** AtliQ Seasons, Mumbai – ₹65M
- **Lowest Performing (Revenue):** AtliQ Blu, Bangalore – ₹22M despite high occupancy (72%)
- **Lowest Customer Rating:** AtliQ Grands, Bangalore – ⭐ 2.37
- **Highest Rated:** AtliQ Grands, Delhi – ⭐ 3.62

> Revenue is not always aligned with customer satisfaction—opportunity to improve services at low-rated, high-revenue properties.

---

## 🌐 Realisation & ADR by Booking Platform

| Platform     | Realisation % | ADR     |
|--------------|----------------|---------|
| Loginn       | 70.6%          | ~12.7K  |
| Journer      | 70.5%          | ~12.7K  |
| Direct       | 70.3%          | ~12.7K  |
| Others       | 70.2%          | ~12.8K  |
| Makeyr       | 69.9%          | ~12.6K  |
| Tripser      | 69.8%          | ~12.6K  |

> Direct and trusted platforms like Loginn and Journer offer high realisation. Tripser is underperforming.

---

## 🚨 Cancellation & Rating Overview

- **Average Cancellation Rate:** ~24.8%
- **Customer Satisfaction:** Ranges from 2.30 to 3.62 stars

> High cancellation rates and poor average ratings highlight customer dissatisfaction and need for operational improvements.

---

## 🧠 Key Recommendations

- Focus on service improvement in low-rated properties
- Drive corporate bookings to improve weekday occupancy
- Increase promotions for direct and high-yield platforms
- Identify and address root causes of high cancellation rates
- Use performance trends to implement agile pricing strategies

---

## ⚙️ Technical Implementation

### 🔎 Power Query
- Performed data cleaning, transformation, and shaping
- Removed nulls, formatted date columns, pivoted/unpivoted data
- Merged tables and created relationships for accurate reporting

### 📊 DAX (Data Analysis Expressions)
- Created calculated columns and measures:
  - `RevPAR = Revenue / Available Rooms`
  - `ADR = Revenue / Total Bookings`
  - `Occupancy % = (Room Nights Sold / Available Room Nights) * 100`
  - Week-over-week change calculations using `CALCULATE`, `PREVIOUSWEEK`, and `DIVIDE`
- Used `SWITCH`, `IF`, and `FILTER` for conditional logic in visuals

---

## 📂 Tools Used

- Power BI (Dashboard & Visualization)
- **Power Query** (ETL – Data Transformation)
- **DAX** (Custom Measures & Calculated Columns)
- Excel (Raw data formatting and reference)
