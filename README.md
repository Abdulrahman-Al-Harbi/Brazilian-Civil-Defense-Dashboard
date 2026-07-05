# Civil Defense in Brazil Dashboard

A complete Data Analytics and Machine Learning project that analyzes Civil Defense occurrences in Brazil using Python and Power BI.

The project covers data preprocessing, exploratory data analysis (EDA), interactive dashboard development, and predictive modeling to gain insights into disaster events, their impacts, and complaint status.

---

# Dashboard Preview

![Dashboard](images/dashboard.png)

---

# Project Overview

This project analyzes Brazilian Civil Defense records to understand disaster patterns, human impacts, infrastructure damage, environmental issues, and economic losses.

The project combines:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Interactive Power BI Dashboard
- Machine Learning Classification
- Feature Importance Analysis
- Time-Series Forecasting

---

# Objectives

- Analyze disaster occurrences across Brazil.
- Identify the most common disaster categories.
- Explore complaint distribution across states and cities.
- Analyze human casualties caused by disasters.
- Compare economic losses with government expenditure.
- Build an interactive Power BI dashboard.
- Predict complaint validity using Machine Learning.

---

# Dashboard Features

The interactive dashboard includes:

- Complaint count by city
- Brazil geographic distribution map
- Complaint status over time
- Human casualties distribution
- Economic loss versus expenditure
- Disaster category distribution
- Yearly KPIs
- Interactive filters by:
  - Complaint Status
  - State
  - City

---

# Exploratory Data Analysis

## Monthly Trend

![Monthly Trend](images/01_monthly_trend.png)

---

## Disaster Categories

![Disaster Categories](images/02_disaster_types.png)

---

## Geographic Distribution

![Geographic Distribution](images/03_geography.png)

---

## Human Casualties

![Human Casualties](images/04_human_impact.png)

---

## Infrastructure Damage

![Infrastructure Damage](images/05_infra_by_category.png)

---

## Environmental Issues

![Environmental Issues](images/06_environmental_issues.png)

---

## Economic Loss versus Expenditure

![Economic Loss](images/07_loss_vs_expenditure.png)

---

## Correlation Analysis

![Correlation](images/08_correlation.png)

---

## Complaint Status

![Complaint Status](images/09_status_by_category.png)

---

# Machine Learning

The notebook also includes a Machine Learning model that predicts whether a complaint is likely to be classified as **Valid**.

## Confusion Matrix

![Confusion Matrix](images/10_confusion_matrix.png)

---

## Feature Importance

![Feature Importance](images/11_feature_importance.png)

The most influential features are:

- Month
- State
- Population
- Disaster Category

---

## Three-Month Forecast

![Forecast](images/12_forecast.png)

---

# Project Structure

```text
civil-defense-brazil/
│
├── README.md
├── LICENSE
│
├── data/
│   ├── civil_defense_br.csv
│   └── civil_defense_clean.csv
│
├── notebooks/
│   └── civil_defense_full_project.ipynb
│
├── powerbi/
│   └── civil_defense_dashboard.pbix
│
└── images/
    ├── dashboard.png
    ├── 01_monthly_trend.png
    ├── 02_disaster_types.png
    ├── 03_geography.png
    ├── 04_human_impact.png
    ├── 05_infra_by_category.png
    ├── 06_environmental_issues.png
    ├── 07_loss_vs_expenditure.png
    ├── 08_correlation.png
    ├── 09_status_by_category.png
    ├── 10_confusion_matrix.png
    ├── 11_feature_importance.png
    └── 12_forecast.png
```

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Power BI

---

# Dataset

This project uses the **Civil Defense Occurrences** dataset, which contains records of civil defense events in Brazil, including:

- Disaster category
- State
- City
- Population
- Human casualties
- Infrastructure damage
- Environmental impacts
- Economic losses
- Complaint status

Original dataset:

https://www.kaggle.com/datasets/juliotorniero/civil-defense-occurrences

The repository contains:

- **civil_defense_br.csv** – Original dataset
- **civil_defense_clean.csv** – Cleaned dataset used for analysis

---

# Key Analyses

- Data preprocessing and cleaning
- Missing value handling
- Disaster category analysis
- Geographic analysis
- Human casualty analysis
- Infrastructure damage analysis
- Environmental issue analysis
- Economic loss analysis
- Correlation analysis
- Complaint status analysis
- Machine Learning classification
- Feature importance
- Forecasting

---

# Power BI Dashboard

The interactive dashboard is included in:

```text
powerbi/civil_defense_dashboard.pbix
```

---

# Notebook

The complete Python workflow is available in:

```text
notebooks/civil_defense_full_project.ipynb
```

---

# Notes

This project was developed for educational and portfolio purposes.

The original dataset belongs to its respective authors and is publicly available on Kaggle.

---

# Author

**Abdulrahman Alharbi**
