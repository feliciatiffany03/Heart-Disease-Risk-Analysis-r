# Heart Disease Risk Analysis

### Exploring Cholesterol, Blood Pressure, Age, and Other Heart Disease Factors Using R & Shiny


## 📌 Project Overview

Heart disease is one of the major global health challenges addressed under **SDG 3: Good Health and Well-Being**.

This project presents an exploratory data analysis and data visualization study of patient health data to investigate patterns associated with heart disease. The analysis focuses primarily on **cholesterol, blood pressure, and age**, while also exploring additional factors such as gender, blood sugar, maximum heart rate, chest pain, ST slope, exercise-induced angina, and Oldpeak.

The project combines **data analysis, visualization, data storytelling, and an interactive R Shiny dashboard** to communicate the findings in an accessible way.

---

## 🎯 Objectives

The objectives of this project are to:

- Explore patterns associated with heart disease in patient data.
- Analyze the relationship between cholesterol levels and heart disease status.
- Examine heart disease patterns across blood pressure and age groups.
- Explore additional patient and clinical factors associated with heart disease.
- Create clear and informative data visualizations.
- Develop an interactive Shiny dashboard for exploring the analysis.
- Communicate the findings through data storytelling and an infographic.

---

## 📊 Dataset

The project uses the **Heart Failure Prediction Dataset** from Kaggle.

**Dataset Source:**  
https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction

The documentation states that the patient data were collected from four institutions specializing in heart disease and health research.

### Main Variables

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

### Cholesterol

Cholesterol levels were categorized into:

- **Normal:** below 200 mg/dL
- **At Risk:** 200–239 mg/dL
- **High:** above 240 mg/dL

The analysis found that the high-cholesterol group contained a larger number of patients with heart disease compared with patients without heart disease.

### Blood Pressure

Resting blood pressure was categorized into:

- Normal
- Pre-Hypertensive
- Hypertension

The analysis examined the distribution of heart disease status across blood pressure categories, particularly within the high-cholesterol population.

### Age

Patients were grouped into different age categories to investigate differences in heart disease status across age groups.

The analysis showed a higher proportion of heart disease in several older age groups compared with younger groups.

### Additional Factors

The project also explored:

- Gender
- Blood sugar
- Maximum heart rate
- Chest pain
- ST slope
- Exercise-induced angina
- Oldpeak

These variables were visualized to identify differences in heart disease proportions across patient groups.

---

## 📈 Key Findings

The exploratory analysis identified several notable patterns:

- Patients in the **high-cholesterol** category had a higher proportion of heart disease in the analyzed dataset.
- Heart disease proportions varied across **blood pressure categories**.
- Several **older age groups** showed higher proportions of heart disease.
- **Chest pain type** showed substantial differences in heart disease proportions.
- The **low maximum heart rate** category had a high proportion of patients with heart disease.
- **Flat and down ST-slope** categories showed higher proportions of heart disease than the up-slope category.
- Patients experiencing **exercise-induced angina** represented a larger proportion of the heart disease group.
- Higher **Oldpeak** categories showed greater proportions of patients with heart disease.

> **Note:** These findings describe associations and patterns observed in the dataset. They should not be interpreted as evidence that an individual factor directly causes heart disease.

---

## 🌐 Interactive Shiny Dashboard

An interactive **R Shiny dashboard** was developed to allow users to explore the analysis dynamically.

The dashboard consists of three main sections:

### 1. Knowing Heart Disease

Provides background information about heart disease and explores several factors including blood pressure, blood sugar, age, cholesterol, and gender.

### 2. Patient Overview

Provides an overview of patient characteristics, cholesterol levels, heart disease status, and symptoms. Users can interact with the visualizations to explore different patient groups.

### 3. Conclusion

Summarizes the main findings of the analysis and connects the research to **SDG 3: Good Health and Well-Being**.

### 🔗 Live Dashboard

https://kelompokaol.shinyapps.io/DoesCholesterolCauseHeartDisease_AOL/

---

## 🖼️ Data Storytelling Infographic

The analysis was presented through an infographic focusing on the relationship between cholesterol and heart disease.

The infographic combines:

- Data visualizations
- Key statistics
- Health-related context
- Data-driven insights
- Preventive recommendations
- SDG 3 context

---

## 🛠️ Tools & Technologies

- **R**
- **R Markdown**
- **R Shiny**
- **Exploratory Data Analysis (EDA)**
- **Data Cleaning & Transformation**
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
