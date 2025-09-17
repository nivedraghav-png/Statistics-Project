# Statistics-Project
A step-by-step statistics assignment analyzing customer behavior and churn using Python.
# Customer Behavior Analysis.

## What’s inside
- `Statistics_Assignment_Step_by_Step.ipynb` — Q1–Q10 code + plots
- `statistics_project_solution.py` — script version (runs end-to-end)
- `Statistics_Assignment_Report.html` — polished report with interpretations
- `Statistics_Assignment_Report.md` — markdown report
- `requirements.txt` — dependencies
- `.gitignore` — ignores data files (CSV, etc.)

> Note: `customer_behavior.csv` is **not** committed (ignored by `.gitignore`). Keep your CSV locally.

## Dataset columns
`CustomerID, Gender, Region, PurchaseAmount, ProductCategory, Churn (Yes/No), CampaignGroup (A/B)`

## Questions & methods (Q1–Q10)
1) Mean / Median / Mode — descriptive stats  
2) Outliers — IQR fences + boxplot  
3) Skewness & Kurtosis — `scipy.stats.skew`, `kurtosis(fisher=True)`  
4) Gender difference — Welch’s t-test (+ Cohen’s d)  
5) Category × Churn — Chi-square (+ Cramér’s V)  
6) Regions — Levene, one-way ANOVA, Kruskal (+ η²)  
7) Campaign A vs B — Welch’s t (+ d)  
8) Normality — Shapiro–Wilk, Histogram, QQ-plot  
9) CLT — bootstrap sampling distribution of the mean (n=50)  
10) 95% CI — t-interval for the mean

## Quickstart
```bash

# or run the script directly
python statistics_project_solution.py
