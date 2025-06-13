# 🎮 Video Game Sales Analysis Dashboard (Tableau)

## 📊 Project Overview

This project visualizes global video game sales data using Tableau to uncover insights about sales trends by genre, platform, and over time.

The dashboard is built on the `vgsales.csv` dataset and provides two main visualizations:

- **Sheet 1**: A stacked bar chart displaying global and EU sales by genre across time (binned by year), with platform filter options.
- **Sheet 2**: A bar chart showing total global sales by genre.

---

## 📁 Dataset

**File**: `vgsales.csv`

**Columns include:**
- `Name`: Game title
- `Platform`: Console/platform (e.g., PS2, X360, etc.)
- `Year`: Year of release
- `Genre`: Game genre
- `Publisher`: Game publisher
- `NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`, `Global_Sales`: Sales in millions of units by region

---

## 📈 Dashboard Description

### Sheet 1: Sales Over Time by Genre & Platform
- **X-axis**: Year (binned)
- **Y-axis (top)**: Global Sales (EU only)
- **Y-axis (bottom)**: Global Sales (all regions)
- **Color**: Game genre
- **Filters**: Platform selection available via checkbox

This visualization helps in identifying sales trends by genre over time and platform-specific performance.

### Sheet 2: Global Sales by Genre
- **X-axis**: Game genres
- **Y-axis**: Global sales totals
- **Color**: Distinct color for each genre

This chart helps to quickly identify the top-selling game genres.

---

## 💡 Key Insights

- **Top Genres**: Action and Sports games lead in global sales.
- **Sales Peaks**: The early 2000s to late 2000s saw the highest game sales.
- **Platform Trends**: Users can toggle platforms to explore sales contributions across devices.

---

## 🛠 Tools Used

- **Tableau**: For data visualization and dashboard creation
- **Microsoft Excel / Google Sheets**: (Optional) For basic preprocessing or data cleaning
- **Dataset Source**: [Kaggle: Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogame-sales-with-ratings) (or similar)

---

## 🚀 Getting Started

1. Download `vgsales.csv`.
2. Open Tableau and load the dataset.
3. Create visualizations similar to Sheets 1 and 2.
4. Use filters, color legends, and tooltips to make the dashboard interactive.

---

## 📌 Future Improvements

- Add regional breakdown dashboards (e.g., Japan vs. EU).
- Include publisher-wise performance.
- Predictive trends using Tableau forecasting.
