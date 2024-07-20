# Thyroid Disease Return Prediction Project

### Problem Statement

The goal of this project is to analyze thyroid disease data and develop a machine learning model to predict the recurrence of thyroid cancer. The project involves creating a Power BI dashboard for data visualization and analysis, and subsequently building a predictive model to forecast cancer recurrence.

### Key Performance Indicators (KPIs) for Thyroid Disease Analysis

**Patient Demographics**
1. **Total Patients:** Total number of patients in the dataset.
2. **Average Age:** Average age of the patients.
3. **Gender Distribution:** Percentage of male and female patients.
4. **Smoking Prevalence:** Percentage of patients who are smokers.

**Disease Characteristics**
1. **Thyroid Function Distribution:** Percentage of patients with different thyroid function statuses.
2. **Physical Examination Findings:** Distribution of physical examination results (e.g., multinodular goiter, single nodular goiter).
3. **Types of Thyroid Cancer:** Percentage of each type of thyroid cancer (e.g., Papillary, Micropapillary).

**Risk and Severity Indicators**
1. **Cancer Risk Levels:** Distribution of cancer risk levels (low, intermediate, high).
2. **Tumor Size Distribution:** Distribution of tumor sizes (e.g., T1a, T2).
3. **Lymph Node Involvement:** Percentage of patients with lymph node involvement (e.g., N0, N1a, N1b).
4. **Metastasis Status:** Percentage of patients with and without metastasis.

**Treatment Outcomes**
1. **Treatment Response Rates:** Distribution of treatment responses (e.g., excellent, structural incomplete).
2. **Cancer Recurrence Rate:** Percentage of patients who experienced cancer recurrence.
3. **Stage of Cancer at Diagnosis:** Distribution of cancer stages (e.g., Stage I, II, III, IV).

**Survival and Prognosis**
1. **Survival Rates:** If available, survival rates based on stages, treatment, etc.
2. **Prognosis Correlation:** Correlation between different risk factors and treatment outcomes.

### Power BI Dashboards

#### Patient Demographics and Behavior
The first Power BI dashboard provides an overview of patient demographics and behavior. The visualizations include:
- Total number of patients
- Average age of patients
- Gender distribution
- Smoking prevalence among patients

![Patient Demographics and Behavior](https://github.com/Abdoo50/Thyroid-Disease-Return-Prediction/blob/main/Patient%20Demographics%20and%20Behavior.png)

#### Disease Characteristics and Risk Indicators
The second dashboard focuses on disease characteristics and risk indicators. The visualizations include:
- Thyroid function distribution
- Physical examination findings
- Types of thyroid cancer
- Cancer risk levels
- Tumor size distribution
- Lymph node involvement
- Metastasis status

![Disease Characteristics and Risk Indicators](https://github.com/Abdoo50/Thyroid-Disease-Return-Prediction/blob/main/Disease%20Characteristics%20and%20Risk%20Indicators.png)

### Project Description

#### 1. Description

In this project, you will:
1. Understand and clean the data to ensure it's suitable for analysis and modeling.
2. Visualize the data to gain insights and create a dashboard for easy data interpretation.
3. Engineer features to improve the performance of the machine learning model.
4. Build and evaluate machine learning models to predict thyroid disease.
5. Deploy the final model using Streamlit for easy user interaction.

#### 2. Features and Project Purpose

This dataset contains 13 clinicopathologic features aiming to predict the recurrence of well-differentiated thyroid cancer. Collected over 15 years, each patient was followed for at least 10 years.

#### Source
The data was procured from thyroid disease datasets provided by the UCI Machine Learning Repository.

#### Features Declaration of Dataset
- **Age:** Age of the patient during diagnosis or treatment.
- **Gender:** The gender of the patient (male or female).
- **Smoking:** Current smoking status of the patient.
- **Hx Smoking:** History of smoking (ever smoked or not).
- **Hx Radiotherapy:** History of radiotherapy treatment.
- **Thyroid Function:** Status of thyroid gland function.
- **Physical Examination:** Physical examination results of the thyroid gland.
- **Adenopathy:** Presence and location of enlarged lymph nodes.
- **Pathology:** Type of thyroid cancer based on pathology.
- **Focality:** Whether cancer is in one (unifocal) or multiple locations (multifocal).
- **Risk:** Cancer risk category (low, intermediate, or high).
- **T (Tumor Classification):** Classification of tumor size and extent of invasion.
- **N (Nodal Classification):** Lymph node involvement status.
- **M (Metastasis Classification):** Presence or absence of distant metastasis.
- **Stage:** Overall cancer stage based on the TNM system.
- **Response:** Patient's response to treatment.
- **Recurred:** Whether the cancer has recurred after treatment.

Each feature provides valuable insights into the patient’s condition and helps in the overall assessment, diagnosis, and treatment planning for thyroid cancer.

### Notebook Description

The notebook titled "thyroid-disease-prediction.ipynb" contains the following steps:

1. **Data Loading:** Loading the dataset and understanding its structure.
2. **Data Cleaning:** Handling missing values, encoding categorical variables, and feature scaling.
3. **Exploratory Data Analysis (EDA):** Visualizing the data to understand the distribution of features and target variable.
4. **Feature Engineering:** Creating new features or modifying existing ones to improve model performance.
5. **Model Building:** Training different machine learning models to predict thyroid cancer recurrence.
6. **Model Evaluation:** Evaluating the models using appropriate metrics to determine their performance.
7. **Deployment:** Deploying the final model using Streamlit for user interaction.

You can view the notebook [here](https://github.com/Abdoo50/Thyroid-Disease-Return-Prediction/blob/main/thyroid-disease-prediction.ipynb).
