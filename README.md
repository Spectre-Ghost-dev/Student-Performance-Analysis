# Student-Performance-Analysis

### *A Data-Driven Examination of Learning Patterns and Exam Outcomes*

**Date:** November 31, 2025

**Author:** Abubakar Mahfuz Eniola

**Tools Used:**
* Microsoft Excel → Data Cleaning & Statistical Analysis
* Microsoft Power BI → Data Visualization & Dashboard
* Microsoft Word → Analytical Report Documentation

---

## Executive Summary

This project is my **second data analytics project** and my **first experience working with a purely numeric dataset**.
It examines how **study habits, attendance, sleep hours, and previous scores** affect students’ final exam outcomes using a dataset of 200 students.

The analysis combines:

* **Descriptive Statistics** (Mean, Median, SD, IQR)
* **Correlation & Regression Analysis**
* **Segmentation Analysis** (Score Ranges & Performance Bands)
* **Data Visualization** via Power BI (Column Chart, Box Plot, Donut, Scatter Plot)

The findings highlight a centralized performance trend, with most students scoring between **30–39 (Balanced Band)**, showing stable but low achievement levels.

---

## Key Analytical Findings

1. **Previous Scores (r = 0.82)** → Strongest predictor of Exam Score
2. **Hours Studied (r = 0.65)** → Secondary influence; effort matters but depends on foundation
3. **Attendance Percentage (r = 0.51)** → Ensures exposure but not mastery
4. **Sleep Hours (r = 0.46)** → Moderate cognitive support, not a performance driver

---

## Descriptive Statistics Summary

| Metric              | Mean | Median | Std. Dev. | IQR  | Insight                        |
| ------------------- | ---- | ------ | --------- | ---- | ------------------------------ |
| **Exam Score**      | 35.0 | 34.0   | 6.79      | 12.0 | Clustered performance below 40 |
| **Previous Scores** | 68.0 | 69.0   | 15.0      | 25.0 | Stable academic foundation     |
| **Hours Studied**   | 5.5  | 5.5    | 3.0       | 4.8  | Diverse study effort           |
| **Sleep Hours**     | 6.5  | 6.5    | 1.2       | 2.0  | Uniform lifestyle factor       |
| **Attendance %**    | 78.5 | 78.0   | 12.0      | 18.0 | Consistent class presence      |

---

## Performance Bands (0–60)

| Range | Label       | Interpretation           |
| ----- | ----------- | ------------------------ |
| 0–10  | Extreme Low | Severely underperforming |
| 11–20 | Low         | Below average            |
| 21–30 | Average     | Moderate instability     |
| 31–40 | Balanced    | Cohort majority          |
| 41–50 | High        | Emerging excellence      |
| 51–60 | Very High   | Top performers           |

Color Gradient: Shades of green represent increasing performance.

---

## Visual Components

* **Column Chart:** Shows performance distribution across 10-point score ranges.
* **Box Plot:** Displays intra-segment variability — widest in the 20–29 (Average) band.
* **Scatter Plot:** Exam Score vs. Sleep Hours (r = 0.46) → moderate positive trend.
* **Donut Chart:** Confirms 1:1 mapping between numeric ranges and qualitative bands.

![STUDENT ANALYSIS DASHBOARD](https://github.com/Spectre-Ghost-dev/Student-Performance-Analysis/blob/main/Final%20Student%20Dashboard%20Design.jpg)

---

## Major Insights

* Most students fall in the **Balanced** range (30–39), signaling performance stagnation.
* The **Average** range (20–29) has the widest score spread → needs individual diagnosis.
* High attendance doesn’t guarantee better scores — **quality of effort > quantity of presence.**
* Sleep acts as a **supportive cognitive factor**, not a main driver.

---

## Strategic Recommendations

1. **Reinforce Foundational Competence** — Prioritize students with low previous scores for remedial programs.
2. **Differentiate Interventions** — Diagnose whether poor performance stems from effort or comprehension gaps.
3. **Integrate Sleep & Wellness Awareness** — Promote consistent sleep routines for cognitive optimization.
4. **Target the Middle Majority** — Focus on lifting students in the 20–39 range rather than just preventing failure.

---



## Next Steps

* Add predictive modeling (Regression / ML) to forecast exam outcomes.
* Expand dataset to multiple terms for longitudinal tracking.
* Automate Power BI refresh for continuous academic monitoring.


