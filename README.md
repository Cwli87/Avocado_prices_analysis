# Avocado Market Analysis Kaggle Dataset

## Project Overview
This project involves cleaning and analyzing the Avocado Prices dataset from Kaggle using Microsoft Excel. The goal was to explore pricing trends, regional differences, and volume patterns across avocado types, sizes, and bag categories.

---

## Problem Statement
The avocado market has seen significant price fluctuations over the years. This project aims to answer:
- How do organic and conventional avocado prices compare?
- How have avocado prices and volumes changed over time?
- Which regions have the highest average prices?
- Which avocado sizes and bag types sell the most?

---

## Project Roadmap
1. **Data Collection** Downloaded the Avocado Prices dataset from Kaggle
2. **Data Cleaning** Checked for blank cells, removed duplicates, formatted date and type columns
3. **Data Analysis** Built summary tables using AVERAGEIF, AVERAGEIFS, SUMIFS and SUM formulas
4. **Data Visualization** Created charts for price, volume, size, bags and region comparisons
5. **Documentation** Summarized findings in this README file

---

## Data Cleaning Steps
-  Checked for blank cells none found
-  Removed duplicates none found
-  Formatted Date column to YYYY-MM-DD
-  Verified type column only contains `organic` and `conventional`
-  Removed TotalUS and blank entries from region analysis
-  Separated analysis into a clean dedicated sheet

---

## Visualizations
| Chart | Description |
|-------|-------------|
|  Organic vs Conventional Price | Bar chart comparing average prices by type |
|  Price Over Time | Line chart showing yearly price trends (2015�2018) |
|  Total Volume by Year | Bar chart showing sales volume per year |
|  Volume by Size | Bar chart comparing Small (4046), Large (4225), XLarge (4770) |
|  Price by Size | Bar chart comparing average units by avocado size |
|  Small vs Large Bags | Bar chart comparing bag size volumes |
|  Volume by Region | Bar chart showing total volume across 53 regions |
|  Price by Region | Bar chart showing average price across 53 regions |

---

## Key Insights
-  **Organic avocados (~$1.65) cost about 42% more** than conventional ones (~$1.16)
-  **2017 had the highest average price** ($1.52) and highest total volume (~4.9 Billion units)
-  **2018 shows lower volume** due to partial year data in the dataset
-  **Small bags outsell large bags by 3x** (3.32B vs 991M units)
-  **Large avocados (4225) sell the most** compared to small and XLarge
-  **Regional differences** in both price and volume are significant across 53 US regions

---

## Key Learnings
- How to clean and validate data in Excel without any coding
- How to use AVERAGEIF, AVERAGEIFS, and SUMIFS formulas for data aggregation
- How to build and format professional charts in Excel
- How to use PivotTables to summarize large categorical data
- How to organize raw data and analysis into separate sheets for clarity

---

## Tools Used
- Microsoft Excel 365
- Kaggle Avocado Prices Dataset

---

## Dataset Source
[Avocado Prices Kaggle](https://www.kaggle.com/datasets/neuromusic/avocado-prices)
