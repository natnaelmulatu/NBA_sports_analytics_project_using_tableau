# 🏀 NBA Sports Analytics & Performance Dashboard

---

## 📋 Executive Summary

An end-to-end sports analytics project exploring National Basketball Association (NBA) player performance metrics, team efficiency ratings, and advanced game statistics. Built to translate complex multi-dimensional basketball data into intuitive, actionable visual narratives using **Tableau**, backed by optimized **Hyper extracts** and custom data cleaning pipelines.

---

## 🎯 Project Objectives & Business Questions

The primary goal of this project is to uncover hidden efficiencies and trends in modern NBA gameplay by addressing key analytical questions:

1. **Player Valuation & Efficiency:** How do player usage rates correlate with true shooting percentages (TS%) and offensive rating?
2. **Team Tactical Trends:** What measurable stylistic differences distinguish elite playoff contenders from lottery teams across pace, defensive rating, and spacing?
3. **Shot Selection & Spatial Analytics:** Where on the court do teams maximize expected points per possession (xPPP), and how has shot distribution shifted over recent seasons?

---

## 🛠️ Tech Stack & Data Architecture

* **Data Extraction & Ingestion:** Custom scripts parsing raw game logs and box scores into structured formats.
* **Storage & Optimization:** Tableau Hyper files (`.hyper`) for lightning-fast in-memory analytical queries and high-performance extracts.
* **Visualization & BI:** Tableau Desktop / Public (`.twb`) featuring dynamic parameters, custom calculated fields, tooltips, and responsive dashboard layouts.
* **Version Control:** Git & GitHub for asset and project management.

---

## 📁 Repository Structure

```text
├── NBA_Dataset.csv                             # Intial dataset that was given (Table format)
├── NBA_Dataset.txt                             # Initial dataset that was given (Text format)
├── NBA_Sports_Analytics_Project.twb            # Dashboard created for analysis 
└── README.md                                   # Project documentation and guide

```

---

## 📊 Key Dashboard Features

* **Interactive Player Profiler:** Deep-dive view comparing individual player performance benchmarks against league-average baselines using synchronized filters for position, minutes played, and usage tier.
* **Team Efficiency Quadrant:** Scatter plot matrix mapping Offensive Rating vs. Defensive Rating to instantly categorize league tiers (e.g., Championship Contenders, Rebuilding, Offensive Powerhouses).
* **Spatial Shooting Heatmaps:** Visual breakdown of shooting efficiency by zone (Paint, Mid-Range, Corner 3, Above-the-Break 3).

---

## 📈 Key Insights & Findings

* **The 3-Point Efficiency Trade-off:** High-volume 3-point shooting teams demonstrate a tighter variance in regular-season win shares, highlighting how reliance on variance can introduce volatility in playoff series.
* **Usage vs. Efficiency Curve:** Diminishing returns become apparent once a player's usage rate exceeds 30% without an elite secondary playmaker on the floor, impacting overall team net rating.

