# Wine Quality Prediction
### Data Analytics Internship — Oasis Infobyte | Project 6 (Level 2)

---

## Overview

Can the chemistry of a wine predict whether it's good or not?

This project builds and compares three machine learning classifiers
on real red wine data to predict wine quality based on its chemical
properties — alcohol content, acidity, sulphates, pH, and more.

---

## Dataset

| Property | Detail |
|----------|--------|
| Source | UCI Machine Learning Repository — Red Wine Quality |
| File | `winequality-red.csv` |
| Total samples | 1,599 wines |
| Features | 11 chemical properties |
| Target | Quality score (3–8), binarized: Good (≥7) vs Not Good (<7) |

**Class distribution after binarization:**
- Not Good (0): 1,382 wines
- Good (1): 217 wines

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python 3 | Core language |
| Pandas & NumPy | Data loading and manipulation |
| Matplotlib & Seaborn | Visualization |
| Scikit-learn | ML models + evaluation |
| Google Colab | Development environment |

---

## Project Workflow

```
1. Load & Explore Dataset
        ↓
2. Visualize Quality Score Distribution
        ↓
3. Correlation Heatmap (feature analysis)
        ↓
4. Binarize Target Variable (Good vs Not Good)
        ↓
5. Feature Scaling (StandardScaler)
        ↓
6. Train/Test Split (80/20)
        ↓
7. Train 3 Models: Random Forest, SGD, SVC
        ↓
8. Compare Accuracy
```

---

## Results

| Model | Accuracy |
|-------|----------|
| **Random Forest** | **90.00%** ✅ Best |
| Support Vector Classifier | 87.50% |
| SGD Classifier | 85.31% |

Random Forest outperformed the others — its ensemble approach
handles the non-linear patterns in wine chemistry more effectively.

---

## Key Insights

- **Random Forest wins** at 90% accuracy — best for this dataset
- Feature scaling significantly improves SGD and SVC performance
- The dataset is imbalanced (only ~13.6% "Good" wines), which
  makes accuracy a useful but not complete metric
- Chemical features like alcohol content and sulphates show
  strong correlation with quality in the heatmap

---

## How to Run

```bash
# 1. Clone the repository
git clone https://github.com/chavanraj9545-coder/oasis-wine-quality

# 2. Open Wine_Quality_Prediction.ipynb in Google Colab

# 3. Upload winequality-red.csv from UCI or Kaggle

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
