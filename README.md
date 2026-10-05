# EV Market Intelligence Dashboard

## 📊 Project Overview

The **EV Market Intelligence Dashboard** is an interactive Power BI project developed to analyze electric vehicle market data and provide meaningful insights into sales performance, pricing, vehicle range, battery capacity, manufacturers, and yearly market trends.

The dashboard transforms raw EV data into an easy-to-understand business intelligence report using **Power Query for data preparation, DAX for calculations, and Power BI for interactive visualization**.

This project is designed to demonstrate practical **Data Analyst skills**, including data cleaning, data transformation, KPI development, exploratory analysis, dashboard design, and business insight generation.

---

## 🎯 Project Objective

The main objective of this project is to understand the EV market through different business and vehicle-level metrics.

The dashboard focuses on answering questions such as:

- Which manufacturers have the highest EV sales?
- Which EV models are the best-selling?
- How have EV sales changed over the years?
- What is the average price of EVs?
- What is the average driving range?
- What is the average battery capacity?
- How does vehicle price compare with driving range?
- How do different battery and charging types relate to the EV market?

---

## 📁 Dataset

The dataset contains **3,022 electric vehicle records** with information related to vehicle specifications, manufacturers, pricing, sales, battery characteristics, and charging information.

### Important columns used in the dashboard:

| Column | Description |
|---|---|
| Manufacturer | EV manufacturer |
| Model | EV model name |
| Year | Manufacturing/model year |
| Battery_Type | Type of battery used |
| Battery_Capacity_kWh | Battery capacity in kWh |
| Range_km | Vehicle driving range in kilometers |
| Charging_Type | Type of charging supported |
| Charge_Time_hr | Charging time in hours |
| Price_USD | Vehicle price in USD |
| Country_of_Manufacture | Country where the vehicle was manufactured |
| Units_Sold_2024 | Number of units sold |

---

## 🛠️ Tools & Technologies

- **Power BI** – Dashboard development and interactive visualization
- **Power Query** – Data cleaning and transformation
- **DAX** – KPI and analytical calculations
- **Data Visualization** – Business-focused charts and dashboard design

---

## 🔄 Data Preparation

The raw dataset was prepared using Power Query before creating the dashboard.

The main data preparation steps included:

1. Imported the EV dataset into Power BI.
2. Reviewed the available columns and selected relevant fields.
3. Checked and corrected data types.
4. Verified numerical fields such as price, range, battery capacity, and units sold.
5. Checked for missing values and data errors.
6. Reviewed duplicate records.
7. Prepared the cleaned dataset for visualization and analysis.

---

## 📐 DAX Measures

DAX measures were created to calculate the main KPIs used in the dashboard.

### Total Units Sold

```DAX
Total Units Sold =
SUM(EV_Data[Units_Sold_2024])
