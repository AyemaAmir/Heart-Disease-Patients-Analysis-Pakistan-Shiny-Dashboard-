# Heart-Disease-Patients-Analysis-Pakistan-Shiny-Dashboard-
📌 Overview

This project applies statistical analysis, data visualization, and machine learning techniques to the Heart Disease Dataset to identify key risk factors and predict the likelihood of heart disease. It combines data preprocessing, exploratory data analysis (EDA), predictive modeling, and clustering with a user-friendly Shiny dashboard for interactive insights.

⚙️ Features

EDA (Exploratory Data Analysis):

Symptom vs severity gap analysis

Multi-disease risk detection (kidney, diabetes + heart severity)

Gender & age-specific risk factors

Blood & biochemical markers impact

Statistical Tests:

Normality (Shapiro-Wilk)

Chi-square tests for lifestyle factors

Kruskal-Wallis for age vs severity

ECG & stress test indicators

Machine Learning Models:

Random Forest severity prediction

Logistic Regression mortality prediction

Clustering of patients into risk groups

Policy Recommendations:

Symptom-based risk awareness

Multi-disease screening integration

Special focus on middle-aged females

Triage-based risk stratification

Gender-sensitive healthcare strategies

📊 Dataset

Source: [ Clinical dataset of heart patients in Pakistan](https://opendata.com.pk/dataset/heart-patients-in-pakistan/resource/70aec9b8-7674-492f-a390-1bd72666744f)

Attributes: Demographics, lifestyle factors, comorbidities, biochemical & blood markers, ECG & stress test results

Target Variables:

num → Severity level of heart disease

Mortality → Survival status

🛠️ Tech Stack
🔹 Data Handling

dplyr, tidyr, readr, stringr – data cleaning, transformation, and manipulation

🔹 Statistical Testing

stats, car – hypothesis testing and validation

🔹 Visualization

ggplot2, plotly – interactive and static visualizations

🔹 Modeling

randomForest, nnet, caret, MASS – machine learning & predictive modeling

🔹 Clustering & Dimensionality Reduction

cluster – segmentation and pattern discovery

🔹 Dashboard Interface

shiny, shinydashboard – interactive user interface for model insights

<img width="731" height="350" alt="image" src="https://github.com/user-attachments/assets/1f07f55f-9720-4b43-a9d2-a48ade78cce4" />

<img width="735" height="351" alt="image" src="https://github.com/user-attachments/assets/86f393bf-01b0-43e4-be4a-da14ebf11298" />

<img width="711" height="347" alt="image" src="https://github.com/user-attachments/assets/ed6a2076-1619-4720-a057-a08a6720f8a9" />

<img width="672" height="335" alt="image" src="https://github.com/user-attachments/assets/272830b3-f32a-4d38-a051-785cc3fc707b" />



📌 Future Work

Deployment on Shiny Server / RStudio Connect for public access

Integration with real-time hospital data

Expand dataset with longitudinal follow-up records
