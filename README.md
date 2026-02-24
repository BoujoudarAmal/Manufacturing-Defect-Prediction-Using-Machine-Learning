# 🏭 Manufacturing Defect Prediction Using Machine Learning

## 📌 Project Overview

This project focuses on predicting manufacturing defects using supervised machine learning techniques.  
The objective is to analyze industrial production data and develop predictive models capable of identifying defective products in order to improve quality control and reduce operational losses.

By comparing multiple classification algorithms, this project demonstrates how data-driven approaches can enhance industrial decision-making and production optimization.

---

## 🎯 Problem Statement

In manufacturing environments, defective products lead to:

- Increased operational costs  
- Material waste  
- Reduced productivity  
- Lower customer satisfaction  

Early and accurate defect prediction is essential for maintaining high production standards.  
The main challenge is handling complex process variables while achieving balanced model performance.

---

## 📊 Dataset Description

The dataset contains production measurements collected during the manufacturing process.

It includes:

- Multiple process-related features (e.g., temperature, pressure, operational parameters)  
- A binary target variable:
  - `0` → Non-defective product  
  - `1` → Defective product  

The dataset reflects diverse industrial production scenarios, enabling robust model training and evaluation.

---

## ⚙️ Methodology

### 1️⃣ Data Preprocessing
- Data cleaning and preparation  
- Feature analysis  
- Train-test split  
- Normalization (when required)  

### 2️⃣ Model Implementation

Five machine learning classification models were developed and compared:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- k-Nearest Neighbors (KNN)  

### 3️⃣ Model Evaluation

Models were evaluated using:

- Accuracy  
- Precision  
- Recall  
- Confusion Matrix  
- Decision threshold analysis  

Special attention was given to balancing false positives and false negatives, which is critical in industrial applications.

---

## 📈 Results & Key Insights

- Model performance varied depending on defect detection sensitivity.  
- Some models minimized false positives, reducing unnecessary production interruptions.  
- Others improved recall, increasing defect detection capability.  
- Temperature and pressure-related variables were among the most influential predictors.  
- The optimal model depends on industrial priorities (cost reduction vs. detection sensitivity).  

---

## 🛠 Technologies & Tools

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## 📂 Project Structure

```
├── manufacturing_defect_dataset.csv
├── Analyse_Defauts_Manufacturiers.ipynb
├── Presentation_Projet.pptx
├── Rapport_Statistique.pdf
└── README.md
```

---

## 🚀 Industrial Impact

This project demonstrates how machine learning can:

✔ Improve quality control systems  
✔ Reduce manufacturing defects  
✔ Support data-driven production decisions  
✔ Enhance industrial productivity  

---

## 🔮 Future Improvements

- Hyperparameter tuning optimization  
- Cross-validation for improved robustness  
- Advanced ensemble models  
- Real-time deployment dashboard  

---

## 👩‍💻 Author

**Amal Boujoudar**  
Industrial Data Analysis & Machine Learning Enthusiast
