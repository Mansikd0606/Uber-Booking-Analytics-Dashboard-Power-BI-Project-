# 🚖 Uber Booking Analytics Dashboard (Power BI Project)

## 📌 Project Overview

This project focuses on building an **interactive Power BI dashboard** to analyze Uber booking data. The goal is to extract meaningful insights from raw data by performing data cleaning, transformation, and visualization.

The entire project was developed using **Power BI**, leveraging **Power Query** for data preprocessing and **DAX (Data Analysis Expressions)** for creating key performance indicators (KPIs).

---
📂 Dataset Description

The dataset contains ride booking information including:

 - Pickup & Drop locations
 - Booking status (Completed, Cancelled, Incomplete)
 - Distance traveled
 - Revenue generated
 - Vehicle type
 - Booking timestamps
---
## 🛠️ Tools & Technologies Used

* **Power BI**
* **Power Query (ETL)**
* **DAX (Data Modeling & Measures)**

---

## 🔄 Data Preparation (Power Query)

Data cleaning and transformation steps performed:

* Removed null and duplicate values
* Standardized column formats (date, text, numeric)
* Handled missing or inconsistent entries
* Created derived columns for better analysis

---

## 📊 Key Measures (KPIs)

The following important metrics were created using DAX:

* 📍 **Average Distance**
* 📊 **Booking Count**
* ❌ **Booking Remove Status Filter**
* ✅ **Completed Bookings**
* 🚫 **Lost Bookings**
* 💰 **Total Revenue**
* 🛣️ **Total Distance Travelled**

---

## 📈 Dashboard Visualizations

### 🔹 Trend Analysis

* **Revenue by Month**
* **Completed Bookings by Month**

### 🔹 Category Analysis

* **Revenue by Vehicle Type**

### 🔹 Booking Status Distribution

* Donut Chart representing:

  * Completed Bookings
  * Cancelled Bookings
  * Incomplete Bookings

### 🔹 Key Insights (Cards)

* 🟢 **Top Pickup Location**
* 🔵 **Top Drop Location**

---

## 🎯 Key Insights from Dashboard

* Identified peak revenue months and booking trends
* Analyzed customer booking behavior and cancellation patterns
* Determined most preferred vehicle types
* Highlighted high-demand pickup and drop locations
* Evaluated operational efficiency through completed vs lost bookings

---
⚡ Challenges Faced

Here are strong, real-world challenges :

1. Data Cleaning Complexity
 - Raw data contained missing and inconsistent values
 - Required careful handling in Power Query to ensure accuracy

2. Handling Booking Status Logic
 - Different booking states (Completed, Cancelled, Incomplete) needed proper classification
 - Avoided double-counting while creating measures

3. Creating Accurate DAX Measures
 - Writing correct DAX formulas for:
    - Revenue calculation
    - Average distance
    - Lost bookings
 - Faced challenges with filter context and aggregation

4. Time-Based Analysis
 - Month-wise analysis required proper date formatting
 - Sorting months correctly (Jan–Dec) instead of alphabetical order

5. Designing User-Friendly Dashboard
 - Balancing visuals and avoiding clutter
 - Choosing the right charts for better storytelling

## 📸 Dashboard Preview

<img width="1482" height="801" alt="Uber Dashboard" src="https://github.com/user-attachments/assets/f8696d0d-8f07-4a12-9de2-db7072e5688b" />


---

## 🚀 How to Use

1. Download the `.pbix` file from this repository
2. Open it using **Power BI Desktop**
3. Interact with filters, slicers, and visuals to explore insights

---

## 📌 Future Improvements

* Add real-time data integration
* Include customer segmentation analysis
* Build predictive models for demand forecasting
* Enhance dashboard UI/UX with advanced visuals

---

## 📢 Conclusion

This project demonstrates how raw booking data can be transformed into actionable insights using Power BI. By applying data cleaning, modeling, and visualization techniques, the dashboard helps stakeholders understand booking trends, revenue patterns, and operational performance. It serves as a strong example of end-to-end data analysis for real-world business scenarios.
