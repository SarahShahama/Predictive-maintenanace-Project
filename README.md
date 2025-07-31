# 🛠️ Predictive Maintenance for Industrial Equipment

This project aims to predict machine failures using supervised machine learning models based on sensor data from industrial equipment. The goal is to help manufacturers take preventive actions before actual breakdowns occur.

---

## 📂 Project Structure
📁 predictive-maintenance-project/
│
├── ai4i2020.csv # Original dataset
├── predictive_maintenance.ipynb # Main Python code with models
├── report.docx # Detailed project report
├── LICENSE # License file (CC BY-NC-ND 4.0)
└── README.md # This file

---

## 🔍 Business Problem

Predicting whether a machine will fail within a given timeframe using sensor data like temperature, torque, power, and rotational speed. This can prevent downtime, reduce maintenance costs, and improve productivity.

---

## 📊 Dataset Information

- 📁 File: `ai4i2020.csv`
- Rows: 10,000+
- Features include:
  - Air Temperature
  - Process Temperature
  - Rotational Speed
  - Torque
  - Tool Wear
  - Machine Failure
  - Failure Type

---

## 🤖 Models Used

We implemented and evaluated the following classification models:

### ✅ In-Depth Modeling:
- **Logistic Regression**  
  Interpretable model used for understanding relationships between features and failure prediction. Detailed evaluation performed.

- **Random Forest Classifier**  
  An ensemble model providing strong performance. Feature importance analysis and interpretability included.

### 🔍 Additional Models Evaluated (Comparison Only):
- **K-Nearest Neighbors (KNN)**
- **Support Vector Classifier (SVC)**
- **XGBoost (XGBClassifier)**

These models were evaluated on classification metrics such as Accuracy, Precision, Recall, F1 Score, and ROC-AUC. Observations from these comparisons helped justify the selection of Logistic Regression and Random Forest as the final models.


## 🧪 Key Techniques & Tools

- **Train-Test Split**
- **Permutation Feature Importance**
- **GridSearchCV** for hyperparameter tuning
- **KDE Plots** for distribution visualization
- **Confusion Matrix, ROC Curve, Precision-Recall Curve**
- **Classification Reports** for each model
- **Correlation Heatmap** for exploratory data analysis

---

## 📈 Evaluation Metrics

- Accuracy
- Precision, Recall, F1 Score
- ROC Curve and AUC
- Confusion Matrix
- Feature Importance Score

---

## 🧠 Key Features

✅ **Custom Threshold-Based Prediction**  
Implemented custom decision thresholds (0.5 for Logistic Regression, 0.6 for Random Forest) to classify machines as likely to fail or not. This reflects real-world flexibility in defining failure risk levels based on operational needs.

✅ **Model Comparison & Insights**  
Compared five classifiers (Logistic Regression, Random Forest, KNN, SVC, XGBoost) and selected the best-performing ones based on evaluation metrics and business relevance.

✅ **Permutation-Based Feature Importance**  
Used permutation importance to identify the most influential features affecting machine failure.

✅ **Hyperparameter Optimization**  
Tuned models using GridSearchCV for improved performance.

✅ **Clean Visualizations**  
Plotted KDE distributions, ROC curves, confusion matrices, and heatmaps to support analysis and interpretation.

✅ **Well-Structured Report**  
Detailed Word document summarizing methods, results, insights, and business implications.
  

---

## 🛡️ License

This project is licensed under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License**.

🔗 [View License Details](https://creativecommons.org/licenses/by-nc-nd/4.0/)

Please do not reuse, modify, or redistribute this work without explicit permission.

---

## 🙋‍♀️ Author

**Sara Shahama**  
Aspiring Data Scientist  
📧 Contact: [sarashhama7@gmail.com]

---

## 📌 Note

This project was created as part of a Python internship and is intended for educational and portfolio purposes only.

