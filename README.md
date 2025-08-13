# 🩺 Kidney Disease Detection using Machine Learning with Explainable AI (XAI)

This project focuses on detecting **kidney disease** using machine learning techniques, enhanced with **Explainable AI (XAI)** to make model predictions interpretable and transparent.  
It is designed to assist healthcare professionals in early detection and decision-making.

## 📂 Project Structure
1. **Kidney Disease Detection using ML with XAI.ipynb** → Main Jupyter notebook containing data preprocessing, model training, evaluation, and explainability.
2. **kidney_disease.csv** → Dataset containing patient health records and features related to kidney health.

## 🎯 Objective
1. Build a **predictive model** to classify whether a patient has kidney disease.
2. Use **Explainable AI** (e.g., SHAP, LIME) to interpret model decisions.
3. Provide **actionable insights** to support medical diagnosis.
4. Ensure transparency and trustworthiness in AI-powered predictions.

## 🛠️ Technologies Used
- **Python** (pandas, numpy, scikit-learn, matplotlib, seaborn)
- **Machine Learning** algorithms (Random Forest, Logistic Regression, etc.)
- **Explainable AI** libraries (SHAP, LIME)
- **Jupyter Notebook**

## 📊 Dataset Overview
The dataset contains medical parameters such as:
- Age, Blood Pressure, Specific Gravity
- Albumin, Sugar, Red Blood Cells, Pus Cell
- Serum Creatinine, Sodium, Potassium
- And other clinical measurements

**Target Variable** → `classification` (CKD / Not CKD)

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/spandanmohanty87/Kidney_Disease_Detection_Model.git
   ```
2. Navigate into the project folder:
   ```bash
   cd Kidney_Disease_Detection_Model

   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook "Kidney Disease Detection using ML with XAI.ipynb"
   ```

## 📌 Features
- End-to-end ML pipeline: data cleaning → feature engineering → model training → evaluation
- Model performance metrics (accuracy, precision, recall, F1-score)
- Explainable AI visualizations to understand predictions
- User-friendly and adaptable to new datasets

## 🧠 Example Use Case
Doctors can input patient health data into the model to predict kidney disease risk, and see **which features influenced the prediction**.

## 📜 License
This project is licensed under the MIT License.

---
**Author:** Spandan Mohanty
