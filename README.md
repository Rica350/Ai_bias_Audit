# Bias Audit Report: Hiring Dataset  
_A machine learning fairness audit with bias detection, mitigation, and visualization_

## 📌 Overview
This project conducts a **bias audit on a hiring dataset** to analyze gender-related bias in hiring decisions. Using machine learning and fairness frameworks, the project evaluates **fairness metrics**, applies **bias mitigation techniques**, and visualizes results for stakeholder communication.

The goal is to ensure **responsible AI adoption** in recruitment by detecting and addressing discriminatory patterns in automated decision-making systems.

---

## ✨ Features
- Preprocessing of hiring dataset  
- Training **baseline Logistic Regression model**  
- Computation of **fairness metrics** (Accuracy, Selection Rate, TPR, FPR)  
- Bias **mitigation using reweighting techniques**  
- **Visualization** with confusion matrices & fairness metric plots  
- Concise **summary table** for stakeholder reporting  

---

## 📊 Dataset
- Dataset includes hiring decision records with demographic information.  
- **Target variable**: Hiring decision (Hired / Not Hired).  
- **Sensitive attribute**: Gender.  
- Dataset is split into **train** and **test sets**.  

---

## 🛠️ Technologies & Tools
This project was implemented in **Python (Jupyter Notebook)** using the following key libraries:

- **Data Handling**: `pandas`, `numpy`  
- **Machine Learning**: `scikit-learn`  
- **Fairness Framework**: [`fairlearn`](https://fairlearn.org/)  
- **Visualization**: `matplotlib`, `seaborn`  
- **Reporting**: `pandas` summary tables  

---

## ⚙️ How to Run the Project

### 1. Clone the repository
```bash
git clone https://github.com/your-username/hiring-bias-audit.git
cd hiring-bias-audit
