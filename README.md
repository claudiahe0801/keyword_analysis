# 📈 Keyword Analysis for Google Ads

## Overview

This project aims to support paid search marketing by identifying high-performing keywords using SEMrush data. We analyzed keyword search volume, keyword difficulty, and intent to prioritize terms that balance competitiveness and business value.

## Data

* `Keywords.csv` / `Keywords.xlsx`: Contains search terms, volume, CPC, KD%, intent, and related metadata
* Source: SEMrush export for MyEdMaster's ad research (2024)

## Objectives

* Identify keywords with high volume and manageable difficulty
* Filter terms by commercial or transactional intent
* Recommend strategic keywords to optimize Google Ads targeting

## Tools

* Python (Pandas, Matplotlib)
* Jupyter Notebook
* SEMrush keyword data export

## Key Steps

1. **Data Cleaning**

   * Removed duplicates, handled missing values
2. **Intent Filtering**

   * Focused on Commercial/Transactional keywords
3. **Ranking Criteria**

   * Balanced high search volume with lower keyword difficulty (KD%)
   * Highlighted keywords with strong CPC or high-intent phrases
4. **Visualization**

   * Plotted scatter charts to identify high-opportunity keyword clusters

## Output

* `keywords_analysis.html`: Interactive notebook output
* Recommended keyword list (in notebook)

## Usage

Open `keywords_analysis.ipynb` in Jupyter to explore the full process and replicate the analysis on new keyword data.

## Author

Claudia (Yuxia He), 2025

---

Feel free to contribute or adapt this workflow for your own ad campaign optimization.
