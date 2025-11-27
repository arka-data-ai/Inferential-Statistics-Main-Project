# 📊 Inferential Statistics Main Project  
End-to-End Statistical Analysis using Probability, Z-scores, Hypothesis Testing & ANOVA

This project demonstrates core inferential statistics concepts using four real-world scenarios.  
It includes probability analysis, normal distribution applications, two-sample hypothesis testing, and two-way ANOVA with interaction effects.

---

## 🚀 Project Overview

This repository contains:

- **Jupyter Notebook:** Inferential_Statistics_Main_Project.ipynb  
- **PDF Report:** Inferential_Statistics_project_report.pdf  

The project is divided into **four structured inferential statistics problems**, each representing a practical business or scientific scenario.

---

# 🧩 **1. Problem Statements & Solutions**

## 🔶 **Problem 1 — Probability Using Contingency Tables**

**Objective:**  
Analyze customer behavior using a 2×2 contingency table based on:
- Age Group (Young, Middle, Old)
- Purchase Decision (Yes/No)

**Key Work Done:**
- Constructed contingency table
- Calculated:
  - Marginal probabilities
  - Joint probabilities
  - Conditional probabilities  
- Verified probability rules

**Outcome:**  
Clear understanding of how customer demographics influence purchase patterns.

---

## 🔶 **Problem 2 — Normal Distribution & Z-Scores**

**Scenario:**  
A logistics company tracks delivery times (μ = 88 mins, σ = 15 mins).

**Key Analysis:**
- Converted delivery times to **Z-scores**
- Calculated probability ranges using the standard normal distribution:
  - P(X < 75)
  - P(75 < X < 90)
  - P(X > 120)
- Plotted the normal curve with cutoff zones

**Outcome:**  
Helped quantify delivery performance and identify delays using probability.

---

## 🔶 **Problem 3 — Two-Sample Hypothesis Testing (t-Test)**

**Scenario:**  
Measure whether polishing stones increases hardness.

**Process:**
1. Loaded polished vs unpolished data  
2. EDA: Boxplots, histograms  
3. Normality check → Shapiro-Wilk  
4. Variance check → Levene’s test  
5. Two-sample **independent t-test**  
6. Hypothesis:  
   - H0: μ₁ = μ₂  
   - H1: μ₁ ≠ μ₂  

**Outcome:**  
Statistically determined whether polishing significantly affects hardness.

---

## 🔶 **Problem 4 — Two-Way ANOVA + Interaction Effects**

**Scenario:**  
Analyze dental implant hardness based on:
- Treatment Type (A/B)
- Material Type (M1, M2, M3)

**Steps Performed:**
- Exploratory summary tables  
- Interaction plots (Treatment × Material)  
- Built ANOVA model using `statsmodels`  
- Interpreted:
  - Treatment effect  
  - Material effect  
  - Interaction effect  

**Outcome:**  
Identified which combinations of treatment & material lead to optimal hardness.

---

# 🛠️ **Technologies Used**

- Python  
- NumPy, Pandas  
- SciPy (t-tests, normal distribution)  
- Statsmodels (ANOVA)  
- Matplotlib / Seaborn (visualizations)  
- Jupyter Notebook  

---

