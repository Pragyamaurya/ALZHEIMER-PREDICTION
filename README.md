# Alzheimer's Disease Diagnosis Dataset

This dataset contains information about 2,149 patients, with 35 features, used for predicting the likelihood of Alzheimer's disease. The target variable is Diagnosis, where 0 indicates no Alzheimer's and 1 indicates the presence of Alzheimer's disease.

Dataset Overview
Total Records: 2,149 patients
Total Features (Columns): 35
Missing Values: None (No missing values in any column)
Target Variable:
Diagnosis:

0 = No Alzheimer's

1 = Alzheimer's

Feature Descriptions
Demographics & Lifestyle
PatientID: Unique patient ID

Age: Patient's age (60–90)

Gender:

0 = Female

1 = Male

Ethnicity: Coded as integers (0–3)

EducationLevel: Ordinal value (0 = low to 3 = high)

BMI: Body Mass Index

Smoking: Indicator of smoking status

AlcoholConsumption: Indicator of alcohol consumption

PhysicalActivity: Indicator of physical activity level

DietQuality: Indicator of diet quality

SleepQuality: Indicator of sleep quality

Medical History
FamilyHistoryAlzheimers: Binary indicator (0 = No, 1 = Yes)

CardiovascularDisease: Binary indicator (0 = No, 1 = Yes)

Diabetes: Binary indicator (0 = No, 1 = Yes)

Depression: Binary indicator (0 = No, 1 = Yes)

HeadInjury: Binary indicator (0 = No, 1 = Yes)

Hypertension: Binary indicator (0 = No, 1 = Yes)

SystolicBP: Systolic blood pressure

DiastolicBP: Diastolic blood pressure

CholesterolTotal: Total cholesterol levels

CholesterolLDL: Low-density lipoprotein (LDL) cholesterol levels

CholesterolHDL: High-density lipoprotein (HDL) cholesterol levels

CholesterolTriglycerides: Triglyceride levels

Cognitive & Functional Scores
MMSE: Mini Mental State Examination score (used for cognitive impairment assessment)

FunctionalAssessment: Functional assessment score

ADL: Activity of Daily Living score (measuring daily functional abilities)

MemoryComplaints: Binary indicator of memory complaints

BehavioralProblems: Binary indicator of behavioral problems

Confusion: Binary indicator of confusion

Disorientation: Binary indicator of disorientation

PersonalityChanges: Binary indicator of personality changes

DifficultyCompletingTasks: Binary indicator of difficulty in completing tasks

Forgetfulness: Binary indicator of forgetfulness

Others
DoctorInCharge: Same value for all patients ("XXXConfid")

Usage
This dataset is useful for building machine learning models aimed at predicting Alzheimer's disease based on a combination of demographic, lifestyle, medical history, and cognitive assessments.
