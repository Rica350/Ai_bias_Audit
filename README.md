# 🤖 Bias Audit Report: Hiring Dataset  

_A machine learning fairness audit with bias detection, mitigation, and visualization_  

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)  
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)](https://jupyter.org/)  
[![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1djf_4VohnSw0qD3d5xZ9PqA_3QgY73Oa?usp=sharing)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  

---

## ⚙️ Quick Access  

**2. Open the Notebook**  
**[Google Colab Notebook (Recommended)](https://colab.research.google.com/drive/1djf_4VohnSw0qD3d5xZ9PqA_3QgY73Oa?usp=sharing)**  

**3. View the Presentation**  
**[PowerPoint slides summarizing findings](https://capeitinitiative-my.sharepoint.com/:p:/g/personal/nontathu_sikhwebu_capaciti_org_za/EXt5hfJhKo5Cq8XBpc-r6SwBYJpw_bMvvUX5FJoixSh6rg?e=tr8MF8)**  

**[Fairlearn](https://fairlearn.org/?utm_source=chatgpt.com)** – Fairness metrics & bias mitigation toolkit  
**[What-If Tool](https://pair-code.github.io/what-if-tool/?utm_source=chatgpt.com)** – Visual ML inspection and fairness testing

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
- **[Fairlearn](https://fairlearn.org/?utm_source=chatgpt.com)** – Fairness metrics & mitigation  
- **Matplotlib, Seaborn** – Data visualization  
- **PowerPoint** – Stakeholder reporting  

---

## 📂 Project Structure  


├── 1TechTeam_AIBias.ipynb # Jupyter Notebook with bias audit analysis
├── Bias_Audit_Presentation.pptx # PowerPoint summary for stakeholders
├── README.md # Project documentation
├── requirements.txt # Python dependencies (optional)


---

## ⚙️ How to Run the Project  

### 1. Clone the repository  
```bash
git clone https://github.com/your-username/hiring-bias-audit.git
cd hiring-bias-audit

**2. Open the Notebook**  
Use Google Colab (recommended): **[Open Notebook in Colab](https://colab.research.google.com/drive/1djf_4VohnSw0qD3d5xZ9PqA_3QgY73Oa?usp=sharing)**  

**3. View the Presentation**  
PowerPoint slides summarizing findings: **[View Presentation](https://capeitinitiative-my.sharepoint.com/:p:/g/personal/nontathu_sikhwebu_capaciti_org_za/EXt5hfJhKo5Cq8XBpc-r6SwBYJpw_bMvvUX5FJoixSh6rg?e=tr8MF8)**

**🙌 Contribution**

We welcome contributions! 🚀

Fork the repository

Create a new branch (feature-name)

Commit changes and submit a Pull Request

**📜 License**

This project is licensed under the MIT License.
You are free to use, modify, and distribute with attribution.

**👥 Team & Acknowledgments**

Developed by TechTeam

Special thanks to the CAPACITI training initiative for guidance and support

**📢 Notes for Users**

The Colab notebook allows anyone to run the analysis without local setup

The PowerPoint is designed for non-technical stakeholders to understand bias insights

Feel free to fork, modify, or contribute improvements to the project

**📚 References**

Barocas, S., Hardt, M., & Narayanan, A. (2019). Fairness and Machine Learning: Limitations and Opportunities

Mitchell, M. et al. (2021). Algorithmic Fairness: Choices, Assumptions, and Definitions

- Microsoft Research: [Fairlearn](https://fairlearn.org/?utm_source=chatgpt.com)  
- Google AI: [What-If Tool](https://pair-code.github.io/what-if-tool/?utm_source=chatgpt.com)





