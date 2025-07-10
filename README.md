# 🏨 Hotel Performance Analytics Dashboard - Power BI  
**Author:** Arun Kothandaraman  
**Last Updated:** July 8, 2025  
**Tool:** Power BI Desktop  
**File Type:** `.pbit` (Power BI Template)  
**File Name:** Hotel Analysis 04072025.pbit  
**Dataset:** Simulated Hotel Booking & Performance Metrics  

---

## 📊 Project Overview

This interactive Power BI dashboard provides deep insights into hotel performance across multiple properties. It is designed to support data-driven decision-making by tracking key hospitality KPIs.

---

## 🖼️ Dashboard Preview

![Hotel Dashboard Preview](https://github.com/ArunKothandaraman94/Hotel-Analysis-Report/blob/main/Hotel%20Analysis%20Image%2010072025.png?raw=true)

---

## 🔍 Key Features

- **Filters for Custom View:**
  - Hotel Name
  - Room Class
  - Year and Month

- **KPIs Tracked:**
  - ADR (Average Daily Rate)
  - RevPAR (Revenue per Available Room)
  - Occupancy %
  - Realisation %
  - DSRN & DBRN (Room Night Metrics)
  - Cancellations
  - Avg. Length of Stay

- **Interactive Visuals:**
  - Weekly Trends
  - Day-Type Revenue Analysis
  - Booking Platform Mix
  - Category-wise Revenue (Pie Chart)
  - Hotel-wise KPI Comparison Table

---

## 📈 Key Business Insights

This dashboard provides actionable insights to help optimize hotel operations and strategy:

- **📉 Revenue & Occupancy Trends**  
  Track fluctuations in occupancy % and RevPAR over time to improve pricing and room inventory decisions.

- **🚫 Cancellations Analysis**  
  Identify patterns and spikes in cancellation rates to reduce revenue leakage through targeted policies.

- **📊 Booking Channel Contribution**  
  Analyze revenue distribution across booking sources like OTAs, direct, and corporate channels.

- **🛏️ Room Class Insights**  
  Evaluate which room types perform best, helping guide marketing and upgrade investments.

- **🧳 Length of Stay Patterns**  
  Monitor stay duration trends to align staffing and service offerings with guest behavior.

- **🏨 Cross-Property Comparisons**  
  Benchmark performance across hotel locations to identify top performers and areas needing attention.

---

## 📁 Data Model

Structured using a star schema for optimized performance:

- **Fact Tables:**
  - `fact_bookings`
  - `fact_aggregated_bookings`

- **Dimension Tables:**
  - `dim_date`
  - `dim_hotels`
  - `dim_rooms`
  - `KPI_Icons`
  - `CF_Color`

---

## 📦 Download

👉 [Click here to download the Power BI Template (.pbit)](Hotel%20Analysis%2004072025.pbit)

> 💡 Note: This template does **not include actual data**. It is intended for demo purposes. Users can load their own hotel performance dataset to explore the visuals.

---

## 🧠 Business Use Cases

- Monitor multi-property hotel performance  
- Identify trends in occupancy and booking behavior  
- Evaluate revenue performance by channel  
- Reduce cancellations and optimize RevPAR  
- Support strategic decisions with reliable KPIs  

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**  
- Power Query for ETL  
- DAX for custom KPIs and measures  
- Custom icons and themes for enhanced UI  

---

## 📌 Note

This dashboard uses hypothetical data and is created for **portfolio demonstration** and **learning purposes only**.

---

## 🙌 Credits

Designed and developed by **Arun Kothandaraman**  
Feel free to fork, explore, and customize it for your own use.

---
