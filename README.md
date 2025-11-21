# Diabetes-Readmission-within-30-days-Analysis

**Objective**
<p>Analyze patterns in 30-day hospital readmissions among patients with diabetes and identify key factors contributing to early readmission. The goal is to enable healthcar providers to design targeted intervention strategies that reduce preventable readmissions.<p>

**Measure**
- Percentage of diabetes patients(see definition below) who are readmitted within 30 days of discharge.
  
**Key Findings**
- Readmission rate: 11.0% vs. 18-20% national average
- Model Performance: AUC 0.60-0.65(moderate discrimination)
- Top predictors: medication volume, comorbidity load, care coordination gaps
- Interventions: pharmacist-led reviews, structured care coordination, post-discharge telehealth

## Methodology
**Identifying Diabetes Patients**
- Inclusion criteria: Any of the three diagnosis fields (diag_1, diag_2, diag_3) contains ICD-9 code indicating diabetes.
- Relevant ICD-9 codes:
  - **250.00**: Diabetes without complication
  - **250.02**: Diabetes, uncontrolled
  - **250.40**: Diabetes with renal manifestations
  - (and other codes beginning with 250)

**Data Preparation**
 - Handle missing values (including denoted by "?" in dataset).
 - Create binary indicator for target variable: readmission <30days.
 - Engineer feature indicators to capture patient characteristics and risk factors.
 - Generate risk score and assign risk levels to flag high-risk patients.


**​Deliverables**
- Python Analysis: Data prep, analysis, correlation modeling, and visual outputs.
- Interactive Dashboard: Identifies diabetic patients at risk of readmission within 30 days.
- One Pager: Comprehensive overview of Dashboard for At-Risk Patients.
(Links for Deliverables are pasten below.)

# Link
- [GitHub Python Analysis Page](https://tamiyad.github.io/Diabetes-Readmission-within-30-days-Analysis/)
- [Website for Full Project](https://tamiyaindata.weebly.com/diabetes-readmission-analysis.html)
