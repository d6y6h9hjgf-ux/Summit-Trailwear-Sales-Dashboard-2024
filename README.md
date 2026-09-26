# Summit Trailwear Sales Dashboard — 2024

A Power BI sales dashboard analyzing a full year of apparel retail transactions across three stores, built to highlight seasonal trends, store performance, and product category insights.

## 📊 Overview

This project simulates one year (Jan 1 – Dec 31, 2024) of sales data for Summit Trailwear, an apparel retailer with three stores in climate-contrasting locations: Denver, Austin, and Seattle. The dataset includes roughly 53,225 transactions across 85 unique products in 9 categories, with realistic shopping patterns like weekday after-work peaks and shorter Sunday hours.

## 🏬 Stores

- **Denver**
- **Austin**
- **Seattle**

Stores were chosen specifically for climate contrast, to help surface seasonal buying pattern differences across regions.

## 👕 Product Categories

Outerwear, Knitwear, Tops, Bottoms, Dresses, Footwear, Accessories, Activewear, Swimwear

## 🛠️ Tools Used

- **Power BI Desktop** — data modeling, DAX measures, report design
- **DAX** — custom measures for sales, average order size, and trend analysis

## 🔍 Key Design Decisions

- Full calendar year of data (not a partial period) to properly capture seasonal trends across categories like Swimwear vs. Outerwear
- Realistic time-of-day and day-of-week shopping patterns, including weekday after-work peaks, a Saturday morning peak, and shorter Sunday hours (11am–6pm)
- Store open all 7 days a week
- Product structure kept 1:1 between product ID and product detail, including size, for clean joins in the data model

## 📷 Screenshots

**PAGE 1 - OVERVIEW**
<img width="2038" height="1144" alt="image" src="https://github.com/user-attachments/assets/4c23b2cb-3ce4-4ac4-a7fe-8305ca6c809e" />

**PAGE 2 - PRODUCT PERFORMANCE**
<img width="2038" height="1148" alt="image" src="https://github.com/user-attachments/assets/45653d3d-f102-477f-bcb8-761f2d9a2295" />


## 📂 Files

- [Summit Trailwear Sales Dashboard.pbix](Summit%20Trailwear%20Sales%20Dashboard.pbix) — the full Power BI report file

## 🚀 How to View

1. Download the `.pbix` file
2. Open it in [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
