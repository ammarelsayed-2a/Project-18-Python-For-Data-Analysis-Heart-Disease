# Project-18-Python-For-Data-Analysis-Heart-Disease
End-to-end Heart Disease EDA on 302 patient records | Analyzing risk factors: chest pain types, cholesterol, blood pressure, age, max heart rate &amp; exercise angina using Python, Pandas &amp; Seaborn

# 🫀 Heart Disease Data Analysis — Medical Dataset

An end-to-end Heart Disease Data Analysis project on 302 unique patient records, completed as part of the **Python for Data Analysis** course.

> ⚠️ **Medical Disclaimer:** This analysis is for educational and data science purposes only. It does not constitute medical advice.

## 📌 Objective
Analyze clinical risk factors, identify patterns between patient characteristics and heart disease diagnosis, and find the strongest predictors using correlation analysis.

## 📂 Dataset
- **Source:** HeartDiseaseData.csv
- **Original Records:** 1,025 rows
- **After Cleaning:** 302 unique patients (723 duplicates removed)
- **Features:** age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal, target

## 📋 Column Dictionary
| Column | Description |
|---|---|
| `age` | Patient age in years |
| `sex` | 1=Male, 0=Female |
| `cp` | Chest pain: 0=Typical Angina, 1=Atypical, 2=Non-anginal, 3=Asymptomatic |
| `trestbps` | Resting blood pressure (mm Hg) |
| `chol` | Serum cholesterol (mg/dl) |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina (1=Yes, 0=No) |
| `oldpeak` | ST depression induced by exercise |
| `ca` | Major vessels colored by fluoroscopy (0–3) |
| `target` | **1=Heart Disease, 0=No Heart Disease** |

## 🛠️ Tools & Libraries
| Library | Purpose |
|---|---|
| NumPy | Numerical operations |
| Pandas | Data cleaning, groupby, crosstab |
| Matplotlib | Bar charts, histograms, scatter plots, dashboard |
| Seaborn | Boxplots, heatmaps, pairplot |

## ❓ Analytical Questions

| # | Question |
|---|---|
| Q1 | How many patients have heart disease vs no heart disease? |
| Q2 | Average age of patients with vs without heart disease |
| Q3 | Are men more likely to have heart disease than women? |
| Q4 | Average cholesterol by disease status |
| Q5 | Relationship between Age and Max Heart Rate (thalach) |
| Q6 | Which chest pain type is most associated with heart disease? |
| Q7 | Does high blood pressure relate to heart disease? |
| Q8 | Strongest variables correlated with heart disease |
| Q9 | Is exercise-induced angina more common in disease patients? |
| Q10 | Characteristics of the highest-risk patients |

## 💡 Key Insights
- Dataset had 70% duplicate rows — reduced from 1,025 to 302 after cleaning
- Asymptomatic chest pain (cp=3) has the HIGHEST heart disease rate
- thalach (max heart rate) is the strongest negative predictor
- oldpeak and ca are the strongest positive predictors
- Exercise-induced angina patients have 3x higher heart disease rate
- Peak risk age group: 51–60 years

## 🚀 How to Run
```bash
git clone https://github.com/ammarelsayed-2a/Project-18-Python-For-Data-Analysis-Heart-Disease.git
cd Project-18-Python-For-Data-Analysis-Heart-Disease
jupyter notebook "Project 18 HeartDisease.ipynb"
```

## 👤 Author
**Ammar Elsayed** — Python for Data Analysis | 2026  
[LinkedIn](https://www.linkedin.com/in/ammar-elsayed-ibrahim)
