# Heart Disease Patients Analysis-Pakistan
📌 **Overview**

This project applies statistical analysis, data visualization, and machine learning techniques to the Heart Disease Dataset to identify key risk factors and predict the likelihood of heart disease. It combines data preprocessing, exploratory data analysis (EDA), predictive modeling, and clustering with a user-friendly Shiny dashboard for interactive insights.

⚙️**Features**
**EDA (Exploratory Data Analysis):**

- Symptom vs severity gap analysis

- Multi-disease risk detection (kidney, diabetes + heart severity)

- Gender & age-specific risk factors

- Blood & biochemical markers impact

**Statistical Tests:**

- Normality (Shapiro-Wilk)

- Chi-square tests for lifestyle factors

- Kruskal-Wallis for age vs severity

- ECG & stress test indicators

**Machine Learning Models:**

- Random Forest severity prediction

- Logistic Regression mortality prediction

- Clustering of patients into risk groups

**Policy Recommendations:**

- Symptom-based risk awareness

- Multi-disease screening integration

- Special focus on middle-aged females

- Triage-based risk stratification

- Gender-sensitive healthcare strategies

📊 **Dataset**

**Source:** [ Clinical dataset of heart patients in Pakistan](https://opendata.com.pk/dataset/heart-patients-in-pakistan/resource/70aec9b8-7674-492f-a390-1bd72666744f)

**Attributes**: Demographics, lifestyle factors, comorbidities, biochemical & blood markers, ECG & stress test results

**Target Variables:**

- num → Severity level of heart disease

- Mortality → Survival status

🛠️**Tech Stack**

🔹 **Data Handling**

dplyr, tidyr, readr, stringr – data cleaning, transformation, and manipulation

🔹**Statistical Testing**

stats, car – hypothesis testing and validation

🔹 **Visualization**

ggplot2, plotly – interactive and static visualizations

🔹 **Modeling**

randomForest, nnet, caret, MASS – machine learning & predictive modeling

🔹 **Clustering & Dimensionality Reduction**

cluster – segmentation and pattern discovery

🔹 **Dashboard Interface**

shiny, shinydashboard – interactive user interface for model insights

<img width="1176" height="560" alt="image" src="https://github.com/user-attachments/assets/1a98ea49-a7b6-4c47-9b00-d4cb92fa87da" />

<img width="1209" height="582" alt="image" src="https://github.com/user-attachments/assets/1d707ccf-235c-4fc9-aae8-bf8d7d117aaa" />

<img width="1219" height="583" alt="image" src="https://github.com/user-attachments/assets/2d5e777a-5045-464b-9e8f-f005e7b19211" />

<img width="1116" height="550" alt="image" src="https://github.com/user-attachments/assets/c22f2e38-faa0-4267-90c4-38bf84fd9dca" />

📌 **Future Work**

- Deployment on Shiny Server / RStudio Connect for public access

- Integration with real-time hospital data

- Expand dataset with longitudinal follow-up records
