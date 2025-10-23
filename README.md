# Student Retention Capstone

**Author:** Harshitha Koppala  
**Course:** INST414 — Data Science Capstone (ADSP Track)  
**Instructor:** Huy Nghiem  
**Sprint 2 Submission:** October 22, 2025  

---

## Project Overview
This project predicts which first-year students are at risk of dropping out based on academic, demographic, and financial factors.  
By identifying early risk patterns, universities can design proactive support systems that improve student retention.

---

## Data Sources
1. **Predict Student Dropout and Academic Success (Kaggle)**  
   - ~4,500 records from a Portuguese university  
   - Variables: GPA, attendance, financial aid, dropout status  

2. **IPEDS — Integrated Postsecondary Education Data System**  
   - Institutional-level retention and demographic context  

---

## Sprint 2 Progress
- Acquired and cleaned Kaggle dataset  
- Created derived features (`gpa_delta`, `financial_stress`)  
- Conducted exploratory data analysis (EDA)  
- Refined research question and modeling plan  
- Added report and notebooks to this repository  

---

## Repository Structure
Student-Retention-Capstone/
├── data/
│ ├── raw/
│ ├── interim/
│ └── processed/
├── notebooks/
│ ├── 01_data_exploration.ipynb
│ ├── 02_data_cleaning.ipynb
│ └── 03_modeling.ipynb
├── src/
│ ├── data/
│ ├── features/
│ ├── models/
│ └── visualization/
├── reports/
│ ├── figures/
│ └── sprint2_report.pdf
├── requirements.txt
├── .gitignore
└── README.md


---

## Next Steps (Sprint 3)
- Implement ML models (Random Forest, Gradient Boosting, Logistic Regression)
- Evaluate using AUC-ROC, precision, recall
- Visualize feature importance and interpret findings
- Develop actionable recommendations for universities

---

## References
- Kaggle: Predict Student Dropout and Academic Success Dataset  
- U.S. Department of Education: IPEDS  
- Pedregosa et al. (2011). *Scikit-learn: Machine Learning in Python*

