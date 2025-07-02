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

## ML Workflow

```mermaid
flowchart TD
    A[CTG Signal Data] --> B[Preprocessing & Cleaning]
    B --> C[Feature Engineering + SMOTE]
    C --> D[Model Training]
    D --> E[Evaluation & Visualization]
    E --> F[Clinical Insight & Interpretation]
![Descriptive Caption](path/to/image.png)

