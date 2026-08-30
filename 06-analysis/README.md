# 06 — Analysis

Scripts, notebooks, and reports for analysing data and model outputs.

## What Goes Here

- Exploratory data analysis (EDA) notebooks
- Statistical analysis scripts
- Visualisation code and output figures
- Final analysis reports

## Structure

```
06-analysis/
  exploratory/   ← quick, iterative EDA notebooks
  statistical/   ← formal statistical tests and results
  figures/       ← generated plots and visualisations
  reports/       ← written summaries and findings
```

## Guidelines

- Notebooks in `exploratory/` are for investigation — keep them lightweight
- Promote reusable helper functions to a shared utilities module when possible
- Every figure should have a corresponding script that regenerates it
