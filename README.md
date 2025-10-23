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

##### Step 3: Data Types

##### Numerical columns: Age, TSH_Level, T3_Level, T4_Level, Nodule_Size

##### Categorical columns: Gender, Country, Ethnicity, Family_History, etc.

##### Step 4: Encoding & Cleaning

##### Converted categorical data into numerical form (if required for modeling).

##### Verified balanced distributions for key categorical fields

## Statistical Summary

##### Feature : Age	 Mean : 51.9	 Min : 15	 Max : 89	 Std : 21.6	 Insight : Majority middle-aged patients
##### Feature : TSH_Level	 Mean : 5.04	 Min : 0.10	 Max : 10.00	 Std : 2.86	 Insight : Normal average range
##### Feature : T3_Level	 Mean : 2.00	 Min : 0.50	 Max : 3.50	 Std : 0.86	 Insight : Normal thyroid hormone
##### Feature : T4_Level	 Mean : 8.24	 Min : 4.50	 Max : 12.00	 Std : 2.16	 Insight : Standard thyroid range
##### Feature : Nodule_Size	 Mean : 2.50	 Min : 0	 Max : 5	 Std : 1.44	 Insight : Small-to-medium nodules common

## Visual Summary
##### 1. Bar Plot
##### Insight : Both genders show higher frequency in Low Risk, but Medium/High Risk more common in females.

##### 2. Heatmap
##### Insight : Strong correlation observed between TSH, T3, and T4 levels, confirming hormonal interdependence.

##### 3. Line Plot
##### Insight : The Line Plot shows how one variable changes with respect to another — for example: Age vs T3_Level → helps see how thyroid hormone levels vary by age. Age vs Thyroid_Cancer_Risk → indicates trends or fluctuations in risk with age.

##### 4. Histogram Plot
##### Insight : Most patients fall in the 30–70 age range. TSH levels show moderate spread.

##### 5. Box Plot
##### Insight : Some outliers appear in hormone levels, possibly indicating abnormal thyroid function.

##### 6. Pair Plot
##### Insight : TSH, T4, and Nodule Size influence cancer risk; visible clustering across risk levels

##### 7. Pie Plot
##### Insight: ~76% Benign and ~24% Malignant — benign cases are dominant.
