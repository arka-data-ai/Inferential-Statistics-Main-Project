# 📊 Inferential Statistics Main Project  
End-to-End Statistical Analysis using Probability, Normal Distribution, t-Tests & ANOVA

This project showcases four real business analytics scenarios using inferential statistics.  
It covers probability, normal distribution, hypothesis testing, one-way ANOVA, and two-way ANOVA with interaction analysis.

---

## 🚀 Project Overview

This repository contains:

- **Jupyter Notebook:** `Inferential_Statistics_Main_Project.ipynb`  
- **PDF Report:** `Inferential Statistics Main Project.pdf`

The project includes **four structured inferential statistics problems**, each based on a real-world scenario:

1. Football player injury probability analysis  
2. Gunny bag breaking strength (normal distribution)  
3. Stone hardness suitability & comparison  
4. Dental implant hardness (ANOVA and interaction effects)

---

# 🧩 Problem Statements & Solutions

---

# 🔶 Problem 1 — Football Player Injury Probability (Contingency Table)

### **Business Context**
A physiotherapist wants to determine whether injury risk varies by football player position  
(Striker, Forward, Attacking Midfielder, Winger).

### **Key Work Done**
- Built a contingency table of **Player Position × Injury Status**
- Calculated:
  - Marginal probabilities  
  - Joint probabilities  
  - Conditional probabilities  

### **Questions Answered**
- Probability a player is injured  
- Probability a player is a Forward or Winger  
- Probability of being an injured Striker  
- Probability a player is a Striker *given* he is injured  

### **Outcome**
Clear understanding of injury distribution across positions to support injury-prevention strategies.

---

# 🔶 Problem 2 — Breaking Strength of Gunny Bags (Normal Distribution)

### **Business Context**
A cement manufacturing company studies breaking strength of gunny bags,  
known to follow a **normal distribution**:

- **Mean (μ):** 5 kg/cm²  
- **Standard Deviation (σ):** 1.5 kg/cm²  

### **Key Statistical Tasks**
Using Z-scores and standard normal distribution, computed:

- **P(X < 3.17)**  
- **P(X ≥ 3.6)**  
- **P(5 ≤ X ≤ 5.5)**  
- **P(X NOT between 3 and 7.5)**  

### **Outcome**
Quantified the probability of weak or excessively strong bags to reduce wastage and quality issues.

---

# 🔶 Problem 3 — Stone Hardness Suitability & Two-Sample Testing

## **3.1 Suitability Test for Unpolished Stones**

### **Business Context**
Zingaro Printing requires a minimum **Brinell Hardness Index (BHI) ≥ 150** for print quality.

### **Test Used**
One-sample, one-tailed **t-test**

- **H₀:** μ ≥ 150  
- **H₁:** μ < 150  

### **Outcome**
Unpolished stones were **significantly below** the required hardness.  
They are **not suitable** for printing.

---

## **3.2 Polished vs Unpolished Stones (Two-Sample t-Test)**

### **Business Context**
Polishing is expected to improve stone hardness.

### **Test Used**
Welch’s **two-sample t-test** (unequal variances)

- **H₀:** μ₁ = μ₂  
- **H₁:** μ₁ ≠ μ₂  

### **Outcome**
Polished stones have **significantly higher** hardness than unpolished stones.

---

# 🔶 Problem 4 — Multi-Factor ANOVA on Dental Implant Hardness

Analysis conducted separately for **Alloy 1** and **Alloy 2**  
to understand how hardness varies based on:

- **Dentist**
- **Implant Method**
- **Interaction (Dentist × Method)**

---

## **4.1 Effect of Dentist (One-Way ANOVA)**

### **Outcome**
For both alloys:
- No statistically significant difference between dentists.

---

## **4.2 Effect of Method (One-Way ANOVA + Tukey HSD)**

### **Outcome**
- Method **significantly affects implant hardness** for both alloys.  
- **Method 3 always produces much lower hardness**.  
- Methods 1 & 2 are similar.

---

## **4.3 Interaction Effect (Dentist × Method)**

### **Outcome**
- **Alloy 1:** Significant interaction → effect of method changes by dentist  
- **Alloy 2:** No significant interaction  

---

## **4.4 Two-Way ANOVA (Dentist + Method + Interaction)**

### **Alloy 1 Results**
- Dentist: **Significant**  
- Method: **Significant**  
- Interaction: **Significant**

### **Alloy 2 Results**
- Dentist: Not significant  
- Method: **Highly significant**  
- Interaction: Not significant  

### **Conclusion**
Method selection is the most important factor.  
**Method 3 should be reconsidered or improved.**

---

# 🛠️ Technologies Used

- Python  
- NumPy, Pandas  
- SciPy (t-tests, normal distribution)  
- Statsmodels (ANOVA, Tukey HSD)  
- Matplotlib & Seaborn  
- Jupyter Notebook  

---


