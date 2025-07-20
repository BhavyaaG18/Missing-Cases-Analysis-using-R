# Missing Cases Analysis in India using R (2017–2021)

This project presents a comprehensive data analysis project on missing persons cases in India from 2017 to 2021. The goal is to examine patterns in missing, recovered, and unrecovered persons across different states and years using gender-disaggregated data.

## 📂 Contents

- 📄 `Report - Missing Cases.pdf`: A detailed PDF report covering the methodology, visualizations, and interpretations.
- 📁 `Missing Cases Complied (2017-2021).csv`: CSV containing the cleaned and merged dataset from 2017–2021.
- 📓 `R Code.ipynb`: Jupyter Notebook using R kernel for data processing, visualization, and interpretation.

---

## 📊 About the Dataset

- **Source**: [data.gov.in](https://data.gov.in/)
- **Title**: *State/UT-wise Total Missing and Traced Persons (2017–2021)*
- **Rows**: 180  
- **Columns**: 28  
- **Description**: This dataset integrates five yearly datasets for missing, traced, and untraced persons, segmented by gender. It includes rows with `NA` values (especially for transgender entries), which were handled in preprocessing.

---

## 🎯 Purpose

- Analyze and visualize trends in missing and recovered persons.
- Identify state-wise and year-wise variations.
- Examine patterns for different genders.
- Generate insights using bar plots, line plots, choropleth maps, and R data tables.

---

## 🛠️ Tools & Techniques

- **Language**: R
- **Environment**: Jupyter Notebook (IRkernel)
- **Visualizations**: 
  - Bar Plots
  - Line Charts
  - India Choropleth Maps

---

## 🔍 Key Insights

1. **Highest missing cases** were recorded in specific states and years, with females disproportionately affected.
2. **2020 shows a dip** in reported cases likely due to COVID-19 lockdowns.
3. **States with <60% recovery** include Punjab and Chandigarh.
4. **Transgender patterns** show increased recovery post-2019, possibly due to legislative support.
5. **Regional disparities** hint at underlying socio-economic and administrative differences.
