# Women in STEM Analysis

## Project Overview

Analysis of gender representation in STEM fields across 117 U.S. cities (2015-2019).

**Key Findings:**
- Average women's representation: 27.3%
- Range: 10.1% to 44.1%
- Average gender pay gap: $6,298 (8.8%)

---

## Included Files

**Data:**
- `women_in_stem.csv` - Dataset (117 cities, 16 variables)
- `women_in_stem.ipynb` - Python analysis notebook

**Power BI:**
- `Women_in_STEM_Analysis.pbix` - Interactive dashboard
- `DAX_UPDATED_FIXED.dax` - All DAX formulas

**Presentations:**
- `Redi Project powerpoint.pptx`

**Documentation:**
- `README.md` - This file

---

## Instructions to Run the Analysis

### Python Analysis

**Requirements:**
```
pandas>=1.3.0
numpy>=1.20.0
matplotlib>=3.3.0
seaborn>=0.11.0
```

**Install:**
```bash
pip install pandas numpy matplotlib seaborn
```

**Run:**
1. Open `women_in_stem.ipynb` in Google Colab
2. Upload `women_in_stem_.xlsx.csv` when prompted
3. Run all cells

---

### Power BI Dashboard (Primary Analysis)

**Requirements:**
- Microsoft Power BI Desktop (Free)
- Download: https://powerbi.microsoft.com/desktop/

**Quick Setup (30 minutes):**

1. **Load Data** (5 min)
   - Open Power BI Desktop
   - Get Data → Text/CSV → Select `women_in_stem.csv`
   - Click "Load"

2. **Create Calculated Columns** (10 min)
   - Data view → New Column
   - Copy formulas from `DAX_UPDATED_FIXED.dax` 

3. **Create Measures** (10 min)
   - New Measure
   - Copy formulas from `DAX_UPDATED_FIXED.dax` 
   - Format as percentage/currency/number

4. **Verify** (5 min)
   - Total_STEM_Jobs: 2,513,000 ✓
   - Total_Women_STEM: 723,000 ✓
   - Avg_Pct_Women_STEM: 27.3% ✓


---

## Author

Adedokun Rohi Kunmi  

November 28, 2025

---
