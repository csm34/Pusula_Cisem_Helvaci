# Pusula_Cisem_Helvaci

# Side Effect Data Analysis and Prediction

## Overview
This project involves analyzing a dataset related to drug side effects. The goal is to understand the patterns of side effects reported by users.

## Dataset
The dataset used in this project is named `side_effect_data 1.xlsx` and contains 2357 entries with the following features:

- **Kullanici_id**: User ID
- **Cinsiyet**: Gender of the user (Male/Female)
- **Dogum_Tarihi**: Date of birth
- **Uyruk**: Nationality
- **Il**: Province
- **Ilac_Adi**: Name of the medication
- **Ilac_Baslangic_Tarihi**: Start date of the medication
- **Ilac_Bitis_Tarihi**: End date of the medication
- **Yan_Etki**: Reported side effect
- **Yan_Etki_Bildirim_Tarihi**: Date of side effect reporting
- **Alerjilerim**: User's allergies
- **Kronik Hastaliklarim**: Chronic diseases of the user
- **Baba Kronik Hastaliklari**: Father's chronic diseases
- **Anne Kronik Hastaliklari**: Mother's chronic diseases
- **Kiz Kardes Kronik Hastaliklari**: Sister's chronic diseases
- **Erkek Kardes Kronik Hastaliklari**: Brother's chronic diseases
- **Kan Grubu**: Blood type
- **Kilo**: Weight
- **Boy**: Height

## Data Exploration
- Missing values were identified and visualized using heatmaps.
- Various statistical analyses were performed to describe the dataset.
- Visualizations were created to explore the distribution of gender, blood type, age, and side effects.

## Data Preprocessing
- Missing values were handled using imputation techniques.
- Categorical variables were encoded using label encoding and multi-label binarization.
- Date columns were transformed into numerical features (year, month, day).
- Numerical features were standardized using `StandardScaler`.
