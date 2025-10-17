# Credit Card Fraud Detection (Supervised Learning)

This repository contains a Jupyter Notebook file for a supervised learning project on credit card fraud detection. 

Project Overview
Goal: Build a classifier to detect fraudulent credit-card transactions.
Dataset:  Kaggle Credit Card Fraud Detection (Class: `1`=Fraud, `0`=Legit)
Challenge:  Highly imbalanced data; focus on Precision/Recall and ROC-AUC over accuracy.

 

How to Run
1. Clone the repo:
   ```bash
   git clone <YOUR_REPO_URL>.git
   cd creditcard-fraud-detection
   ```
2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   ```
3. Place `creditcard.csv` in the project root or `data/` (update the path in the notebook if needed).
4. Open and run the notebook:
   ```bash
   jupyter notebook notebooks/Credit_Card_Fraud_Detection.ipynb
   ```

 

Links
Dataset (Kaggle): https://www.kaggle.com/mlg-ulb/creditcardfraud


 Citation
If you use the Kaggle dataset, please cite the original authors (see Kaggle page for citation guidelines).

License
See `LICENSE` for more details.

---

Last updated:2025-10-17
