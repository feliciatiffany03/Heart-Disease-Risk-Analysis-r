# Heart-Disease-Risk-Analysis-r
# Heart Disease Risk Analysis

### Exploring Cholesterol, Blood Pressure, Age, and Other Heart Disease Factors Using R & Shiny

An exploratory data analysis and data visualization project investigating factors associated with heart disease using patient health data.

This project was developed as part of the Data Mining & Visualization course at Bina Nusantara University and focuses on data exploration, visualization, data storytelling, and interactive visualization using R Shiny.

---

## 📌 Project Overview

Heart disease is one of the major global health challenges addressed under **SDG 3: Good Health and Well-Being**.

This project explores patient health data to understand patterns associated with heart disease, with a primary focus on:

- Cholesterol levels
- Blood pressure
- Age
- Gender
- Blood sugar
- Maximum heart rate
- Chest pain
- ST slope
- Exercise-induced angina
- Oldpeak

The analysis aims to communicate the patterns found in the dataset through clear visualizations and an interactive Shiny dashboard.

---

## 🎯 Objectives

The main objectives of this project are to:

1. Explore the relationship between patient characteristics and heart disease status.
2. Identify patterns in cholesterol, blood pressure, and age among patients.
3. Analyze additional health-related factors associated with heart disease.
4. Create informative data visualizations to communicate the findings.
5. Develop an interactive Shiny dashboard for exploring the dataset.
6. Present the findings through data storytelling and an infographic.

---

## 📊 Dataset

The dataset used in this project is the **Heart Failure Prediction Dataset**, obtained from Kaggle.

**Source:**  
https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

The documentation states that the patient data were collected from four institutions specializing in heart disease and health research.

### Main Variables

The analysis explores variables including:

| Variable | Description |
|---|---|
| Age | Patient age |
| Sex | Patient gender |
| ChestPainType | Type of chest pain |
| RestingBP | Resting blood pressure |
| Cholesterol | Serum cholesterol level |
| FastingBS | Fasting blood sugar |
| MaxHR | Maximum heart rate |
| ExerciseAngina | Exercise-induced angina |
| Oldpeak | ST depression measurement |
| ST_Slope | Slope of the peak exercise ST segment |
| HeartDisease | Heart disease status |

---

## 🔎 Exploratory Data Analysis

The analysis focuses on several major factors associated with heart disease.

### 1. Cholesterol

Patients were categorized into:

- **Normal:** cholesterol below 200 mg/dL
- **At Risk:** 200–239 mg/dL
- **High:** above 240 mg/dL

The analysis shows that the high-cholesterol group contains a larger number of patients with heart disease compared with patients without heart disease.

---

### 2. Blood Pressure

Resting blood pressure was categorized into:

- Normal
- Pre-Hypertensive
- Hypertension

The analysis examines the distribution of heart disease status across these blood pressure categories, particularly within the high-cholesterol population.

---

### 3. Age

Patients were grouped into different age categories to explore how heart disease status varies across age groups.

The analysis shows a higher proportion of heart disease in several older age groups compared with younger groups.

---

### 4. Additional Factors

The interactive analysis also explores:

- Gender
- Blood sugar
- Maximum heart rate
- Chest pain type
- ST slope
- Exercise-induced angina
- Oldpeak

These variables provide additional perspectives on patterns within the heart disease population.

---

## 📈 Key Findings

Some notable patterns identified in the exploratory analysis include:

- High cholesterol is associated with a higher proportion of heart disease in this dataset.
- Heart disease proportions vary across blood pressure categories.
- Older age groups generally show higher proportions of heart disease.
- Patients with certain chest pain categories show substantially different heart disease proportions.
- Lower maximum heart rate categories show a higher proportion of patients with heart disease in the analyzed data.
- ST slope categories show noticeable differences in heart disease proportions.
- Patients experiencing exercise-induced angina show a higher proportion of heart disease in the dataset.
- Higher Oldpeak categories show a greater proportion of patients with heart disease.

> **Note:** These findings describe patterns and associations observed in the dataset. They should not be interpreted as proof that an individual factor directly causes heart disease.

---

## 📊 Visualizations

The project uses multiple visualization techniques, including:

- Stacked bar charts
- Percentage-based comparisons
- Distribution charts
- Correlation heatmap
- Interactive visualizations

The visualizations were designed to support data storytelling and make the relationships within the dataset easier to understand.

---

## 🌐 Interactive Shiny Dashboard

An interactive Shiny dashboard was developed to allow users to explore the findings dynamically.

### Dashboard Sections

**1. Knowing Heart Disease**

Provides background information and an overview of factors explored in the analysis.

**2. Patient Overview**

Allows users to explore patient characteristics, cholesterol levels, heart disease status, and related symptoms.

**3. Conclusion**

Summarizes the main findings and connects the analysis to SDG 3: Good Health and Well-Being.

### 🔗 Live Dashboard

https://kelompokaol.shinyapps.io/DoesCholesterolCauseHeartDisease_AOL/

---

## 🖼️ Data Storytelling Infographic

The findings were also presented through an infographic focusing on the relationship between cholesterol and heart disease.

![Heart Disease Infographic](poster/heart-disease-infographic.png)

---

## 🛠️ Tools & Technologies

- **R**
- **R Markdown**
- **R Shiny**
- **Data Cleaning & Transformation**
- **Exploratory Data Analysis (EDA)**
- **Data Visualization**
- **Data Storytelling**

---

## 📁 Project Structure

```text
heart-disease-risk-analysis/
│
├── README.md
│
├── data/
│   └── heart.csv
│
├── R/
│   └── DataMining_HeartDisease.Rmd
│
├── poster/
│   └── heart-disease-infographic.png
│
├── report/
│   └── documentation.pdf
│
└── visualizations/
    ├── cholesterol.png
    ├── blood-pressure.png
    ├── age.png
    └── ...
