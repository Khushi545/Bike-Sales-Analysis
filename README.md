# Bike-Sales-Analysis

An interactive **Bike Sales Dashboard** built entirely in **Microsoft Excel**, using PivotTables, PivotCharts, and Slicers to analyze customer demographics and purchasing behavior.

![Excel](https://img.shields.io/badge/Made%20with-Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📊 Overview

This dashboard visualizes bike sales data to help understand **who buys bikes and why**, based on customer attributes like income, gender, age, marital status, region, education, and commute distance.

It was built using **only native Excel features** — no VBA, no add-ins, no external tools — to demonstrate how far you can push Excel's built-in analytics and dashboard capabilities.

---

## 🧩 Features

- **Slicers** for interactive filtering by:
  - Marital Status (Married / Single)
  - Region (Europe, North America, Pacific)
  - Education (Bachelors, Graduate Degree, High School, Partial College, Partial High School)

- **PivotCharts:**
  - **Avg Income Per Purchase** — Bar chart comparing average income by gender, split by whether a bike was purchased
  - **Customer Age Brackets** — Line chart showing purchase count across Adolescent / Middle Age / Old age groups
  - **Customer Commute** — Line chart showing purchase count across commute distance ranges (0-1 miles to 10+ miles)

- **Dynamic filtering:** All charts and slicers are connected via PivotTable data sources, so selections update every visual simultaneously.

- **Clean, presentation-ready layout** styled with a custom title banner and consistent color theme.

---

## 🗂️ Workbook Structure

| Sheet | Description |
|---|---|
| `Dashboard` | Main interactive dashboard with slicers and PivotCharts |
| `Pivot Table` | Underlying PivotTables powering the charts |
| `Working Sheet` | Raw/cleaned source data used for analysis |

---

## 🛠️ Tools & Techniques Used

- Excel PivotTables & PivotCharts
- Slicers (linked across multiple PivotTables via Slicer Connections)
- Conditional formatting & custom styling
- Data cleaning and structuring on a dedicated working sheet

---

## 📈 Key Insights

- Customers who purchased a bike generally have a **higher average income** than those who didn't, across both genders.
- **Middle-aged** customers show the highest count of bike purchases compared to adolescents and older customers.
- Customers with **shorter commute distances (0-1 miles)** show a higher tendency to purchase bikes, with counts declining as commute distance increases.

---

## 🚀 How to Use

1. Download `Bike Sales Dashboard.xlsx` from this repository.
2. Open it in Microsoft Excel (2016 or later recommended for full Slicer support).
3. Use the **slicers** on the left (Marital Status, Region, Education) to filter the entire dashboard.
4. Use the **dropdown filters** above each chart (Gender, Age Brackets, Commute Distance, Purchased Bike) to drill further into each visual.

---

## 📌 Notes

This project was built purely as an Excel dashboarding exercise to practice:
- Data modeling with PivotTables
- Interactive dashboard design
- Visual storytelling with charts and slicers

---

## 📄 License

This project is open-sourced for learning and portfolio purposes. Feel free to fork and adapt it for your own datasets.
