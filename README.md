# Early-Detection-of-Fetal-Distress-Using-Machine-Learning-on-CTG-Data-for-Smarter-Prenatal-Care

Improving Maternal and Child Health in Low-Resource Settings Through AI-Driven Monitoring

---

## Overview

This research project applies machine learning to analyze Cardiotocography (CTG) signals and accurately classify fetal health into Normal, Suspect, or Pathological categories. Leveraging models such as XGBoost, Random Forest, CatBoost, and LightGBM, the solution aims to enhance diagnostic precision and support clinical decisions in underserved regions.

Achieved up to 99% accuracy (XGBoost) — surpassing traditional statistical and manual CTG interpretation methods.

---

## Project Goals

- Build supervised ML models to assess fetal health using CTG data
- Compare classifier performance using robust evaluation metrics
- Develop scalable, interpretable solutions for real-world, low-resource clinics

---

## Technologies Used

| Category        | Tools / Techniques                                           |
|----------------|--------------------------------------------------------------|
| Dataset         | Public CTG dataset (anonymized, compliant)                  |
| Preprocessing   | Null removal, outlier filtering, SMOTE balancing            |
| Models          | XGBoost, CatBoost, LightGBM, Random Forest, SVM, CNN       |
| Evaluation      | Accuracy, Precision, Recall, ROC-AUC                        |
| Development     | Python, Scikit-learn, Pandas, Matplotlib, Seaborn           |

---
## Results

The experimental evaluation demonstrated that machine learning models significantly outperformed traditional methods in detecting fetal distress from CTG data. Among all models tested, the XGBoost classifier achieved the highest performance with an accuracy of 99.04% and an ROC-AUC of 0.9998, making it the most reliable model for this classification task. CatBoost and LightGBM followed closely, both achieving accuracies above 98%. Random Forest and Gradient Boosting also maintained strong performance, indicating the robustness of ensemble-based models in medical signal classification. In contrast, baseline models such as Naïve Bayes and Logistic Regression showed lower accuracy and recall, especially in detecting 'Suspect' and 'Pathological' cases. These results confirm the effectiveness of advanced ML techniques in supporting early, accurate, and automated diagnosis of fetal complications, particularly beneficial in under-resourced clinical environments.

## ML Workflow

```mermaid
flowchart TD
    A[CTG Signal Data] --> B[Preprocessing & Cleaning]
    B --> C[Feature Engineering + SMOTE]
    C --> D[Model Training]
    D --> E[Evaluation & Visualization]
    E --> F[Clinical Insight & Interpretation]


© 2025 Farman Ali All rights reserved.  
Unauthorized use, reproduction, or distribution of this project’s content (including code, data, and methodology) is strictly prohibited without prior written permission.
