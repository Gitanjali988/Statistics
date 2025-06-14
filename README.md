# 📊 Students Performance in Exams – Statistical Methods 

This project applies rigorous statistical techniques to analyze the factors influencing student's performance in standardized exams. The goal is to explore relationships between exam scores and variables like gender, parental education, test preparation, lunch type, and ethnicity.

---

## 📌 Overview

- **Data Source**: [Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams)

---

## 🧪 Statistical Techniques Applied

| Technique                     | Purpose |
|------------------------------|---------|
| Hypothesis Testing           | Analyze independence between variables like gender & performance |
| One-Way ANOVA                | Compare mean scores across multiple groups |
| Chi-Square Test              | Test independence in categorical variables |
| Logistic Regression          | Model categorical response variable (e.g., gender) |
| Linear Regression            | Predict exam scores using other variables |
| Ridge & Lasso Regression     | Handle multicollinearity and improve model generalization |

---


---

## 📂 Dataset Description

- **Fields**:
  - Gender (Male/Female)
  - Race/Ethnicity (Groups A–E)
  - Parental level of education
  - Lunch type (standard/reduced)
  - Test preparation (completed/none)
  - Math score
  - Reading score
  - Writing score

![image](https://github.com/user-attachments/assets/4417fd59-494b-4fce-b560-9688cc2bb347)

---

## 📈 Key Findings

- **Test Preparation** and **Lunch Type** significantly affect performance.
- **Females** outperform males in reading and writing, while **males** do better in math.
- **Parental education** has a moderate impact on student scores.
- **Chi-square tests** show that **gender is independent** of test prep at a 95% confidence level.
- **Model Accuracy**: 
  - Logistic Regression: **91%**
  - Linear/Ridge/Lasso Regression: **82%+**

---

## 📄 References

1. Rice, John A. – *Mathematical Statistics and Data Analysis*  
2. ISLR – *An Introduction to Statistical Learning*  
3. StatsBlogs – [Chi-square Test](https://statsandr.com/blog/chi-square-test-of-independence-in-r/)  
4. Scribbr – [ANOVA in R](https://www.scribbr.com/statistics/anova-in-r/)

---

## 🛡️ License

This project is protected under copyright.


