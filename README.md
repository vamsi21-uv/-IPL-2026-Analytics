# -IPL-2026-Analytics
End-to-end IPL 2026 analytics project — ETL, SQL, Python
# 🏏 IPL Squad Performance Analytics

## About This Project

I'm a fresher learning data analytics and  built this project 
to go beyond tutorials and work on 
something that felt like actual analyst work.
The idea was simple — instead of working on a generic dataset, 
I wanted to build something that felt like real analyst work.

So I picked a problem: how does an IPL franchise decide who 
to buy at auction? I sourced real ball-by-ball data, built 
the pipeline myself, and tried to answer that question using 
SQL and Python.

## What I Did

- Found and downloaded ball-by-ball IPL data from Cricsheet.org
- Wrote Python to open a ZIP of 1,243 JSON files and parse 
  each match into flat tables
- Loaded 295,732 deliveries into SQLite
- Wrote 10 business queries covering batting, bowling, 
  venues and phase analysis
- Built clean datasets and published them on Kaggle

## What I Learned

This project taught me that real data is messy. For example, 
I discovered that run outs were inflating bowler wicket counts 
and had to fix it using CASE WHEN filters. After the fix, 
my numbers matched official IPL 2026 records exactly.

## Tech Stack

- **Python** — zipfile, json, pandas
- **SQLite** — business queries
- **Matplotlib** — basic visualizations
- **Data Source** — Cricsheet.org (CC BY-SA 4.0)

## Files

- IPL_2026_Analysis.ipynb — main notebook
- matches_2026.csv — match results
- batsman_2026.csv — batting stats per match
- bowler_2026.csv — bowling stats per match

## SQL Skills Practiced

GROUP BY · HAVING · CASE WHEN · Subqueries · 
Window Functions · RANK · ROW_NUMBER · PARTITION BY · JOINs

---
*Data sourced from Cricsheet.org under CC BY-SA 4.0 license*
