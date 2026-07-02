# 🫀 Healthcare Analytics Solution: Heart Disease Risk Prediction & Clinical Decision Dashboard

> **End-to-End Clinical Data Pipeline · Statistical Analysis · Machine Learning · Interactive R Shiny Dashboard**

# 📌 Project at a Glance

| Category | Details |
|-----------|---------|
| **Domain** | Healthcare Analytics & Clinical Decision Support |
| **Programming Language** | R |
| **Project Type** | End-to-End Data Analytics & Predictive Modeling |
| **Dataset** | [ Clinical dataset of heart patients in Pakistan](https://opendata.com.pk/dataset/heart-patients-in-pakistan/resource/70aec9b8-7674-492f-a390-1bd72666744f) |
| **Dataset Size** | Several hundred patient records · 60+ clinical variables |
| **Techniques** | Data Cleaning · EDA · Statistical Analysis · Machine Learning · Clustering · Dimensionality Reduction |
| **Dashboard** | Interactive R Shiny Application |
| **Outcome** | Risk Prediction · Patient Segmentation · Actionable Healthcare Recommendations |

# 🩺 Problem

Cardiovascular disease is the leading cause of death globally, claiming roughly 17.9 million lives annually (WHO). In Pakistan, the burden is compounded by late-stage diagnosis, poor symptom awareness among frontline workers, and a lack of structured risk screening tools — patients typically present to hospitals only after symptoms become severe.

Existing predictive models for heart disease risk are overwhelmingly built on Western clinical datasets such as the Cleveland dataset, which do not reflect Pakistani patient demographics, comorbidity profiles, or healthcare patterns.

This project addresses that gap directly. I sourced a real-world clinical dataset of heart disease patients from Pakistan — containing several hundred records and over 60 variables across demographics, lifestyle factors, biochemical markers, cardiac diagnostics, and outcomes — and built a full analytics pipeline from raw, inconsistent data through to an interactive clinical decision support dashboard.

**The core deliverable is not a model. It is an actionable system that tells a clinician or health policymaker: who is at risk, how severe that risk is, why it exists, and what to do about it.**

# 🚀 What This Project Demonstrates

- Collection and preparation of real-world clinical datasets
- Cleaning and standardizing messy healthcare data
- Exploratory Data Analysis (EDA) for pattern discovery
- Selection of appropriate statistical tests based on data characteristics
- Development of interpretable machine learning models
- Patient risk segmentation using unsupervised learning
- Translation of analytical findings into business-friendly recommendations
- Delivery of insights through an interactive R Shiny dashboard


---

# ⚙️ Analytics Pipeline

```text
Clinical Dataset
      │
      ▼
Data Cleaning & Preprocessing
      │
      ▼
Exploratory Data Analysis (EDA)
      │
      ▼
Statistical Analysis
      │
      ▼
Machine Learning Models
      │
      ▼
Patient Risk Segmentation
      │
      ▼
Interactive R Shiny Dashboard
      │
      ▼
Clinical Insights & Recommendations
```

---

# 📊 Exploratory Data Analysis (EDA)

| Analysis | Purpose | Key Outcome |
|----------|---------|-------------|
| **Symptom–Severity Analysis** | Explore relationship between symptoms and disease severity | Identified chest pain as a strong indicator of severe disease. |
| **Multi-Disease Risk Analysis** | Assess impact of diabetes and kidney dysfunction | High comorbidity patients represented over **30%** of severe cases. |
| **Female Risk Profiling** | Analyze cardiovascular risk in women aged 45–59 | Revealed elevated risk despite relatively normal renal markers. |
| **Comorbidity Cluster Analysis** | Identify patients with multiple chronic conditions | Highlighted high-risk patient groups requiring early intervention. |
| **Triage Risk Scoring** | Develop rule-based clinical risk categories | Classified patients into High, Moderate, and Low risk groups. |
| **Blood Marker Analysis** | Evaluate hematological markers | Showed single biomarkers are insufficient predictors without clinical context. |
| **Follow-Up Analysis** | Examine relationship between follow-up and mortality | Regular follow-up was associated with improved survival outcomes. |

---

# 🔬 Statistical Analysis

Statistical methods were selected according to variable types and distribution rather than applying a single approach across the dataset.

| Technique | Purpose | Why Selected |
|------------|---------|--------------|
| **Shapiro-Wilk Test** | Test data normality | Guided the selection of appropriate statistical methods. |
| **Chi-Square Test** | Analyze categorical relationships | Measured associations between lifestyle, clinical factors, and disease severity. |
| **Kruskal-Wallis Test** | Compare severity groups | Non-parametric alternative to ANOVA for multiple groups. |
| **Mann-Whitney U Test** | Compare two independent groups | Suitable for non-normally distributed variables. |
| **Spearman Correlation** | Evaluate biomarker relationships | Measures monotonic relationships without assuming normality. |

---

# 🤖 Machine Learning Pipeline

All predictive models were trained using an **80/20 stratified train-test split** following feature engineering and multicollinearity assessment.

| Technique | Business Purpose | Why Selected |
|------------|-----------------|--------------|
| **Data Cleaning & Standardization** | Prepare raw healthcare records | Improved consistency and data quality before analysis. |
| **Feature Engineering** | Create clinically meaningful variables | Generated kidney risk, diabetes risk, and composite triage scores. |
| **Multinomial Logistic Regression** | Predict disease severity | Provides an interpretable baseline for multi-class classification. |
| **Random Forest** | Predict severity & rank predictors | Captures complex relationships while identifying feature importance. |
| **Binary Logistic Regression + StepAIC** | Predict mortality | Produces interpretable probability estimates using significant predictors. |
| **Multicollinearity Analysis (VIF)** | Validate model assumptions | Removed redundant predictors before model fitting. |
| **Weighted Risk Score** | Generate actionable patient risk score | Combined significant predictors into a single clinical score. |
| **K-Means Clustering** | Segment patients into risk groups | Identified clinically meaningful patient clusters. |
| **Principal Component Analysis (PCA)** | Visualize cluster separation | Reduced dimensionality while preserving data patterns. |

---

# 🛠 Tech Stack

| Category | Tools |
|-----------|------|
| **Programming** | R |
| **Data Wrangling** | dplyr · tidyr · readr · stringr |
| **Statistical Analysis** | stats · car |
| **Machine Learning** | randomForest · caret · MASS · nnet |
| **Clustering** | cluster · PCA |
| **Visualization** | ggplot2 · plotly |
| **Dashboard Development** | shiny · shinydashboard |

---

# 🎯 Skills Demonstrated

**Data Engineering:** Data Collection · Data Cleaning · Data Preprocessing · Feature Engineering

**Analytics:** Exploratory Data Analysis (EDA) · Statistical Hypothesis Testing · Correlation Analysis · Non-Parametric Statistics

**Machine Learning:** Predictive Modeling · Multi-Class Classification · Binary Classification · Feature Selection · Model Interpretability · Clustering · Dimensionality Reduction

**Visualization & Reporting:** Data Visualization · Interactive Dashboard Development · Data Storytelling · Clinical Decision Support

**Domain Expertise:** Healthcare Analytics · Patient Risk Stratification · Mortality Prediction · Data-Driven Recommendations

---

# 📷 Interactive Dashboard

All analyses are presented through an interactive **R Shiny Dashboard**, allowing clinicians and non-technical users to explore findings without reading code.

| Module | Highlights |
|---------|------------|
| **EDA** | Symptom analysis, comorbidity patterns, female risk profiles, blood marker exploration, follow-up analysis |
| **Statistical Analysis** | Normality testing, hypothesis testing, ECG analysis, lifestyle associations, biomarker correlations |
| **Machine Learning** | Random Forest feature importance, mortality prediction, PCA visualization, patient clustering |
| **Recommendations** | Data-driven healthcare recommendations for clinicians and policymakers |

---


<img width="1176" height="560" alt="image" src="https://github.com/user-attachments/assets/1a98ea49-a7b6-4c47-9b00-d4cb92fa87da" />

<img width="1209" height="582" alt="image" src="https://github.com/user-attachments/assets/1d707ccf-235c-4fc9-aae8-bf8d7d117aaa" />

<img width="1219" height="583" alt="image" src="https://github.com/user-attachments/assets/2d5e777a-5045-464b-9e8f-f005e7b19211" />

<img width="1116" height="550" alt="image" src="https://github.com/user-attachments/assets/c22f2e38-faa0-4267-90c4-38bf84fd9dca" />
