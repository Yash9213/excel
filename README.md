# Dataset Overview – Price Summary Report

This repository contains an Excel dataset that provides a summarized view of product prices grouped by labels (likely product brands or categories). The data appears to be generated from a pivot table summarizing total prices for each label.

## 📄 File Included
- **de045222-89dc-4fb0-ba2e-f7e510550eaa.xlsx**  
  Contains two primary columns:
  - **Row Labels** – Represents product names, brands, or categories.
  - **Sum of Price** – Total aggregated price value associated with each label.

## 📊 Sample Data

| Row Label         | Sum of Price |
|-------------------|--------------|
| 109°F             | 199          |
| 24 Mantra         | 1045         |
| 5:15PM            | 2909         |
| A-1 Chips         | 70           |
| Aashirvaad        | 2527         |
| Aigner            | 17150        |
| Ajmal             | 42461        |

*(This is a preview extracted from the file.)*

## 🧾 Purpose
This dataset can be used for:
- Price aggregation studies  
- Brand-wise spending analysis  
- Market basket research  
- Reporting dashboards  
- Exploratory data analysis (EDA)

## 🔧 How to Use

### Python (Pandas)
```python
import pandas as pd

df = pd.read_excel("de045222-89dc-4fb0-ba2e-f7e510550eaa.xlsx")
print(df.head())
Excel / BI Tools
You can open the file directly in:

Microsoft Excel

Google Sheets

Power BI

Tableau

📈 Possible Extensions
Visualizing price distribution per brand

Identifying top-selling categories

Merging with SKU-level data

Creating dashboards or automated reports
author : Yash Kumar
