# 🧠 Early Parkinson’s Disease Detection Using Voice Analysis

## 📌 Overview

This project focuses on the early detection of Parkinson’s Disease (PD) using machine learning techniques applied to biomedical voice measurements. Parkinson’s Disease is a progressive neurological disorder that affects movement, coordination, and speech. Since speech abnormalities appear in early stages, voice analysis provides a non-invasive and cost-effective diagnostic approach. 

The system analyzes voice features such as jitter, shimmer, pitch, and harmonicity to classify individuals as healthy or affected by Parkinson’s disease.

---

## 🎯 Objectives

* Study the impact of Parkinson’s Disease on speech patterns
* Use biomedical voice features for prediction
* Compare multiple machine learning models
* Develop an accurate and reliable prediction system
* Enable low-cost and non-invasive diagnosis

---

## 📊 Dataset

* Source: UCI / Kaggle Parkinson’s Dataset
* Total Samples: 195
* Parkinson’s Cases: 147
* Healthy Cases: 48
* Features: 23 biomedical voice attributes

---

## ⚙️ Methodology

The project follows a complete machine learning pipeline:

1. Data Collection
2. Data Preprocessing

   * Removing irrelevant columns
   * Handling duplicates and missing values
   * Feature scaling
3. Exploratory Data Analysis (EDA)
4. Feature Selection (SelectKBest)
5. Data Balancing (Borderline-SMOTE)
6. Train-Test Split (80:20)
7. Model Training
8. Performance Evaluation

---

## 🤖 Machine Learning Models Used

* Decision Tree
* Random Forest
* Logistic Regression
* Support Vector Machine (SVM)
* XGBoost
* Extra Trees Classifier
* Stacking Classifier

---

## 📈 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Decision Tree       | 96.61%   |
| Random Forest       | 93.22%   |
| Logistic Regression | 86.44%   |
| SVM                 | 96.61%   |
| XGBoost             | 96.61%   |
| Stacking            | 98.31%   |
| Extra Trees         | 98.31%   |

👉 Ensemble models (Stacking & Extra Trees) achieved the best performance. 

---

## 🏆 Best Model

**Extra Trees Classifier**

* Accuracy: ~98.30%
* High precision and recall
* Strong generalization
* Less overfitting

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib, Seaborn
* Imbalanced-learn (BorderlineSMOTE)

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Upload dataset (if required)
3. Run all cells sequentially
4. Model will train and generate results

---

## 📂 Project Structure

```
parkinsons-detection-ml/
│
├── code/
│   └── parkinsons_detection.ipynb
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pptx
│
└── README.md
```

---

## 🌍 Applications

* Early disease screening
* Telemedicine systems
* Healthcare decision support
* Remote patient monitoring

---

## 🔮 Future Scope

* Use larger real-world datasets
* Deploy as web/mobile application
* Apply deep learning (CNN, LSTM)
* Integrate wearable sensor data
* Explainable AI (SHAP, LIME)

---

## 👨‍💻 Authors

* Sarthak Gupta (23U02077)
* Raj Rai (23U02113)

Supervisor: Dr. Amit Kumar Nandanwar

---

## ⚠️ Note

If you use this code or project, please make sure to give proper credit to the authors.
