# Training Effectiveness and Learning Analytics for Candidates with Disabilities

## 📌 Project Overview

This project analyzes **training effectiveness and learning outcomes among candidates with disabilities** using Python and data analytics techniques.

The objective is to identify patterns in **learning improvement, attendance, training programs, training modes, mentor feedback, and completion status**, and to generate data-driven recommendations for improving training delivery and learner outcomes.

---

## 🎯 Objectives

* Measure the improvement in candidate performance after training.
* Analyze the relationship between **attendance and training completion**.
* Compare learning outcomes across different **training programs and disability groups**.
* Examine the impact of **training mode, mentor rating, and training hours**.
* Identify key patterns and insights through statistical analysis and visualization.
* Provide actionable recommendations for improving training effectiveness.

---

## 📊 Dataset

| Metric            | Details                   |
| ----------------- | ------------------------- |
| Records           | **750 candidates**        |
| Features          | **16 variables**          |
| Data Types        | Numerical & Categorical   |
| Missing Values    | **0 after preprocessing** |
| Duplicate Records | **0**                     |
| Analysis Tool     | Python / Jupyter Notebook |

The dataset contains information related to candidate characteristics, training participation, assessment scores, attendance, training programs, training modes, mentor ratings, and completion status.

---

## 🛠️ Tools & Technologies

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Analysis environment

---

## 🔍 Analytical Approach

### 1. Data Cleaning & Preprocessing

* Inspected dataset structure, data types, and statistical summaries.
* Identified and treated missing values.
* **78 missing values** in `Accommodation_Provided` were replaced with **"Not Specified"**.
* Checked and confirmed **0 duplicate records**.
* Created the derived feature **`Training_Improvement`** to measure change between pre- and post-training performance.
* Performed consistency checks and final dataset validation.

### 2. Exploratory Data Analysis

The analysis included:

* **Univariate Analysis** – distributions and patterns of individual variables.
* **Bivariate Analysis** – relationships between key variables.
* **Multivariate Analysis** – interaction of multiple variables.
* GroupBy and summary analysis.
* Pivot analysis.
* Correlation analysis.
* Comparative analysis across training programs, training modes, and disability groups.

### 3. Visualization

The project includes **10+ different visualizations** to communicate patterns and findings effectively.

---

## 📈 Key Findings

### Training Program Performance

| Training Program        | Avg. Improvement | Avg. Attendance |
| ----------------------- | ---------------: | --------------: |
| Office Administration   |        **21.19** |          81.36% |
| English & Communication |        **21.03** |          80.93% |
| Employability Skills    |        **20.88** |          81.00% |
| Data Entry              |        **20.59** |          80.13% |
| Customer Support        |        **20.29** |          80.33% |
| Digital Literacy        |        **19.98** |          81.78% |

Improvement was observed across all training programs, with relatively small differences between programs.

### Training Mode & Completion

| Training Mode | Completion Rate |
| ------------- | --------------: |
| **Hybrid**    |      **91.85%** |
| Online        |          90.13% |
| Classroom     |          86.96% |

Hybrid training recorded the highest observed completion rate among the three training modes.

### Attendance & Completion

Candidates who completed training had an average attendance of **82.30%**, compared with **70.10%** among candidates who did not complete training.

This represents an approximate **12.20 percentage-point difference** in average attendance.

---

## 💡 Key Insights

1. **Post-training performance showed the strongest relationship with Training Improvement** with a correlation of **r = 0.541**.

2. **Attendance was higher among candidates who completed training**, suggesting an association between consistent participation and completion.

3. **Hybrid training recorded the highest observed completion rate** at **91.85%**.

4. **Mentor rating was positively associated with Training Improvement** with **r = 0.355**.

5. **Training hours had a very weak negative relationship with improvement** (**r = -0.067**), indicating that duration alone does not explain learning outcomes.

6. **Training Improvement was relatively consistent across programs**, with Office Administration recording the highest average improvement (**21.19**) and Digital Literacy the lowest (**19.98**).

7. Across disability groups, **Multiple Disability** recorded the highest average improvement (**22.16**), while **Speech & Language Disability** recorded the lowest (**20.13**).

8. **Pre-training score showed almost no relationship with improvement** (**r = 0.015**), while post-training score showed a considerably stronger relationship.

9. Individual learning improvement varied, highlighting the importance of considering learner-level differences rather than relying only on overall averages.

10. Training effectiveness is better evaluated using **multiple indicators** rather than a single measure.

---

## 🎯 Recommendations

Based on the analysis:

* **Strengthen post-training assessments** to measure learning outcomes consistently.
* **Encourage regular attendance** through effective monitoring and learner support.
* **Consider flexible and hybrid training approaches** where appropriate.
* **Use mentor feedback** as an additional indicator for improving training delivery.
* Focus on **training quality and learner engagement**, rather than training duration alone.
* Maintain consistent training quality across different programs.
* Provide **individualized and accessibility-focused support** based on learner needs.

---

## ⚠️ Reliability & Limitations

The findings represent patterns and associations observed within the available dataset.

* **Correlation does not imply causation.**
* Differences between groups should be interpreted carefully.
* Group sizes may vary across categories.
* Factors such as individual learning needs, accessibility, engagement, support systems, and personal circumstances may not be fully captured in the dataset.

Therefore, the results should be used as **evidence for identifying patterns and supporting training decisions**, rather than as proof of direct causal relationships.

---

## 🏁 Conclusion

The analysis indicates that candidates demonstrated **positive learning improvement after training**, although the level of improvement varied across individuals and learner groups.

The findings highlight the importance of **post-training performance, attendance, mentoring, training mode, and learner support** in understanding training outcomes. At the same time, training duration alone showed little relationship with improvement.

Overall, the project demonstrates how **Python-based data analysis and visualization can transform training data into meaningful insights** that can support better training delivery, learner engagement, and accessibility-focused decision-making.

---

## 📂 Project Structure

```text
Training-Effectiveness-and-Learning-Analytics/
│
├── Training Effectiveness and Learning Analytics for Candidates with Disability.ipynb
├── Disabled_Candidate_Training_Analytics.xlsx
├── README.md
└── Data Analytics Final Project Guidelines.pdf
```

---

## 📌 Project Requirements Covered

✔ Data cleaning and preprocessing
✔ Missing-value treatment
✔ Duplicate detection
✔ Feature engineering
✔ Statistical analysis
✔ Univariate, bivariate & multivariate EDA
✔ GroupBy and pivot analysis
✔ Correlation analysis
✔ 10+ data visualizations
✔ Key insights and findings
✔ Recommendations
✔ Limitations and validation
✔ Final conclusion

---

### 👩‍💻 Project Focus

**Data Analytics | Training Effectiveness | Learning Analytics | Exploratory Data Analysis | Python | Accessibility & Inclusion**
Project Link : https://drive.google.com/file/d/1yrRqi5X8M_6f6LE58iHsRabRRQlH3-DE/view?usp=sharing
