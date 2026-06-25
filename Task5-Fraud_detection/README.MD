# Credit Card Fraud Detection
### Data Analytics Internship — Oasis Infobyte | Project 7 (Level 2)

---

## Overview

Financial fraud costs the global economy billions every year.
This project builds a machine learning pipeline to automatically
detect fraudulent credit card transactions from a dataset of
284,807 real-world transactions — where only 0.17% are fraud.

The core challenge: **extreme class imbalance.**
A model that blindly predicts "normal" every time achieves
99.83% accuracy — yet catches zero fraud. This project solves that.

---

## Dataset

| Property | Detail |
|----------|--------|
| Source | Kaggle — ULB Credit Card Fraud Detection |
| Total transactions | 284,807 |
| Fraud cases | 492 (0.17%) |
| Features | 30 (V1–V28 PCA-transformed + Time + Amount) |
| Missing values | None |

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | Visualization |
| Scikit-learn | ML model + evaluation |
| Google Colab | Development environment |

---

## Project Workflow

```
1. Load & Explore Data
      ↓
2. Analyze Class Imbalance
      ↓
3. Scale Features (Amount + Time)
      ↓
4. Train/Test Split (80/20, stratified)
      ↓
5. Train Logistic Regression Model
      ↓
6. Evaluate → Confusion Matrix + ROC-AUC Curve
```

---

## Results

| Metric | Score |
|--------|-------|
| ROC-AUC Score | **0.9573** |
| Baseline (random guess) | 0.5000 |
| Improvement over baseline | +45.73% |

The ROC curve rises steeply toward the top-left corner —
meaning the model catches most fraud cases early while
keeping false alarms minimal.

---

## Key Insights

- **AUC 0.9573** → model correctly ranks fraud above normal
  transactions 95.73% of the time
- Plain accuracy is misleading on imbalanced data —
  ROC-AUC is the correct metric for fraud detection
- Feature scaling of `Amount` and `Time` was critical
  for Logistic Regression to converge properly
- Even a simple linear model achieves near-excellent
  performance when features are prepared correctly

---

## How to Run

```bash
# 1. Clone this repository
git clone https://github.com/chavanraj9545-coder/oasis-infobyte-fraud-detection

# 2. Open fraud_detection.ipynb in Google Colab

# 3. Upload creditcard.csv from Kaggle

# 4. Run all cells top to bottom
```

---

## Author

**Pruthviraj Chavan**
Data Science Undergraduate — DY Patil Technical Campus (2023–2027)
- 📧 chavanraj9545@gmail.com

---

*Completed as part of the Oasis Infobyte Data Analytics Internship*
*Reference: OIB/J2/IP4257*
