# Ovulytics-A-Machine-Learning-Approach-to-Diagnosing-PCOS-PCOD-and-Infertility
Ovulytics is a machine learning-based project aimed at diagnosing Polycystic Ovary Syndrome (PCOS), Polycystic Ovarian Disease (PCOD), and PCOS with infertility. This project utilizes three machine learning algorithms to predict the likelihood of these conditions based on clinical and biochemical data. 

In this project, three distinct datasets related to Polycystic Ovary Syndrome (PCOS), Polycystic Ovary Disease (PCOD), and PCOS with infertility were used to train machine learning models for precision diagnosis. These datasets contain comprehensive clinical and biochemical features, capturing the unique characteristics that are the symptoms of each condition.

The first dataset, sourced from Kaggle, focuses on detecting PCOS and includes data from 541 women, with 177 PCOS cases and 364 healthy individuals. It covers key clinical markers such as FSH, LH, Hb, and AMH, along with physical metrics like weight, height, and waist-to-hip ratio with values ranging from both categorical and numerical.

The second dataset, also from Kaggle, targets PCOD prediction. It includes 162 records and 12 features related to menstrual and reproductive health, with key variables like bleeding patterns, cycle length, ovulation day, and BMI.

The third dataset, which forecasts infertility chances among PCOS patients, contains 541 rows and 6 columns. It focuses on key infertility indicators like beta-HCG and AMH levels.

Various preprocessing techniques were applied to these datasets, including outlier detection using the Interquartile Range (IQR) and Z-scores, and data standardization. The imbalanced datasets were handled using SMOTE (Synthetic Minority Over-sampling Technique) to balance the classes. Feature selection was performed using Recursive Feature Elimination with Cross-Validation (RFECV), allowing models to select the most relevant features like age, cycle length, and hormonal levels.

Three machine learning models—Logistic Regression, XGBoost, and Random Forest—were used to predict the likelihood of PCOS, PCOD, and infertility. Random Forest outperformed other models, achieving the highest accuracy for PCOS (92%), PCOD (97%), and infertility prediction (91%).

Key performance metrics, including accuracy, precision, recall, and F1 scores, were used to evaluate the models, with Random Forest emerging as the most effective classifier for this dataset. The results demonstrate that machine learning can provide probabilistic predictions for menstrual disorders, assisting in more accurate and early diagnosis of PCOS, PCOD, and infertility.
