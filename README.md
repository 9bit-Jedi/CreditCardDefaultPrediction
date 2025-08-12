# Credit Card Behaviour Score Prediction
### Author

**Utsah** – Department of Chemical Engineering, IIT Roorkee  
Enrollment No.: 22112109  
Bhawan: Rajiv Bhawan

**🎉 Technopedia 2025 – Rajiv Bhawan Hackathon**

An intra-bhawan hackathon hosted by Rajiv Bhawan, IIT Roorkee, bringing together innovators to solve real-world problems through AI and data science. This project was developed as part of the **AI, Analytics & Smart Decisions** track.

---

## 📌 Project Overview
This project predicts the likelihood of a credit card customer defaulting in the next month using advanced machine learning techniques. The solution is designed to help financial institutions proactively identify high-risk customers and reduce potential losses.

## 🚀 Key Features
- **Exploratory Data Analysis (EDA)** to identify trends and patterns.
- **Feature Engineering** including domain-specific financial metrics.
- **Handling Imbalanced Data** with SMOTE.
- **Model Training & Tuning** with Logistic Regression, Decision Trees, Random Forest, XGBoost, LightGBM, and Stacking Ensembles.
- **Threshold Optimization** to maximize F2-score.
- **Final Deployment-Ready Model** optimized for recall.

## 📊 Tech Stack
- **Languages:** Python
- **Libraries:** scikit-learn, imbalanced-learn, XGBoost, LightGBM, pandas, NumPy, matplotlib, seaborn
- **Tools:** Jupyter Notebook, Git

## 📈 Performance
- **Primary Metric:** F2-score (focus on recall for defaulter detection)
- **Best Model:** Tuned LightGBM
- **F2-score:** High recall with balanced precision.

## 📂 Repository Structure
```
├── Datasets_FC_2025/
│   ├── train_dataset.csv
│   ├── validate_dataset.csv
├── latex_report/
│   ├── figures/
│   └── CreditCardDefaultPrediction_Utsah_22112109.tex
├── Credit_Card_Behaviour_Score_Prediction_22112109.ipynb
├── CreditCardDefaultPrediction_Utsah_22112109.pdf
├── submission_22112109.csv
```
