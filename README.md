🎬 Netflix Shows Dashboard

An interactive Power BI dashboard analyzing Netflix's content library — breaking down movies vs. TV shows by rating, release trend, and country to reveal how the platform's catalog has grown and what content dominates it.

<img width="1014" height="574" alt="image" src="https://github.com/user-attachments/assets/1c1e1d91-c57c-4da8-939a-cce86ad63124" />

---------------------------------------------------------------------------

📌 Project Overview

This project explores the Netflix content catalog through a single-page Power BI dashboard. It gives a quick, filterable view of the split between movies and TV shows, how the content library has grown over time, what maturity ratings dominate the platform, and how content is distributed geographically.

---------------------------------------------------------------------------

🎯 Business Problem

A streaming catalog spanning thousands of titles is hard to make sense of in raw, row-level form. This dashboard consolidates that data into clear visuals so stakeholders can quickly answer:

- What's the overall split between movies and TV shows?
- How has content addition trended over the years?
- Which content ratings (TV-MA, TV-14, PG, etc.) are most common?
- Which countries produce the most Netflix content?
- How does content mix vary by show type, release year, and country?

---------------------------------------------------------------------------

📊 Dashboard Preview

<img width="1014" height="574" alt="image" src="https://github.com/user-attachments/assets/3d38a64c-fcc5-485c-98bf-b63e0e8dd92f" />


KPI Cards
- **Movies:** 6,131
- **Total Shows:** 8,808
- **TV Shows:** 2,676

Visuals
- **Total Shows by Type (donut)** — Movies (69.61%) vs. TV Shows (30.38%) split
- **Total Shows by Type (area/trend chart)** — content additions over release years, showing a sharp rise peaking around 1,147 titles before tapering off
- **Total Shows by Type (donut with center total)** — 4,403 combined total with the same movie/TV-show split, shown as a secondary summary view
- **Total Shows by Type (bar chart)** — breakdown by content rating: TV-MA (3,207), TV-14 (2,160), TV-PG (863), R (799), PG-13 (490), and further down to NR, G, NC-17, UR, and runtime-based ratings
- **Total Shows by Country (map)** — geographic distribution of content across countries worldwide

Interactive Filters
- **Show Type** slicer (All / Movie / TV Show)
- **Release Year** slicer
- **Country** slicer

------------------------------------------------------------------------

💡 Key Insights

- Movies make up the majority of the catalog at 69.61%, compared to 30.38% for TV shows.
- Content additions grew sharply in recent years, peaking at 1,147 titles before declining.
- TV-MA is the most common content rating (3,207 titles), followed by TV-14 (2,160) — indicating the catalog skews toward mature audiences.
- Content is distributed across a wide range of countries, visible via the global map view.
- Lower-frequency ratings like NC-17, UR, and short-runtime classifications make up a small share of the catalog.


---------------------------------------------------------------------

🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- Power Query (data cleaning/transformation)
- DAX (Data Analysis Expressions)
- Microsoft Excel / CSV (data source)

------------------------------------------------------------------------

📂 Repository Contents

| File | Description |
|------|-------------|
| `Netflix_Shows_Dashboard.pbix` | Power BI project file (data model, DAX, dashboard) |
| `Netflix Titles.csv` | Source content dataset |
| `assets/` | Dashboard screenshot used in this README |

---------------------------------------------------------------------

💼 Skills Demonstrated

Power BI Dashboard Development · Data Cleaning & Transformation · DAX Measures · KPI Design · Data Visualization · Geospatial Analysis · Content/Media Analytics
