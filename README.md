# Intrusion-Detection-System-ML
"Machine Learning based IDS using NSL-KDD dataset"
# Machine Learning-based Intrusion Detection System (IDS)

## Project Overview
This project implements a **Machine Learning-based Intrusion Detection System (IDS)** using the **NSL-KDD dataset**.  
It detects malicious network traffic and anomalies with high accuracy, combining **cybersecurity concepts** with **AI/ML techniques**. 

## Key Features / Highlights

- Developed an IDS using NSL-KDD dataset, achieving **99.6% accuracy**, **F1-score 0.996**, and **ROC-AUC 0.999** in detecting malicious traffic.  
- Implemented cybersecurity techniques for anomaly and attack detection, leveraging **Random Forest Classifier** with **SMOTE** to handle class imbalance.  
- Built **data preprocessing pipelines** (feature encoding, scaling, balancing) to enhance detection accuracy for **DoS, Probe, U2R, and R2L attack patterns**.  
- Applied **threat analysis** and **network traffic monitoring concepts** to detect suspicious behavior in real-time.  
- Created visualizations (**confusion matrix, ROC curve, feature importance**) for interpretability and integrated a **deployable ML pipeline (joblib)**.  
- Showcased **cross-domain expertise** by combining cybersecurity fundamentals (network protocols, attack categories) with AI/ML techniques for advanced threat detection.

---

##  Tech Stack
- Python 3
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn
- Google Colab (for training)

---

## Files
- `IDS_NSLKDD.ipynb` → Jupyter Notebook with full code  
- `plots/` → Visualizations (confusion matrix, ROC curve)  
- `requirements.txt` → List of dependencies  

---

## Results
- **Accuracy:** 99.6%  
- **F1-score:** 0.996  
- **ROC-AUC:** 0.999  


---

## How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/Varshavsajjanavar/Intrusion-Detection-System-ML.git
   cd Intrusion-Detection-System-ML
2. Install Dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the notebook:
-  Open IDS_NSLKDD.ipynb in Jupyter Notebook or Google Colab.
-  Run all cells to train and evaluate the IDS.


