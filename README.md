# 🏔️ Pakistan Tourism & Hospitality Analytics 

**Strategic Dashboard Analyzing 6 Years of Hotel Bookings, Revenue & Demographics (2020–2025)**

[![Status](https://img.shields.io/badge/Project_Status-Completed-success?style=flat-square)](#)
[![Excel](https://img.shields.io/badge/Data_Processing_&_Visualization-MS_Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)](#)
[![Region](https://img.shields.io/badge/Region-Pakistan-01411C?style=flat-square)](#)

</div>

<br>

##  Executive Summary
This project delivers a comprehensive, interactive analysis of Pakistan's tourism and hospitality sector. By extracting and cleaning raw hotel data from major cities and provinces, this dashboard empowers stakeholders to track **occupancy trends, revenue streams, foreign vs. local footfall, and seasonal demand** to drive data-backed growth strategies.

---

## 🛠️ The Data Pipeline & Snapshots

### 1. Raw Data Assessment
The initial dataset contained 6 years of nationwide hospitality records. It required extensive cleaning due to unformatted numeric metrics, missing structural consistency, and unstandardized geographic parameters.

<div align="center">
  <img src="Pakistan_Tourism_Dashboard (Excel)/Messy Tourism Data.PNG" alt="Raw Messy Data" width="850">
</div>

### 2. ETL & Feature Engineering
Transformed the chaotic raw data into a structured schema. Standardized all monetary figures to **PKR**, cleaned region names (Sindh, Punjab, KPK, Balochistan, ICT), and engineered custom metrics like **Average Daily Rate (ADR)** and **Occupancy Ratios**.

<div align="center">
  <img src="Pakistan_Tourism_Dashboard (Excel)/Cleaned Tourism_Data.PNG" alt="Cleaned Data" width="850">
</div>

### 3. Interactive Visualization
Developed a dynamic, custom Navy Blue themed dashboard. Integrated geo-mapping for provinces and cross-filtering slicers allowing users to drill down by *City, Customer Type, and Year*.

<div align="center">
  <img src="Pakistan_Tourism_Dashboard (Excel)/Tourism Analysis_Dashboard.PNG" alt="Final Dashboard" width="850">
</div>

---

## 💡 Key Performance Indicators (KPIs)

*   💰**Total Revenue:** 1.16 Billion PKR
*   🏷️ **Average Daily Rate (ADR):** 14,083 PKR
*   🛏️ **Total Rooms Booked & Guests:** 81,776
*   📈 **Average Occupancy Rate:** 51.90%
*   ⭐ **Customer Rating Average:** 3.72 / 5.0

---

## 🎯 Core Strategic Insights

| Category | Insight Breakdown |
| :--- | :--- |
| **🌍 Demographics** | Major urban centers like **Islamabad and Lahore** attract a balanced mix of both local and international visitors, while specific regions rely heavily on domestic tourism. |
| **📅 Seasonal Demand** | **Autumn and Winter** represent the absolute peak seasons for hotel bookings, driven by favorable weather and domestic holidays. |
| **🏨 Booking Channels** | **Booking.com** alongside **Walk-in** reservations are the dominant revenue drivers, outperforming AirBnb and direct website bookings. |
| **👥 Customer Segments** | **Business travelers** yield the longest average stay durations, providing steady revenue, whereas **Tour Groups** drive high volume in shorter bursts. |

---

## ⚙️ Core Technology Stack

*   **Microsoft Excel:** Initial data wrangling, conditional formatting, and exploratory data analysis.
*   **Power Query:** Automated ETL processes, data type normalization, and column merging.
*   **DAX (Data Analysis Expressions):** Custom calculations for ADR, Occupancy Rates, and Date Intelligence.
*   **Power BI:** Visual dashboarding, interactive mapping, and dynamic storytelling.

---

## 📥 Run the Project Locally

To explore the dashboard and datasets on your own machine:

1. **Clone the Repository**
   ```bash
   git clone [https://github.com/your-username/pakistan-tourism-dashboard.git](https://github.com/your-username/pakistan-tourism-dashboard.git)
