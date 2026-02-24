# Manufacturing-Defect-Prediction-Using-Machine-Learning
📌 Project Overview

This project focuses on predicting manufacturing defects using supervised machine learning models.
The goal is to leverage industrial production data to build predictive systems capable of identifying defective products, improving quality control, and reducing operational losses.

By applying multiple classification algorithms, this project evaluates model performance and provides actionable insights for industrial process optimization.

🎯 Problem Statement

Manufacturing industries often face production losses due to defective items.
Early detection of defects can:

Reduce waste and operational costs

Improve product quality

Enhance customer satisfaction

Support data-driven industrial decision-making

The challenge lies in handling complex production variables while maintaining high prediction accuracy and balanced model performance.

📊 Dataset Description

The dataset contains industrial production measurements collected during the manufacturing process.

It includes:

Multiple process-related features (e.g., temperature, pressure, operational parameters)

A binary target variable:

0 → Non-defective product

1 → Defective product

The dataset represents diverse production scenarios, making it suitable for robust model training and evaluation.

⚙️ Methodology
1️⃣ Data Preprocessing

Data cleaning

Feature analysis

Train-test split

Normalization (when required)

2️⃣ Model Implementation

Five classification models were trained and evaluated:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

k-Nearest Neighbors (KNN)

3️⃣ Model Evaluation

Models were compared using:

Accuracy

Precision

Recall

Confusion Matrix

Probability-based decision threshold analysis

Special attention was given to the trade-off between false positives and false negatives, which is critical in industrial environments.

📈 Results & Key Insights

Model performance varied depending on defect detection sensitivity.

Some models minimized false positives, reducing unnecessary production stops.

Others improved recall, increasing defect detection capability.

Temperature and pressure-related variables were among the most influential predictors.

The optimal model choice depends on whether the priority is cost reduction or defect detection accuracy.

🛠 Technologies & Tools

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Google Colab

📂 Project Structure
├── manufacturing_defect_dataset.csv
├── Analyse_Defauts_Manufacturiers.ipynb
├── Presentation_Projet.pptx
├── Rapport_Statistique.pdf
└── README.md
🚀 Industrial Impact

This project demonstrates how machine learning can:

✔ Improve quality control systems
✔ Reduce defect rates
✔ Support real-time production monitoring
✔ Enable data-driven manufacturing optimization

🔮 Future Improvements

Hyperparameter tuning optimization

Cross-validation for improved robustness

Implementation of advanced ensemble methods

Deployment as a real-time monitoring dashboard

👩‍💻 Author

Amal Boujoudar
Industrial Data Analysis & Machine Learning Enthusiast
