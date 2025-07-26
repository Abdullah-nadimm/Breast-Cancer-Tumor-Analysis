# 🧬 Breast Cancer Tumor Analysis (Python + SQL)

## 🚀 TL;DR

Analyzed breast cancer data using Python and SQL to identify key tumor features correlated with malignancy. Combined statistical testing, exploratory analysis, and SQL joins/views to discover that **tumor area, concavity, and concave points** are the most predictive indicators of cancer diagnosis.

---

## ❓ Problem Statement

Early detection of malignant tumors is critical for improving breast cancer survival rates. This project aimed to uncover the most influential tumor features associated with malignancy by analyzing diagnostic data using statistical and SQL-based techniques.

---

## ✅ Solution Overview

Developed a hybrid data pipeline integrating **PostgreSQL** for structured querying and **Python** for statistical analysis and visualization. The objective was to compare benign vs. malignant tumor attributes and highlight the strongest predictors of malignancy.

---

## 🧰 Tools & Technologies

| Tool / Tech      | Purpose                                               |
|------------------|--------------------------------------------------------|
| ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) | Data analysis, visualization, statistical testing        |
| ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white) | Data manipulation and feature selection                  |
| ![Seaborn](https://img.shields.io/badge/Seaborn-3772A3?style=for-the-badge&logo=python&logoColor=white) | Visualizations (boxplots, pairplots, heatmaps)           |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white) | SQL joins, views, and feature engineering                |

---

## 🔍 Key Contributions

### 📊 Data Querying (PostgreSQL)
- Created SQL views with **joins** and **window functions** to summarize tumor types and group by diagnosis
- Filtered key numeric attributes like **area mean**, **concavity mean**, and **radius mean**

### 🧠 Exploratory Data Analysis (Python)
- Visualized distributions and correlations using **Seaborn** and **Matplotlib**
- Used heatmaps and pairplots to detect patterns and collinearity across features

### 🧪 Statistical Testing
- Conducted **t-tests** and **ANOVA** to highlight significant differences between benign and malignant tumors
- Found statistically significant separation in features like **concavity mean**

### 🔁 Data Integration
- Built a clean workflow combining SQL output with Python analysis for reproducibility
- Streamlined the diagnostic summary pipeline for easy stakeholder interpretation

---

## 📈 Findings & Insights

- **Concavity mean**, **concave points mean**, and **area mean** showed the **strongest correlation** with malignant tumors
- Benign tumors had **lower variance** in shape-related metrics
- The final correlation heatmap clearly outlined which features were most predictive

---

## 📸 Sample Visuals

### 🧬 Concavity Mean by Diagnosis

> Visualizes the difference in concavity between benign and malignant tumors

![Concavity Mean by Diagnosis](Concavity Means by Diagnosis)

### 🔥 Heatmap of Feature Correlation

![Radius and Area Mean by diagnosis](images/correlation-heatmap.png)

> Add images to the `/images/` folder and replace filenames accordingly.

---

## 🧠 Key Learnings

- SQL window functions and views are powerful for data preparation in diagnostic studies
- Data storytelling is enhanced with effective visualizations and statistical rigor
- Cross-functional workflows (SQL + Python) allow for flexible, scalable health data analysis

---


