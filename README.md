# 🏨 Hotel Booking Cancellation Analysis

A real-world business problem solved using data analytics.

## 🎯 Business Objective

Hotels face high cancellation rates → revenue loss + poor planning.
This project aims to:

- Identify key cancellation patterns
- Estimate revenue loss
- Recommend business strategies to increase profit

This is a business decision-making project, not just EDA.

## 📦 Dataset Overview

| Attribute | Details |
|-----------|--------|
| Total Rows | 119,000+ |
| Time Period | 2015–2017 |
| Target Variable | is_canceled (0 = No, 1 = Yes) |
| Major Features | adr, lead_time, hotel, market_segment, customer_type, stays_in_week_nights, reservation_status_date |
| Source | Kaggle – Hotel Booking Demand Dataset |

## 🔁 Project Workflow

<p align="left">
🧠 <b>Business Problem</b><br>↓<br>
📥 <b>Load & Explore Data</b><br>↓<br>
🧹 <b>Data Cleaning & Preprocessing</b><br>↓<br>
📊 <b>Exploratory Data Analysis (EDA)</b><br>↓<br>
📈 <b>Revenue & KPI Calculation</b><br>↓<br>
🔍 <b>Generate Insights</b><br>↓<br>
📌 <b>Business Strategy & Action Plan</b><br>
</p>




## 🧹 Data Cleaning Summary

- Converted reservation dates to datetime
- Dropped high-null columns: company, agent
- Removed outliers (adr > 5000)
- Removed all missing values
- Created new metric: total_revenue
- Final dataset clean and ready for EDA

## 💰 Revenue Impact

| Metric | Value (₹) |
|--------|----------|
| Estimated Revenue Lost | ₹16,705,837.66 |
| Revenue Earned | ₹25,908,964.82 |
| Avg. Revenue per Booking | ₹358.42 |
| Target After Optimization | ₹420+ |

*Interpretation:*
- Only 61% of potential revenue is realized.
- A 10% reduction in cancellations → ₹4–8 crore annual gain.

## 🔎 Business Insights

| Finding | Meaning |
|---------|---------|
| High cancellations (37.2%) | Major revenue leak |
| City Hotels cancel more | Lower reliability |
| OTA & Group bookings cancel most | Price-sensitive users |
| Direct bookings cancel least | Promote this channel |
| High ADR ↑ → Cancellations ↑ | Pricing issue |
| Seasonal spikes | Forecasting needed |

## 💡 Business Recommendations

| Problem | Recommendation |
|---------|---------------|
| OTA/Group users cancel often | Retention offers |
| High ADR months | Dynamic pricing |
| Low direct bookings | Loyalty program |
| OTA listing issues | Better photos & info |
| Seasonal cancellation trend | Forecast & adjust |

## 📈 Expected Business Impact

| Metric | Current | Target |
|--------|---------|--------|
| Cancellation Rate | 37% | 25–28% |
| Avg. Revenue/Booking | ₹358 | ₹420+ |
| Direct Bookings | 18% | 30% |
| Revenue Lost | ₹1.67 Cr | ↓ 35% |

## 📂 Project Structure

### 📁 Project Structure

```bash
Hotel-Booking-Analysis/
│
├── 📂 data/                          # Raw dataset
│   └── hotel_bookings.csv
│
├── 📂 notebooks/                     # Analysis notebook
│   └── hotel_booking.ipynb
│
├── 📂 images/                        # Visualizations for README
│   ├── cancellation_percentage.png
│   ├── hotel_cancellation.png
│   ├── adr_trend.png
│   ├── monthly_cancellation.png
│   └── revenue_comparison.png
│
├── 📄 README.md                     
```



## 🧠 **Conclusion**

> 📌 _This analysis proves that **data can directly improve hotel profitability**._

### 🔍 **Key Takeaways**
- 📉 **Reducing cancellations by even 10% creates massive revenue benefits**
- 📊 The strategies are **practical, data-backed, and immediately applicable**

---

### 🏨 **What Hotels Should Implement**

| ✔️ Action | 💡 Purpose |
|-----------|------------|
| Prioritize direct bookings | More reliable & high-profit customers |
| Apply demand-based pricing | Reduce cancellations during high ADR months |
| Use targeted retention strategies | Improve loyalty & reduce churn |

---

### 📌 **Final Statement**

> 💡 **This project is not just analysis — it's a business strategy ready for implementation.**  
> A small improvement in **pricing + customer retention** can recover **crores in lost revenue every year.**

---



## 📬 Contact

*Name:* Veeresh Chikkamath  
*Email:* veereshc0704@gmail.com

[LinkedIn](https://www.linkedin.com/in/veereshchikkamath) | [GitHub](https://github.com/veereshchikkamath7)
