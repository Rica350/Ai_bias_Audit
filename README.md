# 🤖 Bias Audit Report: Hiring Dataset  

_A machine learning fairness audit with bias detection, mitigation, and visualization_  

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)  
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)](https://jupyter.org/)  
[![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1djf_4VohnSw0qD3d5xZ9PqA_3QgY73Oa?usp=sharing)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  

---

## 📌 Overview  

This project investigates **gender bias in hiring decisions** using a dataset inspired by real HR scenarios.  
We evaluate fairness with quantitative metrics, visualizations, and apply bias mitigation techniques to ensure equitable outcomes.  

The audit provides actionable insights for **responsible AI adoption** in recruitment processes.  

---

## ✨ Features  

- Preprocessing and encoding of hiring dataset  
- Training **baseline Logistic Regression model**  
- Computation of **fairness metrics**: Accuracy, Selection Rate, TPR, FPR  
- Bias **mitigation using Exponentiated Gradient / Fairlearn**  
- **Visualization**: confusion matrices & fairness metrics by group  
- Concise **summary table** for stakeholder reporting  
- Ready-to-run **Google Colab Notebook**  
- **PowerPoint presentation** summarizing findings for stakeholders  

---

## 📊 Dataset  

- Dataset contains hiring decision records with demographic info, qualifications, and experience  
- **Target variable**: HiringDecision (Hired / Not Hired)  
- **Sensitive attribute**: Gender  
- Split into **training** and **testing** sets  

---

## 🛠️ Technologies & Tools  

- **Python 3.10+**  
- **Jupyter Notebook / Google Colab**  
- **Pandas, NumPy** – Data processing  
- **Scikit-learn** – Machine learning & metrics  
- **Fairlearn** – Fairness metrics & mitigation  
- **Matplotlib, Seaborn** – Data visualization  
- **PowerPoint** – Stakeholder reporting  

---

## 📂 Project Structure  

