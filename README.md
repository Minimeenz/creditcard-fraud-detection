# Credit Card Fraud Detection (Supervised Learning)

This repository contains Deliverable 1 (Jupyter Notebook & PDF report) for a supervised learning project on **credit card fraud detection**.

## 📌 Project Overview
- **Goal:** Build a classifier to detect fraudulent credit-card transactions.
- **Dataset:** Kaggle Credit Card Fraud Detection (Class: `1`=Fraud, `0`=Legit)
- **Challenge:** Highly imbalanced data; focus on Precision/Recall and ROC-AUC over accuracy.

## 📁 Repository Structure
```
.
├── data/                      # (empty) Do NOT commit raw data here
├── notebooks/
│   └── Credit_Card_Fraud_Detection.ipynb
├── reports/
│   └── Credit_Card_Fraud_Detection_Report.pdf
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```
> Note: Please **do not upload raw data** or videos to this repository. Share data via Kaggle (or similar) and videos via YouTube/Vimeo, then link them here.

## 🧪 How to Run
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

## 📊 Deliverables
- **Deliverable 1:** Notebook and PDF report (see `notebooks/` and `reports/`).
- **Deliverable 2:** Presentation video (upload to YouTube; add the link below).
- **Deliverable 3:** This GitHub repository (public).

## 🔗 Links
- **Dataset (Kaggle):** https://www.kaggle.com/mlg-ulb/creditcardfraud
- **Presentation Video:** <ADD_YOUTUBE_LINK_HERE>
- **Notebook (nbviewer):** <ADD_NBV_LINK_HERE>

## 📝 Citation
If you use the Kaggle dataset, please cite the original authors (see Kaggle page for citation guidelines).

## 📄 License
See `LICENSE` for more details.

---

*Last updated:* 2025-10-17