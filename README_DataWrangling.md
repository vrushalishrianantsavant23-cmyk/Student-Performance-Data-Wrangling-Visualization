# 📊 Student Performance — Data Wrangling & Visualization

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-purple?logo=pandas)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Charts-brightgreen)
![Google Colab](https://img.shields.io/badge/Google-Colab-orange?logo=googlecolab)

---

## 📌 Project Description

This project performs **Data Wrangling and Visualization** on a Student Performance Dataset.  
It covers the full data preprocessing pipeline — from handling missing values and outliers to feature scaling — followed by rich interactive and static visualizations to uncover meaningful insights about student performance.

> **Submitted by:** Vrushali Savant  
> **Enrollment Number:** 23STUCHH010296  
> **Under the Guidance of:** Suresh Sir  

---

## 🎯 Objectives

- Clean and preprocess raw student data
- Handle missing values, remove outliers, encode categories, and scale features
- Visualize key patterns using Matplotlib, Seaborn, and Plotly
- Answer analytical questions through data-driven charts

---

## 📂 Dataset

| Detail | Info |
|--------|------|
| **Name** | Student Performance Dataset |
| **File** | `student_performance_dataset_link_version.csv` |
| **Key Columns** | `OverallScore`, `FinalScore`, `MidtermScore`, `StudyHours`, `AttendanceRate`, `Gender`, `Class` |

---

## 🔧 Data Wrangling Steps

1. **Missing Value Treatment** — Numeric columns filled with median; Categorical with mode
2. **Outlier Removal** — IQR (Interquartile Range) method applied on all numeric columns
3. **Label Encoding** — Categorical columns converted to numeric values
4. **Feature Scaling** — Min-Max Normalization applied to numeric features
5. **Cleaned Dataset Saved** — `student_performance_cleaned_advanced.csv`

---

## 📊 Visualizations

| Chart | Library | Insight |
|-------|---------|---------|
| Histogram — Overall Score | Matplotlib | Score distribution across students |
| Histogram — Study Hours | Matplotlib | Study hours pattern |
| Correlation Heatmap | Seaborn | Relationships between all numeric features |
| Box Plot — Final Score | Seaborn | Outlier detection in Final Scores |
| Bar Chart — Score by Gender | Seaborn | Gender-wise performance comparison |
| Interactive Scatter Plot | Plotly | Study Hours vs Overall Score (colored by Gender) |
| 3D Scatter Plot | Plotly | Study Hours vs Attendance vs Score |
| Interactive Histogram | Plotly | Overall Score distribution by Gender |
| Bar Chart — Attendance by Class | Plotly | Class-wise attendance comparison |
| Annotated Correlation Heatmap | Plotly | Full numeric correlation matrix |

---

## ❓ Analytical Questions Answered

- **Q1** — What is the distribution of students' Overall Score?
- **Q2** — How does average Attendance Rate vary across classes?
- **Q3** — What is the relationship between Midterm Score and Final Score?
- **Q4** — How are the various factors in the dataset related to each other?

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Programming Language |
| Pandas | Data Loading & Wrangling |
| NumPy | Numerical Operations |
| Matplotlib | Static Visualizations |
| Seaborn | Statistical Plots |
| Plotly | Interactive Visualizations |
| Scikit-learn | Label Encoding & Scaling |
| Google Colab | Development Environment |

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Mount Google Drive and upload the dataset CSV
3. Run all cells from top to bottom

---

## 📁 Project Structure

```
Student-Performance-Data-Wrangling/
├── Data_Wrangling_and_Visualization_.ipynb   ← Main Notebook
├── requirements.txt                           ← Dependencies
└── README.md                                  ← Project Documentation
```

---

## 🙌 Acknowledgements

- Guidance by **Suresh Sir**
- Dataset used for educational purposes

---

*Made with ❤️ by Vrushali Savant*
