Titanic Survival Prediction

**PS26 - DSC01 Machine Learning | Submission 1**

A supervised machine learning project that predicts whether a Titanic passenger survived, using Logistic Regression, Decision Tree, and Random Forest classifiers.

---

## Project Overview

| Detail | Info |
|---|---|
| **Task** | Binary Classification |
| **Target Variable** | `Survived` (0 = No, 1 = Yes) |
| **Dataset** | Titanic - Machine Learning from Disaster |
| **Dataset Source** | https://www.kaggle.com/c/titanic/data |
| **Dataset Rows** | 891 |
| **Dataset Columns** | 12 |

---

## Research Questions

1. Does passenger class (1st, 2nd, 3rd) affect survival rate?
2. Do female passengers have a higher survival rate than male passengers?
3. How does age influence the likelihood of survival?
4. Does the number of family members aboard affect survival?
5. Which features are the most important predictors of survival?
6. Which ML model achieves the highest accuracy?
7. How does fare paid correlate with survival?

---

## Models Used

| Model | Description |
|---|---|
| Logistic Regression | Simple baseline classifier |
| Decision Tree | Tree-based split model |
| Random Forest | Ensemble of decision trees |

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Repository Structure

```
titanic-survival-prediction/
│
├── titanic_survival_prediction.ipynb   ← Main Jupyter Notebook (with outputs)
├── README.md                           ← This file
├── requirements.txt                    ← Required Python libraries
├── Titanic Proposal.docx        
```

---

## How to Run the Code

### Option 1: Google Colab (Easiest — No Installation Needed)
1. Open [Google Colab](https://colab.research.google.com/)
2. Click **File → Upload Notebook**
3. Upload `titanic_survival_prediction.ipynb`
4. Click **Runtime → Run All**

### Option 2: Run Locally

**Step 1: Clone this repository**
```bash
git clone https://github.com/YOUR_USERNAME/titanic-survival-prediction.git
cd titanic-survival-prediction
```

**Step 2: Install dependencies**
```bash
pip install -r requirements.txt
```

**Step 3: Launch Jupyter Notebook**
```bash
jupyter notebook titanic_survival_prediction.ipynb
```

**Step 4: Run all cells**
- Click **Kernel → Restart & Run All**

> **Note:** The dataset is loaded automatically from a public URL inside the notebook. No manual download needed.

---

## Requirements

See `requirements.txt` for full list. Main libraries:

- `pandas` — data manipulation
- `numpy` — numerical operations
- `matplotlib` & `seaborn` — visualizations
- `scikit-learn` — machine learning models

---

## Results Summary

| Model | Accuracy |
|---|---|
| Logistic Regression | ~80% |
| Decision Tree | ~79% |
| Random Forest | ~82% |

*(Exact values visible in the executed notebook)*

---

## Dataset Link

Original dataset: **https://www.kaggle.com/c/titanic/data**

Direct CSV (used in notebook): `https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv`

---

## Course Info

**Course:** PS26 - DSC01 Machine Learning  
**Instructor:** Prof. Raja Hashim Ali  
**Submission:** Submission 1 — Proposal, Code, and GitHub Repository  
**Due Date:** 5 May 2026
