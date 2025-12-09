Student Performance Statistical Analysis

This project conducts a comprehensive statistical analysis of a student academic performance dataset containing 300 observations. The objective is to explore study habits, academic outcomes, and school-related factors using descriptive statistics, inferential testing, sampling methods, and distribution-based demonstrations.

1. Overview

This analysis examines the relationship between:

study hours,

attendance rate,

exam scores,

gender,

school category, and

study methodology

It includes classical hypothesis testing techniques, outlier detection, and demonstrates fundamental statistical principles such as the Central Limit Theorem.

2. Methodology
2.1 Dataset

The dataset (student_performance_300.csv) contains the following key variables:

study_hours_week

attendance_rate

midterm_score

final_score

school

gender

study_method

passed_final

2.2 Sampling Techniques Implemented

Simple Random Sampling

Stratified Sampling (based on school and gender)

These methods illustrate representativeness and subgroup consistency in sample selection.

2.3 Descriptive Statistics

The script computes detailed descriptive statistics for all numeric variables including:

measures of central tendency

dispersion characteristics

quartiles and IQR

skewness

kurtosis

2.4 Outlier Detection

Two common methods were used:

Interquartile Range (IQR)

Z-Score (±3 standard deviations)

3. Hypothesis Testing
Hypothesis A – Two-Sample T-Test (Welch)

Examines mean differences in final exam performance between students studying:

more than 10 hours/week, and

10 hours or fewer.

Hypothesis B – Paired Samples T-Test

Assesses whether students’ final scores statistically exceed their midterm scores.

Hypothesis C – One-Way ANOVA

Tests whether mean performance significantly differs across:

School A

School B

School C

Effect size (η²) is additionally computed.

Hypothesis D – Chi-Square Test of Independence

Evaluates whether study method is statistically associated with final exam pass status.


4. Multiple Testing Adjustment

To control the family-wise error rate, Bonferroni correction was applied to all hypothesis test p-values, producing an adjusted significance level (α = 0.01).

5. Deliverables Generated

The script automatically exports:

Output File	Content
student_performance_data.csv	Processed dataset
descriptive_statistics.csv	Summary statistics

6. Required Libraries
numpy
pandas
matplotlib
seaborn
scipy
statsmodels

7. Execution
python analysis.py


Ensure the dataset file is located in the working directory.

8. Intended Academic Contribution

This project demonstrates core inferential statistical procedures with real-world data. It supports educational analysis, applied statistics learning, and research in academic performance evaluation. The methodology and results can further be integrated into predictive modeling, educational data mining, and institutional analytics.

9. Author

Prepared by SIDDHARTHA NADIMPALLI and SAI VIVEK
(Statistical Analysis and Data Exploration Project)
