# 🫀 Heart Failure Prediction Project  
### Predicting Risk Using Machine Learning Models   
**Languages:** Python | 🇬🇧 English & 🇸🇦 Arabic Documentation  

---

## Project Overview  
This project aims to predict the likelihood of heart failure using clinical data and machine learning models. It includes data exploration, preprocessing, modeling, and evaluation steps. The goal is to build reproducible, modular code that can be used for educational and diagnostic support purposes.

---

## Dataset  
**Source:** Heart Failure Prediction Dataset  
**Features:** Includes patient metrics such as age, blood pressure, cholesterol, and more.  
**Target:** Binary classification — risk of heart failure (Yes/No)

---

## Workflow Summary  
1. **Data Exploration:**  
   - Checked for missing values, data types, and basic statistics  
   - Visualized distributions and correlations  

2. **Data Analysis:**  
   - Plotted histograms, boxplots, and heatmaps  
   - Identified key features influencing heart failure  

3. **Data Transformation:**  
   - Scaled numerical features  
   - Encoded categorical variables  
   - Handled outliers and balanced the dataset  

4. **Modeling & Evaluation:**  
   Applied four classification models and compared performance:

| Model                  | Accuracy | Precision | Recall | F1 Score |
|------------------------|----------|-----------|--------|----------|
| XGBClassifier          | 0.8913   | 0.9100    | 0.8922 | 0.9010   |
| SVC                    | 0.8804   | 0.8846    | 0.9020 | 0.8932   |
| RandomForestClassifier | 0.9076   | 0.9126    | 0.9216 | 0.9171   |
| KNeighborsClassifier   | 0.8967   | 0.9029    | 0.9118 | 0.9073   |

---
##Visualizations
### Feature Distributions
![Age Histogram](https://github.com/Esraa-MOhamed7/Heart-Failure-Prediction/blob/main/Feature%20distributions.png)

### Feature Correlation
![Correlation Heatmap](charts/correlation_heatmap.png)


