# Capstone Project: Gender Differences in NCD Mortality Rates

## 📘 Overview
This project was developed as part of the "Introduction to Big Data Analytics" Capstone at [Your Institution or Course Name]. The main objective is to explore gender-based disparities in Non-Communicable Disease (NCD) mortality rates across WHO regions over time. The project integrates both Python-based exploratory and machine learning analysis, along with interactive visualization through Power BI.

---

## 🧠 Problem Statement
"What are the gender differences in NCD mortality rates across countries and over time?"

Understanding how mortality rates differ between males and females due to NCDs (such as cardiovascular diseases, diabetes, chronic respiratory diseases, and cancer) can guide more equitable global health interventions.

---

## 📂 Folder Structure

NCD_Mortality_Project/

├── data/

│ └── ncd_gender_cleaned.csv

├── notebooks/

│ └── analysis.ipynb

├── dashboard/

│ └── NCD_Mortality_Report.pbix

├── presentation/

│ └── capstone_presentation.pptx

└── README.md



---

## 📊 Dataset Description
- Source: World Health Organization (WHO)
- File Used: `NCD_Mortality_Rate.csv`
- Dimensions:
  - `Country`: WHO-defined region (e.g., Africa, Europe)
  - `Year`: Reporting year
  - `Sex`: Gender category (`Male`, `Female`, `Both`)
  - `NCD_Mortality_Rate`: Mortality rate due to NCDs

---

## 🔧 Python Workflow Summary

### ✅ 1. Data Cleaning
- Selected relevant columns
- Replaced coded values for gender
- Removed nulls and formatted year column

### ✅ 2. Exploratory Data Analysis (EDA)
- Descriptive statistics for male and female mortality
- Time series line plot of average NCD mortality by sex
- Bar chart of male-female mortality differences for the latest year

### ✅ 3. Clustering (Modeling)
- KMeans clustering on average NCD mortality rates by sex per country
- 3 clusters discovered and visualized
- Evaluated using silhouette score

---

## 📉 Power BI Dashboard
- Visuals included:
  - Bar chart: NCD mortality by region and gender
  - Slicers: Year and Gender filters
  - (Map visuals attempted but omitted due to regional rather than country-level data)

---

## 📈 Key Insights
- On average, males exhibit higher NCD mortality rates than females.
- Regions like Africa and South-East Asia show the greatest gender disparities.
- Clustering reveals region groupings with similar gendered mortality patterns.

---

## 📁 Output Files
- `ncd_gender_cleaned.csv`: Used for both Power BI and modeling
- `analysis.ipynb`: Full Python analysis
- `NCD_Mortality_Report.pbix`: Dashboard
- `capstone_presentation.pptx`: Final slide deck (see /presentation folder)

---

## 🏁 Conclusion
This project demonstrates how gender disparities in NCD mortality can be explored through both statistical and machine learning approaches. The interactive dashboard and Python modeling provide a comprehensive picture for both technical and non-technical stakeholders.

---

## 🔗 Acknowledgments
- WHO Global Health Observatory: https://www.who.int/data/gho
- Powered by: Python, pandas, seaborn, scikit-learn, Power BI

