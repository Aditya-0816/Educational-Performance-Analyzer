# 📄 Educational Performance Analyzer

## 📑 Project Overview
This project analyzes student performance data (UCI/Kaggle datasets) using **Python** and **R**.  
The aim is to identify key predictors of academic success and build machine learning models to flag at‑risk students early, enabling educators to take proactive measures.

---

## 🛠️ Tech Stack
- **Python:** Pandas, NumPy, Scikit‑Learn, Matplotlib, Seaborn  
- **R:** dplyr, ggplot2, caret, randomForest, psych  

---

## 📂 Repository Structure
educational-performance-analyzer/
│
├── README.md
├── python/
│   ├── notebook.ipynb
│   ├── requirements.txt
│   ├── final_summary.txt
│   └── figures/   # saved plots (ROC curves, confusion matrices, feature importance)
│
└── r/
    ├── notebook.Rmd
    ├── final_summary.txt
    └── figures/   # saved plots (attendance vs grades, studytime vs grades)

---

## ⚙️ Methodology
1. **Data Preprocessing** → missing value imputation, one‑hot encoding, normalization  
2. **Feature Engineering** → attendance ratio, total study hours, avg previous grade  
3. **Exploratory Data Analysis (EDA)** → correlation heatmaps, scatterplots, ANOVA, Pearson correlation  
4. **Modeling** → Logistic Regression, Decision Tree, Random Forest, Linear Regression  
5. **Evaluation** → Accuracy, Precision, Recall, F1‑score, ROC‑AUC, RMSE, MAE  
6. **Visualization** → ROC curves, confusion matrices, feature importance charts  
7. **Recommendations** → attendance monitoring, parental engagement, study skill mentoring  

---

## 📊 Results
- **Random Forest** achieved >90% accuracy (best performing model).  
- **Key predictors:** attendance, study habits, parental education, past failures.  
- Consolidated metrics available in:  
  - `python/final_summary.txt`  
  - `r/final_summary.txt`  

---

## 🚀 How to Run
### Python
```bash
pip install -r python/requirements.txt
jupyter notebook python/notebook.ipynb
```

---

# Python
👉 Run directly on Colab: [Python Notebook](https://colab.research.google.com/drive/193YFgj1a1ed65ZKMtBWZV-YXjOvQI4wB?usp=sharing)

# R
Open r/notebook.Rmd in RStudio and knit to HTML/PDF.
👉 Run directly on Colab: [R Notebook](https://colab.research.google.com/drive/1Lb75s6xnLme8_6aOfiNaTEXr95v-sauW?usp=sharing)

---

## 📈 Figures
Plots are saved in the figures/ folders under each language.
Examples include:

- Attendance vs Grades scatterplot

- Studytime vs Grades boxplot

- ROC curve for Random Forest

- Confusion matrix heatmap

- Feature importance chart

---

## 🎯 Insights
Attendance strongly correlates with final grades.

- Students with higher studytime and parental education perform better.

- Past failures negatively impact performance.

- Data‑driven early warning systems can help educators intervene sooner.
