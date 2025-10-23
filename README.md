# Thyroid_Cancer_Risk

## Project Overview

##### The goal of this project is to analyze factors affecting thyroid cancer risk using a large dataset of patient records. By studying relationships between age, hormones (TSH, T3, T4), lifestyle factors, and diagnosis, we aim to uncover trends that can help in early detection and risk prediction.


## Dataset Information

##### Dataset Name: thyroid_cancer_risk_data.csv
##### Records: 212,691 patients
##### Columns: 17 features

##### Feature	Description
##### Patient_ID	Unique patient identifier
##### Age	Patient’s age
##### Gender	Male / Female
##### Country	Country of residence
##### Ethnicity	Patient ethnicity
##### Family_History	Family thyroid cancer history
##### Radiation_Exposure	Whether patient had prior radiation exposure
##### Iodine_Deficiency	Indicates deficiency of iodine
##### Smoking	Whether the patient smokes
##### Obesity	Whether the patient is obese
##### Diabetes	Indicates if diabetic
##### TSH_Level	Thyroid-Stimulating Hormone
##### T3_Level	Triiodothyronine hormone
##### T4_Level	Thyroxine hormone
##### Nodule_Size	Size of thyroid nodules
##### Thyroid_Cancer_Risk	Low / Medium / High risk
##### Diagnosis	Benign / Malignant outcome

 ## Data Preprocessing
 
 ##### 1: Load Data
 ##### import pandas as pd
 ##### df = pd.read_csv("thyroid_cancer_risk_data.csv")

##### Step 2: Data Inspection

##### Rows: 212,691

##### Columns: 17

##### No missing (null) values

##### No duplicate entries (df.duplicated().sum() == 0)

##### Memory usage: 27.6 MB

