# Netflix-content-strategy-analysis-
Analyzed 8,800+ titles across genres, countries, and ratings to uncover content patterns; built a 7-sheet Excel dashboard revealing International Movies as the top genre and TV-MA as the dominant rating.# 🎬 Netflix Content Strategy Analysis

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4c72b0)
![xlsxwriter](https://img.shields.io/badge/xlsxwriter-Excel%20Dashboard-217346)
![Level](https://img.shields.io/badge/Level-Beginner-brightgreen)

---

## 📌 Project Overview

This project performs a full analysis of the Netflix content catalog to uncover genre trends, country production patterns, content ratings, and viewership data. It is designed to answer the question a streaming strategy team would ask: **what content does Netflix produce, for whom, and what performs best?**

**Business Question:** What does Netflix's content library look like across genres, countries, and ratings — and what strategic patterns can we derive?

---

## 📂 Project Structure

```
Netflix_analysis(beginner)/
│
├── netflix_data.csv                          # Dataset — 8,807 titles (2015–2023)
├── Netflix_Content_Strategy_Analysis.ipynb   # 19-cell analysis notebook
└── README.md
```

---

## 📊 Dataset

| Attribute | Details |
|---|---|
| **Source** | Synthetic Netflix catalog dataset (modeled after real catalog) |
| **Records** | 8,807 titles |
| **Period** | 2015 – 2023 |
| **File** | `netflix_data.csv` |

**Columns:** `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `imdb_score`, `views_millions`, `description`

---

## 🎯 Project Objectives

1. Analyze content library split between Movies and TV Shows
2. Identify top-performing genres by title count, IMDb score, and viewership
3. Understand which countries produce the most content
4. Explore content rating distributions
5. Track year-over-year content additions (2015–2023)
6. Build a 7-sheet Excel dashboard with Netflix dark theme

---

## 🔧 Tools & Technologies

| Tool | Purpose |
|---|---|
| Python 3 | Core language |
| pandas | Data loading, cleaning, aggregation |
| NumPy | Numerical operations |
| Matplotlib | 10 visualizations (Netflix red/black theme) |
| Seaborn | Statistical plots |
| xlsxwriter | Excel dashboard generation |
| Jupyter Notebook | 19-cell structured analysis |

---

## 📈 Analysis Workflow (19 Cells)

| Cell | Description |
|---|---|
| 1 | Library imports (`xlsxwriter`, `pandas`, `matplotlib`, `seaborn`) |
| 2 | Synthetic dataset generation — saves `netflix_data.csv` |
| 3 | Load dataset, parse `date_added`, engineer `year_added` and `month_added` |
| 4 | EDA — content type split, top genres, top countries, ratings, IMDb stats |
| 5 | KPI calculations |
| 6 | Data aggregations — genre, country, yearly, rating summaries |
| 7 | Netflix dark theme setup (Netflix Red `#E50914`, Black `#221F1F`) |
| 8–17 | 10 charts (see below) |
| 18 | Executive summary text |
| 19 | Excel dashboard export (7 sheets) |

---

## 📊 Visualizations (10 Charts)

| # | Chart Type | What It Shows |
|---|---|---|
| 1 | Donut chart | Movie vs TV Show split |
| 2 | Bar chart | Titles added per year (2015–2023) |
| 3 | Horizontal bar | Top 10 genres by title count |
| 4 | Bar chart | Top 10 content-producing countries |
| 5 | Bar chart | Content ratings distribution |
| 6 | Histogram | IMDb score distribution with mean line |
| 7 | Horizontal bar | Avg IMDb score by genre (top 10) |
| 8 | Line chart | Monthly content additions (seasonal trend) |
| 9 | Bar chart | Total views by genre (millions) |
| 10 | Histogram | Movie duration distribution with mean line |

---

## 📋 Excel Dashboard — 7 Sheets

Output file: `Netflix_Content_Strategy_Dashboard.xlsx`

| Sheet | Contents |
|---|---|
| 📊 KPI Dashboard | 8 KPIs — Total Titles, Movies, TV Shows, Avg IMDb, Total Views, Top Genre, Top Country, Peak Year |
| 🎭 Genre Analysis | Genre table: title count, avg IMDb, total views |
| 🌍 Country Analysis | Top 15 countries by production volume |
| ⭐ Ratings & Duration | Rating distribution + movie runtime stats |
| 📅 Yearly Trends | Year-over-year content additions table |
| 🏆 Top 20 Titles | Highest-viewed titles with IMDb scores |
| 📋 Executive Summary | Written narrative of all key findings |

---

## 🔍 Key Findings (Verified from Dataset)

| KPI | Value |
|---|---|
| Total Titles | 8,807 |
| Movies | 3,469 |
| TV Shows | 5,338 |
| Avg IMDb Score | 6.8 |
| Top Genre | Horror (785 titles) |
| Top Country | United States |
| Peak Year | 2021 (1,610 titles added) |
| Avg Movie Duration | 108 minutes |
| Top Rating | TV-MA (3,129 titles) |

- **TV Shows (5,338) outnumber Movies (3,469)** in this catalog — Netflix's library is series-heavy
- **Horror** is the most-produced genre at 785 titles, followed by Comedy (775) and Thriller (770)
- Content additions **peaked in 2021** at 1,610 titles — pandemic-era investment
- **TV-MA** is the dominant rating (3,129 titles), confirming Netflix's adult-skewed strategy
- Average movie runtime is **108 minutes**

---

## 💡 Business Recommendations

1. **Horror and Thriller originals** offer the highest volume opportunity — already the top genres
2. **TV Shows drive more sessions** than movies — series strategy supports subscriber retention
3. **Q4 content drops** (Oct–Dec) show the lowest monthly upload volume — opportunity to differentiate
4. Korean and non-English originals noted in executive summary as having the **highest view-per-title ratio**

---

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib seaborn xlsxwriter

jupyter notebook Netflix_Content_Strategy_Analysis.ipynb
# Run all cells — Cell 2 generates the dataset, Cell 19 produces the Excel file
```

---

## 👤 Author

**[ABITHA ]** | [LinkedIn](https://www.linkedin.com/in/abitha-s-105663399?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app) | [GitHub](https://github.com/AbithaSenthil)
