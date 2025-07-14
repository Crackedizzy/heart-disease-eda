# Heart Disease EDA

This project applies exploratory data analysis (EDA) and logistic regression modeling to predict heart disease risk using patient data. The project was completed as part of an academic Big Data module and uses a dataset sourced from Kaggle.

## 📊 Overview

Cardiovascular disease remains a leading global health challenge. This project explores how patient health indicators such as age, cholesterol, blood pressure, and lifestyle factors relate to the presence of heart disease.

Using Python libraries such as pandas, seaborn, and scikit-learn, this study:
- Preprocesses raw healthcare data
- Identifies patterns through EDA
- Trains a Logistic Regression model for classification
- Evaluates performance using accuracy, precision, recall, and F1-score

## 📁 Project Structure

```heart-disease-eda/
├── EDA.ipynb
├── Report.docx
├── README.md
├── data/
│   └── heart.csv
└── images/
    ├── exported charts from notebook
```

## 📚 Dataset

- Source: [Kaggle - Heart Disease Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- 918 samples
- Binary classification: `HeartDisease` (0 = No, 1 = Yes)

## ⚙️ Technologies Used

- Python 3
- Jupyter Notebook
- pandas, numpy
- seaborn, matplotlib
- scikit-learn

## ✅ Model Performance

| Metric     | Value  |
|------------|--------|
| Accuracy   | 84%    |
| Precision  | 0.90   |
| Recall     | 0.84   |
| F1-Score   | 0.87   |

The model used label encoding for categorical features, median imputation for invalid cholesterol and Oldpeak values, and feature scaling using StandardScaler.

## 📈 Key Insights

- Most patients with asymptomatic chest pain had heart disease.
- Cholesterol values of zero were biologically invalid and corrected.
- Elevated age and resting blood pressure were strongly associated with heart disease.
- Exercise-induced angina and ST slope features showed high predictive power.

## 🧠 Learning Outcome

This project demonstrates how EDA and simple machine learning models can provide meaningful insight into cardiovascular health risks using structured datasets. It showcases the value of data preprocessing, visualization, and model evaluation in healthcare analytics.

## 📜 References

All references used in the academic report are listed in `Report.docx`.

---
