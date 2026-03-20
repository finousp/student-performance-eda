# student-performance-eda
Exploratory Data Analysis on student performance dataset using Python


# Student Habits vs Academic Performance — Exploratory Data Analysis

This project performs an exploratory data analysis (EDA) on the Student Habits vs Academic Performance dataset to identify relationships between academic behaviors, lifestyle factors, and exam outcomes.

The goal is to examine which student habits show the strongest association with exam performance and to distinguish meaningful relationships from weak or insignificant patterns.

The analysis focuses on statistical relationships between study habits, lifestyle variables, and academic outcomes.

---

## Dataset

Source: Kaggle  
Dataset: Student Habits vs Academic Performance  

The dataset contains information about student study patterns, lifestyle behaviors, and exam scores.

Key characteristics:

- **Observations:** 1000 students  
- **Target variable:** `exam_score`  
- **Feature categories:**
  - Academic behavior (study hours, attendance)
  - Lifestyle factors (sleep, social media usage, exercise)
  - Demographic variables (gender, age)
  - Student engagement indicators (extracurricular activities, part-time jobs)

---

## Tools & Technologies

The analysis was conducted using:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## Analysis Workflow

The exploratory analysis follows a structured process:

1. Data loading and validation  
2. Missing value handling and sanity checks  
3. Univariate analysis to understand variable distributions  
4. Outlier inspection  
5. Bivariate analysis using scatterplots and correlation measures  
6. Statistical hypothesis testing for categorical variables  
7. Correlation matrix analysis to identify broader relationships

---

## Key Insights

The analysis reveals several patterns in the dataset:

- **Study hours per day show the strongest relationship with exam scores** (r ≈ 0.83), indicating a strong association between academic effort and performance.

- **Mental health rating shows a moderate positive relationship** with exam outcomes.

- **Lifestyle variables such as sleep and exercise show weak positive correlations** with exam performance.

- **Entertainment usage (social media and Netflix viewing) shows weak negative correlations** with exam scores.

- **Statistical tests show no significant differences in exam scores based on gender, part-time employment, or extracurricular participation.**

Overall, the findings suggest that **consistent academic effort is the most influential factor associated with exam performance in this dataset.**

---

## Limitations

Several limitations should be considered when interpreting the results:

- The dataset may contain synthetic or simulated patterns.
- Correlation-based analysis does not imply causation.
- The analysis focuses on exploratory relationships rather than predictive modeling.

---

## Next Steps

Potential extensions of this analysis include:

- Building a regression model to quantify the combined effects of study habits and lifestyle variables.
- Applying clustering techniques to identify groups of students with similar behavioral patterns.
- Validating the findings on real-world educational datasets.

---
## 👤 Author

Finous P
---
