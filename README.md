# 🚗 Uber NCR Ride Bookings Dashboard | Power BI

> An interactive 6-page Power BI dashboard analyzing 150,000+ ride bookings to uncover demand-supply gaps, cancellation drivers, and revenue opportunities for a ride-hailing operation in the National Capital Region (NCR).

---

## 📌 Project Overview

This project dives into a full year of Uber ride-hailing data (Jan–Dec 2024) covering **150,000 bookings** across **7 vehicle types**. The goal was to move beyond raw numbers and answer critical operational questions: *Why are only 62% of bookings completed? Where is demand concentrated? Which vehicle categories drive the most value?*

The final output is a **6-page interactive Power BI dashboard** with a custom navigation menu, designed for operations and business teams to monitor KPIs and make data-backed decisions.

---

## 💡 Key Insights (The "So What?")

- **⚠️ The Funnel Leak**: Only **62% (93K) of bookings were completed**. A massive **18% (27K) were cancelled by drivers**, while 7% were cancelled by customers, and 7% had no driver found.
- **⭐ Rating Insights**: Across all vehicle types, **Uber XL** maintains the highest average customer and driver ratings, while **Go Sedan** has the lowest. *(See Page 4)*
- **💰 Revenue & Payments**: Average booking values are relatively consistent across UPI, Credit Card, Cash, and Debit Card (~₹500-₹511). However, **Uber Wallet** shows a starkly lower average booking value (~₹102). *(See Page 5)*
- **🚗 Vehicle Performance**: **Auto** is the highest utilized vehicle type with over **37K cancelled rides**, indicating a high volume of demand but potential supply/driver issues. *(See Page 6)*

---

## 🖼️ Dashboard Preview

*(Note to Kedar: Save your 6 screenshots as `page1.png`, `page2.png`, etc., and put them in an `images` folder in your repo. Replace the links below!)*

**1. Home / Navigation Page**
![Home Page](link_to_your_first_screenshot)

**2. Overall Performance (Executive Summary)**
*Tracks total bookings (150K) over time, booking status breakdown, and monthly trends.*
![Overall Page](link_to_your_second_screenshot)

**3. Cancellation Analysis**
*Deep dive into customer and driver cancellation reasons, with monthly breakdowns.*
![Cancellation Page](link_to_your_third_screenshot)

**4. Rating Analysis**
*Compares average customer and driver ratings across different vehicle types.*
![Rating Page](link_to_your_fourth_screenshot)

**5. Revenue & Payments**
*Analyzes average booking value by payment method and cancellation counts by payment type.*
![Revenue Page](link_to_your_fifth_screenshot)

**6. Vehicle Type Breakdown**
*Examines average booking value and cancellation volumes per vehicle type (Auto, Go Mini, Bike, etc.).*
![Vehicle Page](link_to_your_sixth_screenshot)

---

## 🛠️ Tech Stack & Methodology

| **Category** | **Tools & Techniques** |
| :--- | :--- |
| **Data Cleaning & Modeling** | Power Query (ETL), Data Validation |
| **Visualization** | Power BI Desktop (DAX, Custom Navigation, Slicers) |
| **Data Source** | `ncr_ride_bookings.csv` (150,000 records) |
| **Analysis Focus** | Funnel Analysis, Cancellation Drivers, Time-Series Trends |

**Methodology:**
1. **Data Profiling**: Cleaned and structured 150K rows of ride data.
2. **DAX Measures**: Created custom measures for Total Bookings, Total Cancelled by Driver, and Average Booking Value.
3. **UI/UX Design**: Built a custom navigation menu using page navigator buttons, allowing users to seamlessly jump between the Home page and specific analytical views (Cancellation, Revenue, Ratings, etc.).

---

## 📂 Repository Structure

```plaintext
UBBER_REPORT/
│
├── README.md
├── UBERPROJECTCLASS.pbix         ← Main Power BI file
├── ncr_ride_bookings.csv         ← Raw dataset
└── images/                       ← Dashboard screenshots
