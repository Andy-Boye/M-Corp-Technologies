# M-Corp-XGBoost

## An Engineered Explainable XGBoost Framework for Predicting Student Internship Placement Success Using Academic and Skill Profiles

### Overview

M-Corp-XGBoost is a research-driven machine learning framework designed to predict internship placement success among university students using academic performance, technical skills, certifications, extracurricular activities, and employability-related attributes.

The framework extends the standard XGBoost algorithm through three engineered enhancements:

1. **Focal Loss Fabrication** – improves learning under class imbalance conditions.
2. **SHAP-Based Feature Pruning** – removes low-contributing features while maintaining model interpretability.
3. **Bayesian Hyperparameter Optimization** – automatically discovers optimal model configurations.

The goal is to provide accurate and explainable predictions that can support students, universities, and employers in internship placement decision-making.

---

## Research Contribution

M-Corp-XGBoost introduces a novel combination of:

* Focal Loss Engineering
* SHAP Explainable AI (XAI)
* Bayesian Hyperparameter Optimization

for internship placement prediction within the context of higher education institutions, particularly in Ghana and Sub-Saharan Africa.

The framework addresses three major gaps:

* Methodological Gap
* Technical Explainability Gap
* African Educational Data Gap

---

## Proposed Architecture

Input Features
↓
Data Preprocessing
↓
Feature Engineering
↓
SHAP Feature Importance Analysis
↓
Feature Pruning
↓
Bayesian Hyperparameter Optimization
↓
Engineered XGBoost Training
↓
Internship Placement Prediction
↓
SHAP Explainability Layer

---

## Dataset

The project utilizes a hybrid dataset consisting of:

### Public Dataset

Placement Prediction Dataset (Kaggle)

### Field Dataset

Data collected from students of Kwame Nkrumah University of Science and Technology (KNUST), Ghana.

Planned features include:

* CGPA
* Technical Certifications
* Programming Languages
* Internship Applications Submitted
* Communication Skills
* Teamwork Skills
* Extracurricular Activities
* Placement Training Attendance
* Year of Study
* Department/Programme
* Internship Placement Outcome

---

## Evaluation Metrics

The framework will be evaluated using:

* AUC-ROC
* AUC-PR
* Accuracy
* Precision
* Recall
* Macro F1-Score
* SHAP Feature Importance
* Statistical Significance Testing (Wilcoxon Signed-Rank Test)

---

## Technology Stack

* Python 3.12.3
* XGBoost 2.1.1
* Scikit-learn 1.6.0
* SHAP 0.46.0
* NumPy 1.26.4
* Pandas 2.2.1
* Matplotlib 3.8.4
* imbalanced-learn 0.12.3
* Jupyter Notebook 7.1.2

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Andy-Boye/M-Corp-Technologies.git
cd M-Corp-Technologies/M-Corp-XGBoost
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the project notebook and run all cells to:

* Load and preprocess data
* Train baseline models
* Train the engineered M-Corp-XGBoost model
* Generate predictions
* Produce SHAP explanations
* Evaluate performance metrics

---

## Expected Outputs

* Internship Placement Predictions
* SHAP Summary Plots
* SHAP Waterfall Plots
* ROC Curves
* Precision-Recall Curves
* Confusion Matrices
* Ablation Studies
* Baseline vs Engineered Model Comparisons

---

## Research Status

Current Stage: Research Proposal Approved

Status:

* Literature Review Completed
* Methodology Defined
* Repository Created
* Dataset Collection Pending
* Model Development Pending

---

## Author

**Amoako-Ayim Andrews**
Department of Computer Science
Kwame Nkrumah University of Science and Technology (KNUST)
Ghana

---

## Supervisor

**Dr. Eric Osei Opoku**
Department of Computer Science
Kwame Nkrumah University of Science and Technology (KNUST)

---

## License

This repository is intended for academic research and educational purposes. Licensing information will be updated upon project completion.

---

## Citation

If you use this work in academic research, please cite the corresponding publication once released.

**Project:** M-Corp-XGBoost
**Version:** 1.0 (Research Prototype)

