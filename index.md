---
title: Mengchen Wang | Data Science Portfolio
description: Portfolio of Mengchen Wang — data science projects, technical skills and key findings.
---

# Mengchen Wang

**Data Science Graduate Student, University of Macau**

Hello! I am a first-year graduate student in Data Science (Marketing Analytics)
at the University of Macau. I enjoy turning messy datasets into clear,
actionable insights — from exploratory analysis and visualization to
interactive dashboards and business-oriented analytics.

## Technical Skills

- **Programming:** Python (pandas, NumPy, matplotlib, plotly, Dash), SQL
- **Data Analysis:** exploratory data analysis (EDA), statistics, data cleaning,
  correlation analysis, time-series trends
- **Visualization:** matplotlib, plotly, Dash dashboards, GitHub Pages
- **Tools:** Jupyter Notebook, Git & GitHub, Anaconda

## Projects

### Automobile Sales Data Analysis (1980–2023)

**Research question:** How do automobile sales respond to economic recessions,
and which vehicle segments are affected the most?

Using an open IBM dataset of monthly US automobile sales (1980–2023, 4 states,
5 vehicle types), I analysed sales behaviour during recession periods and
compared it with non-recession periods. The analysis includes data cleaning,
exploratory statistics, recession vs non-recession comparisons, correlation
analysis of economic indicators, static visualizations, and an interactive
Dash dashboard.

**Key findings:**

- Average monthly sales drop by about **62.5%** during recession years
  (1,382 vs 3,680 units).
- The lowest average sales year was **1981** (549 units), reflecting the
  early-1980s recession.
- **Small Family Cars** are the best-selling segment overall (≈3,494 units),
  while Executive Cars sell the least (≈2,741 units).
- During recessions, sales correlate **negatively with the unemployment rate**
  (r ≈ −0.18), i.e. higher unemployment is associated with weaker demand.

**Visualization — average sales by vehicle type (recession vs non-recession):**

![Sales by Vehicle Type](https://raw.githubusercontent.com/wangmengchen61-cmyk/data-science-project/main/visualizations/sales_by_vehicle_type.png)

The chart shows that every vehicle segment sells fewer cars during recession
years. Small Family Cars remain the largest segment in both regimes, which is
consistent with their role as a necessity purchase, whereas Sports and
Executive Cars — more discretionary purchases — show the largest relative
declines.

**Project repository:** [github.com/wangmengchen61-cmyk/data-science-project](https://github.com/wangmengchen61-cmyk/data-science-project)

**Project status:** Completed (Oct 2026)
