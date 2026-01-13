# student-depression-analysis
Data analysis project identifying key risk factors for student depression using Python &amp; Seaborn.
# 🧠 Student Depression Factors Analysis

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Focus](https://img.shields.io/badge/Focus-Mental%20Health%20Data-green)

## 📖 Project Overview
This project is a quantitative analysis of student mental health, aiming to identify the root causes of depression among university students. Using statistical correlation and data visualization techniques, I analyzed a dataset comprising student records to uncover the relationship between academic performance, financial status, and mental well-being.

The study reveals that **Academic Pressure** (not CGPA itself) is the primary driver of depression, and identifies a critical gap in current screening mechanisms where thousands of high-risk students go undiagnosed.

> **Key Insight:** Identified **~3,700 "Invisible High-Risk" students** who have suicidal thoughts but have not been diagnosed with depression, highlighting a blind spot in traditional campus screening.

## 📊 Key Findings & Insights

Based on the data analysis presented in the [Full Report](./report/Student_Mental_Health_Analysis_Report.pdf), here are the core discoveries:

### 1. The "Pressure" Correlation
* **Academic Pressure** is the #1 risk factor with a correlation coefficient of **0.47**.
* **Financial Stress** follows as the second strongest factor (correlation **0.36**).
* *Insight:* The data proves that extreme academic pressure, rather than the CGPA (grades) itself, is the core driver of the mental health crisis.

### 2. The "Invisible" High-Risk Group
A significant discrepancy was found between students with suicidal thoughts and those clinically diagnosed.
* **Observation:** A large cluster of students reported suicidal ideation but were **missed** by standard depression diagnosis criteria.
* **Implication:** Universities need independent, more sensitive screening tools beyond standard checkups.

*(Place your Fig 8-1 image here)*
![Suicidal Thoughts vs Diagnosis](./images/suicidal_vs_diagnosis.png)

## 🛠️ Technical Implementation

### Data Pipeline
1.  **Data Cleaning:** Handled missing values and standardized categorical variables (Likert scales) for correlation analysis.
2.  **EDA (Exploratory Data Analysis):** Used distribution plots to understand the prevalence of depression (58.5% in sample).
3.  **Statistical Analysis:** Applied Pearson correlation matrices to quantify relationships between independent variables (Pressure, Sleep, Diet) and the target variable (Depression).

### Tech Stack
* **Python:** Core analysis logic.
* **Pandas:** Data manipulation and cleaning.
* **Seaborn / Matplotlib:** Advanced data visualization (Heatmaps, Boxplots).
* **SciPy:** Statistical computations.

## 📸 Visualization Gallery

#### Correlation Heatmap: Risk Factors
*(Place your Heatmap image here)*
![Correlation Heatmap](./images/correlation_matrix.png)

#### Impact of Academic Pressure
*(Place another key chart here, e.g., Boxplot)*
![Pressure Analysis](./images/pressure_vs_depression.png)

## 💡 Recommendations
Based on the data, this project proposes:
1.  **Early Intervention:** Policies should focus on Year 12 and Freshmen, as they show higher vulnerability.
2.  **Holistic Support:** Financial aid and dietary improvements are as critical as counseling.
3.  **New Screening Tools:** Deploying specific tools to detect the "Invisible High-Risk" group identified in Fig 8-1.

## 📬 Author
**HU Xinyue**
* MSc in Computer Science, City University of Hong Kong
* www.linkedin.com/in/昕悦-胡-9a57853a5
* Email: xyhu0305@163.com

---
*For more details, please refer to the `notebooks` folder for code or the `report` folder for the full textual analysis.*
