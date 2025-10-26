# 🏷️ Metrocar Funnel Analysis (Google Sheets + SQL + Power BI + DAX)

## 📬 Contact
If you’d like to connect or discuss data visualization and analytics:
- 📧 [karyna.avetisova@nure.ua]
- 🔗 [https://www.linkedin.com/in/karina-avetisova/]

## 🧭 Project Overview
This project demonstrates a complete statistical analysis workflow conducted in Microsoft Excel and Python.
The analysis focuses on verifying data distribution, testing hypotheses, and performing variance and correlation analysis to understand key relationships in the dataset.


## 🧩 File Structure 
The Excel file consists of several analytical sheets:
| Sheet Name             | Description                                                                          |
| ---------------------- | ------------------------------------------------------------------------------------ |
| **Raw**                | Contains the raw unprocessed dataset used for analysis.                              |
| **Опис даних**         | Data overview — key variables, sample description, and basic descriptive statistics. |
| **Завдання**           | Statement of the analytical task and formulated hypotheses.                          |
| **Distribution check** | Normality check using histograms and descriptive statistics (skewness, kurtosis).    |
| **QQ з Пайтону**       | QQ plot generated in Python to visually confirm normal distribution.                 |
| **Розрахунки SS**      | Sum of Squares (SS) calculations — part of ANOVA methodology.                        |
| **Розрахунки FMLC**    | Factor Model or Linear Component calculations (possibly ANOVA or regression).        |
| **Розрахунки POC**     | Post-hoc comparisons or correlation tests to evaluate variable relationships.        |

## 🎯 Objectives
- Explore and describe the structure of the dataset.
- Check data distribution (normality test, QQ plot).
- Calculate core descriptive statistics (mean, median, variance, standard deviation).
- Perform variance analysis (ANOVA) to test group differences.
- Conduct post-hoc and correlation analysis for deeper interpretation.
- Combine Excel-based manual computation with Python validation for accuracy.

<img width="817" height="516" alt="image" src="https://github.com/user-attachments/assets/bcbd448f-5c6f-4364-99ac-46f0eb7da929" />
<img width="747" height="467" alt="image" src="https://github.com/user-attachments/assets/0b8e482e-b218-423d-a033-e8bfca137310" />


## 📈 Key Analytical Steps
- Data Preparation: Cleaning and structuring data in Excel (“Raw” and “Опис даних” sheets).
- Exploratory Analysis: Checking normality and visualizing distributions.
- Variance Analysis (ANOVA): Calculating SS and F-values to test group means.
- Model Estimation: Building linear or factor-based models (“Розрахунки FMLC”).
- Post-Hoc Analysis: Interpreting group differences and correlations.
- Validation with Python: Verifying statistical results through QQ plot and distribution fit.

## 💡 Key Findings (General)
- Data shows approximately normal distribution, confirmed by QQ plot and descriptive metrics.
- Variance analysis (ANOVA) revealed statistically significant differences between selected groups (p < 0.05).
- Post-hoc tests confirmed which specific factors contributed to group differences.
- The analytical workflow demonstrates how Excel can be used effectively for academic-level statistical analysis when combined with Python validation tools.

## 🧠 What I Learned
- How to calculate Sum of Squares and interpret ANOVA results manually.
- How to cross-check statistical assumptions using Python (QQ plot).
- The importance of verifying distribution assumptions before hypothesis testing.
- Gained practical experience in combining manual calculation transparency (Excel) with automated validation (Python).
