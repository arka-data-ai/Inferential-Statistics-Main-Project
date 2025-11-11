# 🧮 Inferential Statistics Main Project

## 📘 Project Overview
This project focuses on applying **Inferential Statistics** to solve business-driven analytical problems using Python.  
It demonstrates hypothesis testing, ANOVA, and probability-based decision-making through three case studies involving different industries.  
Each analysis aims to support data-driven decision-making by drawing conclusions from sample data and quantifying uncertainty.

The entire analysis was coded in **Python (Jupyter Notebook)**, supported by a **formal report** for statistical interpretation and business insights.

---

## 🎯 Project Objectives
- Apply the concepts of **Inferential Statistics** to practical business scenarios.  
- Perform **Hypothesis Testing** using various test statistics (t-test, ANOVA).  
- Evaluate **sample evidence** to make decisions about population parameters.  
- Quantify statistical significance and interpret results for business actions.  
- Strengthen understanding of probability, sampling, and distribution theory.  

---

## 🧩 Case Studies and Datasets

### 1. 🪨 **Stone Suitability for Printing**
**Objective:**  
Determine whether the two types of stones differ significantly in surface smoothness and suitability for printing.  

**Approach:**  
- Conducted exploratory data analysis to compare surface textures.  
- Applied **Independent Two-Sample t-test** to test for mean differences between the two stone types.  
- Set up hypotheses:  
  - H₀: There is no significant difference between the two stone types.  
  - H₁: There is a significant difference in suitability for printing.  

**Inference:**  
- Based on the p-value, rejected the null hypothesis.  
- Concluded that **stone type significantly influences print quality**.  

---

### 2. 💪 **Fitness Program Effectiveness**
**Objective:**  
Evaluate whether a structured fitness program significantly improved the health metrics of participants.  

**Approach:**  
- Measured health parameters before and after the program.  
- Applied a **Paired t-test** to test the difference in mean outcomes.  
- Verified assumptions of normality using histograms and QQ plots.  

**Inference:**  
- Found a statistically significant improvement (p < 0.05).  
- Concluded that the **fitness program effectively enhanced participants’ performance and health outcomes**.  

---

### 3. 🦷 **Dental Implant Hardness Study**
**Objective:**  
Examine whether **different dentists** and **implant methods** influence metal implant hardness.  

**Approach:**  
- Created a factorial experimental design using two factors: Dentist and Implant Method.  
- Applied **Two-Way ANOVA** to test for main and interaction effects.  
- Hypotheses:  
  - H₀₁: No difference among dentists.  
  - H₀₂: No difference among implant methods.  
  - H₀₃: No interaction between dentist and method.  

**Inference:**  
- Rejected all null hypotheses.  
- Concluded that **both dentist and method significantly affect hardness**, and there is a notable **interaction effect** between the two factors.  

---

## 🧠 Statistical Concepts and Methods
The analysis covered the following core inferential techniques:

| Concept | Description |
|----------|--------------|
| Sampling and Estimation | Drawing conclusions about populations using sample statistics |
| Central Limit Theorem | Understanding sampling distributions and variability |
| Confidence Intervals | Estimating population parameters within uncertainty bounds |
| Hypothesis Testing | Formulating and testing statistical claims |
| t-tests | Comparing means across one or two samples |
| ANOVA | Testing mean differences across multiple groups |
| p-value Interpretation | Quantifying statistical significance |
| Type I & II Errors | Evaluating risks of incorrect decisions |

---

## 🧰 Tools and Libraries
- **Python 3.10+**
- **Jupyter Notebook**
- **NumPy** → Mathematical and statistical operations  
- **Pandas** → Data manipulation and cleaning  
- **Matplotlib / Seaborn** → Visualization and data exploration  
- **SciPy / statsmodels** → Statistical analysis (t-test, ANOVA)  

---

## 📈 Key Findings and Insights
| Scenario | Statistical Test | Result | Business Insight |
|-----------|------------------|---------|------------------|
| Stone Suitability | Two-Sample t-test | Significant difference | Stone type affects printing quality |
| Fitness Program | Paired t-test | Significant improvement | Program improves fitness outcomes |
| Implant Hardness | Two-Way ANOVA | Main & interaction effects significant | Both dentist and method influence hardness |

**Overall Insight:**  
Inferential statistics help businesses move from raw data to actionable decisions by quantifying uncertainty and validating assumptions.

---

## 📊 Visualizations
Throughout the analysis, data visualizations were used to:
- Explore sample distributions (histograms, boxplots)  
- Check assumptions of normality and variance homogeneity  
- Compare mean differences visually  
- Display ANOVA factor effects and interactions  

Example plots:
- Distribution plots for before/after fitness measurements  
- Boxplots comparing hardness across dentists and methods  
- Confidence interval visual summaries  

---

