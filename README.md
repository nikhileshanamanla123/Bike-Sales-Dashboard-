# 🚲 Bike Sales Dashboard

Basic Bike Sales Dashboard using Excel basic formulas and the charts.

An interactive Excel dashboard that analyses who buys bikes, based on a customer dataset of 1,000 records. It uses simple Excel formulas, Pivot Tables, and charts, so it's a good beginner-friendly data analysis project.

## 📁 Files

| File | Description |
|------|-------------|
| `Bike_Sales_Dashboard_Excel_Project.xlsx` | The complete Excel workbook |

## 📊 Workbook Structure

| Sheet | Purpose |
|-------|---------|
| **bike_buyers** | Raw dataset (original data, untouched) |
| **Working sheet** | Cleaned copy of the data: `M/S` and `M/F` codes expanded to *Married/Single* and *Male/Female*, plus a new **Age Brackets** column |
| **Pivot Table** | Pivot tables that summarise the data |
| **Dashboard** | Final dashboard with charts and slicers |

## 🧾 Dataset Columns

ID, Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age, Purchased Bike

## 🛠️ What Was Done

1. **Data cleaning**: copied raw data to a working sheet, replaced abbreviations with full labels, and checked for duplicates.
2. **Age brackets using an `IF` formula**:
   ```excel
   =IF(L2>54,"Old",IF(L2>=31,"Middle Age",IF(L2<31,"Adult","Invalid")))
   ```
   - Adult: under 31
   - Middle Age: 31 to 54
   - Old: over 54
3. **Pivot tables** for:
   - Average income by gender and bike purchase
   - Bike purchases by age bracket
   - Bike purchases by age
   - Bike purchases by commute distance
4. **Charts** (bar and line) built from the pivot tables.
5. **Dashboard** combining the charts, with slicers for interactive filtering.

## 💡 Skills Demonstrated

- Data cleaning and preparation
- Nested `IF` formulas
- Pivot Tables and Slicers
- Bar and line charts
- Dashboard layout and design

## 🚀 How to Use

1. Download `Bike_Sales_Dashboard_Excel_Project.xlsx`.
2. Open it in Microsoft Excel (slicers need Excel 2013 or later).
3. Go to the **Dashboard** sheet and use the slicers to filter the charts.

> Note: Slicers and pivot tables may not work fully in Google Sheets or LibreOffice.

## 👤 Author

Nikhilesh Anamanla
