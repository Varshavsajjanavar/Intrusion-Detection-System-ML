# Intrusion-Detection-System-ML
"Machine Learning based IDS using NSL-KDD dataset"
# Machine Learning-based Intrusion Detection System (IDS)

## Project Overview
This project implements a **Machine Learning Intrusion Detection System (IDS)** using the **NSL-KDD dataset**.  
It detects malicious network traffic and anomalies with very high accuracy.  

The IDS uses **Random Forest Classifier** with **SMOTE** to handle class imbalance, achieving near-perfect results.

---

## 🛠️ Tech Stack
- Python 3
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn
- Google Colab (for training)

---

## Files
- `IDS_NSLKDD.ipynb` → Jupyter Notebook with full code  
- `IDS_model.pkl` → Saved ML model for reuse  
- `plots/` → Visualizations (confusion matrix, ROC curve)  
- `requirements.txt` → List of dependencies  

---

## Results
- **Accuracy:** 99.6%  
- **F1-score:** 0.996  
- **ROC-AUC:** 0.999  

### Confusion Matrix
![Confusion Matrix](plots/confusion_matrix.png)

### ROC Curve
![ROC Curve](plots/roc_curve.png)

---

## How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/Varshavsajjanavar/Intrusion-Detection-System-ML.git
   cd Intrusion-Detection-System-ML

