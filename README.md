# Business Employment Data Analysis

This project analyzes employment statistics from New Zealand's December 2024 quarter business dataset. The goal is to clean the data and perform basic exploratory analysis to identify trends across industries.

##  Contents
- `data/cleaned_business_employment_data.csv` — Cleaned dataset
- `plots/` — Visualizations from EDA
- `employment_analysis.py` — Python script to clean data and generate plots

##  Steps Performed
1. Removed empty and duplicate columns
2. Dropped rows with missing employment values
3. Performed EDA:
   - Distribution of job types
   - Top industries by employment
   - Time trend for the Construction industry

## How to Run
```bash
pip install pandas matplotlib seaborn
python employment_analysis.py
