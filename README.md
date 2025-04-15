# 🧠 Alzheimer's Disease Diagnosis using Machine Learning

This project applies machine learning models to predict **Alzheimer’s Disease** from clinical data. We used two datasets (merged) from the [OASIS repository](https://www.oasis-brains.org/), focusing on detecting dementia vs non-dementia cases using preprocessing, visualization, and classification models.

---

## 📁 Project Structure

- **Data Import & Cleaning**
- **EDA** (Gender, Age, Brain Volume, Education)
- **Handling Missing Values & Encoding**
- **Feature Selection (SelectKBest)**
- **Class Imbalance Handling (SMOTE)**
- **Train-Test Split & Scaling**
- **Machine Learning Models:**
  - Gaussian Naive Bayes (GNB)
  - Decision Tree (DT)
  - Random Forest (RF)
  - Gradient Boosting (GB)
  - XGBoost (XGB)
  - Voting Classifier (Ensemble)
- **Model Generalization Analysis**

---

## 📊 Dataset Summary

- Dataset: OASIS MRI Clinical Data
- Target: `Group` (0 = Non-Demented, 1 = Demented)
- Features: Age, Gender, Brain Volume (nWBV), SES, Education, etc.
- Class Imbalance: Resolved using SMOTE

---

## 📈 Key Results

| Model              | Accuracy (Approx.) |
|--------------------|--------------------|
| Gaussian NB        | Moderate           |
| Decision Tree      | High               |
| Random Forest      | **Highest**        |
| Gradient Boosting  | High               |
| XGBoost            | High               |
| Voting Classifier  | **Best Generalization** |

---

## 🖥️ How to Run

You can run this notebook in Google Colab:

👉 [Open in Colab](https://colab.research.google.com/)  
→ Upload the notebook: `Alzheimers_Disease_Diagnosis_ML.ipynb`

---

## 📌 Conclusion

This project demonstrates how traditional ML pipelines, combined with **oversampling and ensemble methods**, can yield strong predictive results in medical datasets. The Voting Classifier offered robust generalization on imbalanced clinical data.

---

## 📎 Author

- **Name:** Basit Ibrahim  
- **GitHub:** [github.com/yourusername](https://github.com/yourusername)  
- **Education:** MS Artificial Intelligence  
- **Tools Used:** Python, Pandas, Matplotlib, Scikit-learn, SMOTE, XGBoost

---

## 📚 License

This project is for educational and research purposes only.
