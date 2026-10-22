# 🚗 Uber NCR Ride Bookings Dashboard | Power BI

> An interactive 6-page Power BI dashboard analyzing 150,000+ ride bookings to uncover demand-supply gaps, cancellation drivers, and revenue opportunities for an ride-hailing operation in the National Capital Region (NCR).

---

## 📌 Project Overview

This project dives into a full year of Uber ride-hailing data (Jan–Dec 2024) covering **150,000 bookings** across **7 vehicle types** and **176 pickup zones**. The goal was to move beyond raw numbers and answer critical operational questions: *Why are only 62% of bookings completed? Where is demand concentrated, and when? Which vehicle categories and payment modes drive the most value?*

The final output is a **6-page interactive Power BI dashboard** designed for operations and business teams to monitor KPIs, identify friction points, and make data-backed decisions to improve completion rates and resource allocation.

---

## 🎯 Business Problem & Objectives

Ride-hailing platforms lose revenue and customer trust when bookings are cancelled or left unfulfilled. This project addresses three core business questions:

1. **What is the overall health of the booking funnel?** (Completion vs. Cancellation rates)
2. **Who and what is causing cancellations?** (Driver vs. Customer, vehicle type, timing)
3. **Where is demand highest, and how can supply be optimized?** (Peak hours, high-demand zones, revenue-driving segments)

---

## 💡 Key Insights (The “So What?”)

After cleaning and modeling the data, the analysis surfaced several actionable findings:

- **⚠️ The Funnel Leak**: Only **62% of bookings were completed**, while **~25% were cancelled** — split between driver-side cancellations (18%) and customer-side cancellations (7%). This represents a significant revenue leakage point.
- **⏰ Peak Demand Window**: Demand consistently spikes between **5:00 PM and 7:00 PM**, indicating a clear opportunity for driver incentive programs and dynamic pricing during evening commute hours.
- **💰 Revenue Concentration**: The **Auto** vehicle type is the top revenue contributor, accounting for **~25% of the ₹4.7 Cr completed booking value**. UPI is the leading payment mode, used in **45%** of completed rides.
- **🗺️ Operational Blind Spots**: Certain pickup zones show disproportionately high cancellation rates, flagging areas where driver availability or customer wait-time communication needs improvement.

---

## 🛠️ Tech Stack & Methodology

| **Category** | **Tools & Techniques** |
| :--- | :--- |
| **Data Cleaning & Modeling** | Power Query (ETL), DAX (Measures, KPIs) |
| **Visualization** | Power BI Desktop (6-page interactive report) |
| **Data Source** | `ncr_ride_bookings.csv` (150,000 records, 21 fields) |
| **Analysis Focus** | Exploratory Data Analysis, Funnel Analysis, Time-Series Trends, Segmentation |

**Methodology at a glance:**
1. **Data Profiling & Cleaning**: Handled nulls, standardized vehicle types, and validated date/time fields for accurate trend analysis.
2. **Data Modeling**: Built a structured model to support drill-downs by vehicle type, pickup zone, booking status, and time period.
3. **DAX Measures**: Created dynamic KPIs for completion rate, cancellation rate, total booking value, and average fare.
4. **Dashboard Design**: Structured into 6 pages — Executive Summary, Booking Trends, Cancellation Analysis, Revenue & Payments, Vehicle Performance, and Zone-Level Insights.

---

## 🖼️ Dashboard Preview

*(Replace the placeholders below with actual screenshots from your `.pbix` file. This is the most important visual section — recruiters scan images before reading text.)*

| **Page 1: Executive Summary** | **Page 2: Booking Trends** |
| :---: | :---: |
| ![Executive Summary](https://via.placeholder.com/600x350?text=Executive+Summary+Snapshot) | ![Booking Trends](https://via.placeholder.com/600x350?text=Monthly+Booking+Trends) |

| **Page 3: Cancellation Analysis** | **Page 4: Revenue & Payments** |
| :---: | :---: |
| ![Cancellation Analysis](https://via.placeholder.com/600x350?text=Driver+vs+Customer+Cancellations) | ![Revenue](https://via.placeholder.com/600x350?text=Revenue+by+Vehicle+Type) |

> **Note**: The `.pbix` file is included in the repository. You can open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) to explore the full interactive experience.

---

## 📂 Repository Structure

```plaintext
UBBER_REPORT/
│
├── README.md                     ← Project documentation (this file)
├── UBERPROJECTCLASS.pbix         ← Power BI dashboard file (open with Power BI Desktop)
└── ncr_ride_bookings.csv         ← Raw dataset (150,000 ride bookings)
