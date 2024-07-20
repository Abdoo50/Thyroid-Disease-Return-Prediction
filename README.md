# Thyroid Disease Return Prediction Project

## Problem Statement
We aim to create a Power BI dashboard for analyzing thyroid disease and develop a machine learning model to predict the recurrence of thyroid cancer.

## Solution Approach
The project involves two major components: data analysis and machine learning. The steps include:
1. **Data Analysis**: Creating interactive dashboards in Power BI to visualize patient demographics, disease characteristics, and treatment outcomes.
2. **Machine Learning**: Developing a predictive model to foresee cancer recurrence using Python.

## Tools Used
- **SQL Server**: For data extraction and analysis.
- **Power BI**: For data visualization.
- **Python**: For machine learning model development and deployment using Streamlit.

## Key Performance Indicators (KPIs)
### Patient Demographics
1. **Total Patients**: Total number of patients.
2. **Average Age**: Average age of the patients.
3. **Gender Distribution**: Male and female percentages.
4. **Smoking Prevalence**: Percentage of smokers.

### Disease Characteristics
1. **Thyroid Function Distribution**: Various thyroid function statuses.
2. **Physical Examination Findings**: Distribution of examination results.
3. **Types of Thyroid Cancer**: Percentages of different thyroid cancer types.

### Risk and Severity Indicators
1. **Cancer Risk Levels**: Distribution of cancer risk levels.
2. **Tumor Size Distribution**: Distribution of tumor sizes.
3. **Lymph Node Involvement**: Percentage with lymph node involvement.
4. **Metastasis Status**: Percentage with metastasis.

### Treatment Outcomes
1. **Treatment Response Rates**: Distribution of treatment responses.
2. **Cancer Recurrence Rate**: Percentage of recurrence.
3. **Stage of Cancer at Diagnosis**: Distribution of cancer stages.

### Survival and Prognosis
1. **Survival Rates**: Survival rates by stage and treatment.
2. **Prognosis Correlation**: Correlation between risk factors and outcomes.

## Power BI Dashboards
### Patient Demographics and Behavior
![Patient Demographics and Behavior](https://github.com/Abdoo50/Thyroid-Disease-Return-Prediction/blob/main/Patient%20Demographics%20and%20Behavior.png)

### Disease Characteristics and Risk Indicators
![Disease Characteristics and Risk Indicators](https://github.com/Abdoo50/Thyroid-Disease-Return-Prediction/blob/main/Disease%20Characteristics%20and%20Risk%20Indicators.png)

## Dataset Features
### Age
- **Description**: Age at diagnosis or treatment.
- **Summary**: Patient's age during diagnosis or treatment.

### Gender
- **Description**: Male (M) or Female (F).
- **Summary**: Patient's gender.

### Smoking
- **Description**: Current smoking status.
- **Summary**: Smoking status.

### Hx Smoking
- **Description**: History of smoking.
- **Summary**: Smoking history.

### Hx Radiotherapy
- **Description**: History of radiotherapy.
- **Summary**: Radiotherapy history.

### Thyroid Function
- **Description**: Thyroid gland function status.
- **Summary**: Thyroid function status.

### Physical Examination
- **Description**: Clinical examination findings of the thyroid.
- **Summary**: Physical exam results.

### Adenopathy
- **Description**: Presence and location of enlarged lymph nodes.
- **Summary**: Adenopathy status.

### Pathology
- **Description**: Type of thyroid cancer diagnosed.
- **Summary**: Thyroid cancer type.

### Focality
- **Description**: Unifocal or multifocal cancer.
- **Summary**: Cancer focality.

### Risk
- **Description**: Cancer risk level.
- **Summary**: Cancer risk category.

### T (Tumor Classification)
- **Description**: Size and extent of the primary tumor.
- **Summary**: Tumor classification.

### N (Nodal Classification)
- **Description**: Lymph node involvement.
- **Summary**: Nodal classification.

### M (Metastasis Classification)
- **Description**: Presence of metastasis.
- **Summary**: Metastasis classification.

### Stage
- **Description**: Overall cancer stage.
- **Summary**: Cancer stage.

### Response
- **Description**: Treatment response.
- **Summary**: Treatment response status.

### Recurred
- **Description**: Cancer recurrence status.
- **Summary**: Recurrence status.

## Notebook Description
The Jupyter notebook titled [thyroid-disease-prediction.ipynb](https://github.com/Abdoo50/Thyroid-Disease-Return-Prediction/blob/main/thyroid-disease-prediction.ipynb) includes the following:
1. **Data Cleaning**: Preparing the dataset for analysis and modeling.
2. **Data Visualization**: Generating insights through visual representations.
3. **Feature Engineering**: Creating new features to enhance model performance.
4. **Model Building**: Developing and evaluating machine learning models to predict thyroid disease recurrence.
5. **Model Deployment**: Using Streamlit for easy user interaction with the predictive model.
