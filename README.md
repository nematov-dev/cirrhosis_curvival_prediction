# 🏥 Cirrhosis Survival Prediction

Predict survival probabilities for patients with cirrhosis using machine learning. This project demonstrates **data preprocessing, modeling, and generating prediction submissions**.

---

## 📁 Project Files

- `cirrhosis-curvival-prediction.ipynb` – Main notebook including:
  - Data cleaning & preprocessing
  - Model training & cross-validation
  - Predictions generation
- `submission.csv` – Predicted probabilities for the test set

---

## 🎯 Goal

Predict probabilities for three survival outcomes:

| Column       | Description                  |
|--------------|------------------------------|
| `Status_C`   | Survival class C             |
| `Status_CL`  | Survival class CL            |
| `Status_D`   | Survival class D             |

---

## ⚡ Model Details

- **RandomForestClassifier**  
- Hyperparameter tuning using **GridSearchCV**  
- Cross-validation with **StratifiedKFold**  
- Best **log-loss score**: ~0.41  

---

## 📝 Notes

- Predictions are saved in `submission.csv`  
- Ensure your `test` dataset matches the training features for proper prediction  
- Probabilities are normalized for each class per row

---

## 📌 Highlights

- End-to-end ML workflow
- Clean handling of numeric & categorical features
- Ready-to-use predictions for submission
