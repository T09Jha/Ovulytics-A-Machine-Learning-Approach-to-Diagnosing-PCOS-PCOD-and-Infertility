# Ovulytics-A-Machine-Learning-Approach-to-Diagnosing-PCOS-PCOD-and-Infertility
Ovulytics is a machine learning-based project aimed at diagnosing Polycystic Ovary Syndrome (PCOS), Polycystic Ovarian Disease (PCOD), and PCOS with infertility. This project utilizes three machine learning algorithms to predict the likelihood of these conditions based on clinical and biochemical data. 

___________________________________________________________________________________________

## Datasets📊
### PCOS Prediction Dataset
**Source:** Kaggle
**Size:** 541 records (177 PCOS cases, 364 healthy individuals)
**Features:**
- Clinical markers: FSH, LH, Hb, AMH
- Physical metrics: weight, height, waist-to-hip ratio
- Feature types: Combination of numerical and categorical
### PCOD Prediction Dataset
**Source:** Kaggle
**Size:** 162 records
**Features:**
- Menstrual and reproductive health indicators:
- Bleeding patterns
- Cycle length
- Ovulation day
- BMI
### PCOS with Infertility Dataset
**Source:** Private dataset
**Size:** 541 records, 6 features
**Features:**
- Key infertility indicators:
- Beta-HCG (I and II)
- AMH levels

___________________________________________________________________________________________

## Data Preprocessing⚙️
To ensure high-quality and balanced input for model training, the following preprocessing techniques were applied:

**Outlier Detection and Removal:**
- Interquartile Range (IQR)
- Z-scores

**Data Standardization:**
- Scaled features to standard normal distribution for better model performance.
- Handling Class Imbalance:
- Used SMOTE (Synthetic Minority Over-sampling Technique) to address imbalance between positive and negative cases.

**Feature Selection:**
- Implemented Recursive Feature Elimination with Cross-Validation (RFECV).
- Key selected features include:
- Age
- Cycle length
- Hormonal levels

___________________________________________________________________________________________

## Machine Learning Models🤖
Three machine learning models were used to predict PCOS, PCOD, and infertility:
- Logistic Regression
- XGBoost
- Random Forest (Best Performing Model)

___________________________________________________________________________________________

## Model Performance🚀
### PCOS Prediction
- Best Model: Random Forest
- Accuracy: 92%
- Key Features: AMH, LH, FSH, waist-to-hip ratio
### PCOD Prediction
- Best Model: Random Forest
- Accuracy: 97%
- Key Features: Cycle length, Ovulation day, BMI, Bleeding patterns
### Infertility Prediction
- Best Model: Random Forest
- Accuracy: 91%
- Key Features: Beta-HCG levels (I & II), AMH

**Evaluation Metrics:**
Accuracy, Precision, Recall, F1-score

___________________________________________________________________________________________

## Results📈
The results demonstrate that machine learning models, particularly Random Forest, can effectively provide probabilistic predictions for menstrual disorders. These insights can assist medical professionals in early and accurate diagnosis of:

PCOS
PCOD
Infertility

![WhatsApp Image 2024-11-19 at 22 21 48_50f61705](https://github.com/user-attachments/assets/fe21f603-3f08-467f-a2ef-9d89aea9be33)

![WhatsApp Image 2024-11-19 at 22 33 36_d5077b3d](https://github.com/user-attachments/assets/63e60d9d-0ebc-4cd3-bb95-8ddecbcd1789)

![WhatsApp Image 2024-11-19 at 22 36 20_9e2f203a](https://github.com/user-attachments/assets/05544e7d-422b-4241-9168-5b5715959863)

__________________________________________________________________________________________

## Use Case👩‍⚕️
This tool provides valuable insights for:
- Gynecologists to diagnose menstrual disorders.
- Healthcare professionals to predict infertility likelihood in PCOS patients.
- Early intervention strategies to manage reproductive health.
