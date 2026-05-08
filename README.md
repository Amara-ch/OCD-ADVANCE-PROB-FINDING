# OCD-ADVANCE-PROB-FINDING
# 🧠 Demographic and Clinical Predictors of OCD Severity

An advanced statistics and data analysis project focused on identifying the major demographic, behavioral, and clinical factors influencing Obsessive-Compulsive Disorder (OCD) severity using statistical techniques and predictive modeling.

---

# 📌 Project Overview

This project analyzes clinical OCD patient data to understand how therapy types, depression, sleep quality, stress, and other behavioral factors affect OCD severity.

Using statistical hypothesis testing and predictive analysis, the project identifies the most significant contributors to symptom intensity and treatment outcomes.

---

# 🎯 Project Objectives

- Analyze factors affecting OCD severity
- Compare effectiveness of different therapy types
- Study the impact of depression on OCD symptoms
- Identify behavioral predictors such as sleep and stress
- Apply advanced statistical methods to clinical data

---

# 📂 Dataset Information

- **Source:** Kaggle Clinical OCD Dataset
- **Records:** 500 patient records

## Features Included
- Age
- Gender
- Therapy Type (ERP, CBT, Combined)
- Sleep Quality
- Stress Levels
- Exercise Frequency
- Screen Time
- Depression Diagnosis
- Duration of Symptoms
- Y-BOCS Severity Scores

---

# ⚠️ Challenges Faced

## Non-Normal Data Distribution
OCD severity scores were heavily skewed and non-normal, requiring non-parametric statistical testing.

## Complex Clinical Predictors
High comorbidity rates, especially depression, created noise while identifying independent predictors.

---

# 📊 Statistical Analyses Performed

---

## 1️⃣ Mann-Whitney U Test

### Purpose
To analyze whether depression significantly affects OCD severity.

### Hypotheses
- **H₀:** No difference in OCD severity between depressed and non-depressed patients
- **H₁:** Depressed patients have higher OCD severity

### Results
- **U = 20285.5**
- **p = 0.0003**

### Conclusion
Depression significantly increases OCD severity.

---

## 2️⃣ Multiple Linear Regression

### Purpose
To identify the strongest predictors of OCD severity.

### Results
| Predictor | Coefficient | Significance |
|---|---|---|
| Depression | 5.51 | p < 0.001 |
| Sleep Quality | -1.03 | p < 0.001 |
| Stress Level | 0.62 | p = 0.026 |

### Model Performance
- **R² = 0.063**

### Interpretation
- Depression is the strongest predictor of increased severity
- Better sleep quality reduces symptoms
- Higher stress increases severity

---

## 3️⃣ Kendall’s Tau Correlation

### Purpose
To measure relationships between behavioral factors and OCD severity.

### Results
| Variable | Tau (τ) | Significance |
|---|---|---|
| Sleep Quality | -0.11 | Highly Significant |
| Stress Level | 0.088 | Significant |
| Exercise | 0.046 | Not Significant |
| Social Support | -0.04 | Not Significant |

### Interpretation
Sleep quality and stress levels significantly impact OCD severity.

---

## 4️⃣ Chi-Square Test of Independence

### Purpose
To determine whether depression prevalence differs by gender.

### Results
- **χ² = 0.656**
- **p = 0.720**

### Conclusion
No significant association was found between gender and depression.

---

## 5️⃣ Kruskal-Wallis H-Test

### Purpose
To compare OCD severity across therapy types.

### Results
- **H-statistic = 210.00**
- **p < 0.001**

### Conclusion
Therapy type significantly affects OCD severity outcomes.

Combined therapy showed the best results.

---

## 6️⃣ Pearson Correlation Analysis

### Purpose
To analyze relationships among clinical variables.

### Key Results
| Variables | Correlation (r) |
|---|---|
| Obsessions vs Total Severity | 0.96 |
| Compulsions vs Total Severity | 0.96 |
| Duration vs Total Severity | 0.20 |

### Interpretation
- Obsessions and compulsions strongly contribute to total severity
- Longer untreated duration slightly increases severity
- Age has little effect on OCD severity

---

# ✅ Final Conclusion

The study concludes that:

- Therapy type is the strongest factor influencing recovery outcomes
- Depression significantly amplifies OCD severity
- Sleep quality and stress management are critical behavioral factors
- Age and gender have minimal impact on OCD severity

### Recommended Focus Areas
- Integrated therapy approaches
- Depression management
- Better sleep hygiene
- Stress reduction strategies

---

# 🛠️ Technologies & Tools Used

- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 👥 Team Members

- Khansa Azeem
- Amara Tariq
- Ayesha Akbar
- Zeenat Fatima

---

# 🎓 Supervisor

**Dr. Syed Faisal Bukhari**  
Associate Professor  
Department of Data Science

---

# 📌 Future Improvements

- Apply machine learning models for prediction
- Use larger and more diverse clinical datasets
- Build interactive dashboards
- Explore longitudinal OCD patient analysis

---
