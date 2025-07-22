# 🎗️ Breast Cancer Survival Prediction

## 📖 About
This project applies machine learning to predict breast cancer survival based on clinical and hormonal tumor features. It includes data preprocessing, statistical testing, feature importance analysis, and multiple classification models to enhance clinical decision-making.

---

## 📁 Files in the Repository
- `Breast_Cancer Project_KRC.ipynb` – Full Jupyter notebook analysis.
- `Breast_Cancer_KRC.csv` – Dataset used (from Kaggle).
- `Breast_Cancer Project_PPT_KRC.pdf` – Presentation summarizing the project.

---

## 🧪 Methodology
1. **Data Cleaning & Encoding**: Converted categorical values like stage, grade, and hormone status into numeric form.
2. **Statistical Testing**:
   - Shapiro-Wilk (normality)
   - Chi-Square & Kendall Tau (feature significance)
3. **Modeling**: Trained and evaluated:
   - Decision Tree
   - XGBoost
   - Random Forest
   - Logistic Regression
   - KNN
4. **Evaluation**: Accuracy, ROC-AUC, and classification reports compared across models.

---

## 🔍 Key Result
- **Best Model:** Logistic Regression
- **Accuracy:** ~84.6%
- **Key Features Influencing Survival**: Estrogen/Progesterone status, stage, nodal involvement

---

## ▶️ How to Run
1. Clone the repository:
```bash
git clone https://github.com/your-username/breast-cancer-survival-prediction.git
cd breast-cancer-survival-prediction

2.Open the notebook:
jupyter notebook "Breast_Cancer Project_KRC.ipynb"

3.Make sure to install required libraries:
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
