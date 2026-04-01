Student Performance Analysis
Gender and Parental Education Effects on Math & Language Scores

Project Overview

This project analyzes student performance using statistical methods to investigate how gender and parental education level influence mathematics and language test scores.

The analysis is based on a dataset of 486 students, and it was developed as part of an application report for the M.Sc. Data Science program at TU Dortmund University.

Objectives

The project answers two main research questions:

Gender Effect
Is there a statistically significant difference between male and female students in math and language scores?
Parental Education Effect
Do students' scores differ across parental education levels?
Which groups show significant differences?

Dataset

File: Scores.csv
Observations: 486 students
Features:
gender (male/female)
parental_education (high school, associate, bachelor, master)
math_score (0–100)
language_score (0–100)

Methods Used

Descriptive Analysis

Mean, Median, Standard Deviation
Group comparisons
Boxplots & visualizations

Statistical Testing

Shapiro-Wilk Test → Normality check
Mann-Whitney U Test → Gender comparison
Kruskal-Wallis Test → Multiple group comparison
Post-hoc tests (Bonferroni correction)
Effect size calculations (rank-biserial correlation, η²)
🔗 Correlation Analysis
Pearson correlation between math and language scores

Key Findings

Gender Differences

Males perform better in Mathematics
Females perform better in Language
Differences are statistically significant with small to moderate effect sizes

Parental Education

Strong positive relationship between education level and scores
Students with parents with master’s degrees perform the best
Significant differences mainly between:
High school vs Master’s
Associate vs Master’s

Correlation

Strong positive correlation between math and language scores
→ Indicates general academic ability factor

Technologies Used

Python 3.x
pandas
scipy
matplotlib
seaborn
Colap 

Project Structure
 
├── Data_Science_Report.ipynb   # Main analysis notebook

├── Scores.csv                 # Dataset

├── Application_Report.pdf     # Full report

└── README.md                  # Project documentation

Future Improvements

Include more variables (income, school type, etc.)
Apply regression models
Use machine learning for prediction
Analyze interaction effects more deeply

Notes

This project is fully reproducible and demonstrates:

Statistical analysis skills
Data interpretation
Real-world data storytelling
