# 🏨 Hotel Booking Demand Analysis

## 📌 Project Overview
This project performs an end-to-end exploratory data analysis (EDA) on the Hotel Booking Demand dataset to understand booking behavior, seasonal demand patterns, and cancellation drivers across different hotel types and customer segments.

The main objective is to identify:

- Seasonal booking patterns across months  
- Cancellation behavior and its key drivers  
- Differences between hotel types (City Hotel vs Resort Hotel)  
- Customer segment behavior and reliability  
- Country-level booking and cancellation patterns  

---

## 🧹 Data Cleaning
The following preprocessing steps were applied:

- Checked and handled missing values in key columns (`country`, `agent`, `company`)
- Filled missing `country` values with `"Unknown"`
- Replaced missing `agent` and `company` values with `0`
- Ensured dataset consistency for analysis
- Verified data quality after cleaning

---

## 🔧 Feature Engineering
To improve time-based analysis:

- Created a unified `arrival_date` column using year, month, and day information
- Converted the column into proper datetime format
- Ordered months chronologically to support correct seasonal analysis

---

## 📊 Exploratory Data Analysis
The analysis includes:

- Monthly booking distribution across hotel types (pivot table + heatmap)
- Monthly cancellation rate trends
- Lead time comparison between cancelled and non-cancelled bookings
- Top countries by booking volume
- Market segment behavior analysis
- Average daily rate (ADR) trends across time

---

## ❌ Cancellation Analysis
A deep dive into booking cancellations was performed:

- Cancellation rates across hotel types
- Relationship between lead time and cancellation likelihood
- Country-level cancellation behavior
- Market segment-based cancellation patterns

Key focus: understanding what drives booking instability and revenue loss.

---

## 🌍 Customer & Market Analysis
A segmentation-based analysis was conducted:

- Booking distribution across market segments
- Cancellation behavior by segment
- Country-wise booking concentration
- Identification of high-volume and high-risk customer groups

This helps in understanding which customer groups are more valuable and stable.

---

## 🏨 Hotel Type Analysis
Comparison between hotel types revealed:

- Different seasonal demand patterns
- Different cancellation behaviors
- Variation in pricing (ADR trends)
- Different customer segment dominance

This shows that City Hotel and Resort Hotel require different revenue strategies.

---

## 📈 Visualizations
The project includes:

- Heatmaps (Month × Hotel booking distribution)
- Line charts (monthly cancellation trends)
- Bar charts (top countries by bookings)
- Pie charts (market segment distribution)
- Dual-axis charts (ADR + demand trends)

---

## 🛠️ Technologies Used
- Python  
- pandas  
- matplotlib  
- seaborn  

---

## 📌 Key Outcome
This analysis provides actionable insights for hotel revenue management, helping optimize pricing strategies, reduce cancellations, and improve overall occupancy performance through data-driven decision making.
