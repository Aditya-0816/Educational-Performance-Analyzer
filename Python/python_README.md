# 🎓 Educational Performance Analyzer (Python)

This project is designed to be **structured and instructional** so that even a beginner can follow along, understand the workflow, and play with the values to see different outcomes.

---

## 📂 Project Structure
- **Data Loading** → Load student datasets (`student-mat.csv`, `student-por.csv`)
- **Basic Cleaning** → Remove duplicates, check missing values, convert yes/no to 1/0
- **Feature Engineering** → Create new features like average score, pass/fail, grade bands
- **EDA (Exploratory Data Analysis)** → Descriptive statistics, correlation analysis, group-wise insights
- **Visualization** → Distribution plots, correlation heatmaps (split into smaller groups for clarity)
- **Modeling** → Logistic Regression, Decision Tree, Random Forest, Linear Regression
- **Evaluation** → Accuracy, RMSE, confusion matrix, feature importance

---

## 🧹 Basic Cleaning
- Remove duplicate rows  
- Handle missing values  
- Convert categorical yes/no columns into binary (1/0)

👉 Newbies can try dropping vs imputing missing values to see how results change.

---

## 🛠️ Feature Engineering
- Average score from G1, G2, G3  
- Pass/Fail flag (G3 ≥ 10)  
- Grade bands (A, B, C, D)  
- Study time categories  

👉 Beginners can adjust thresholds (e.g., pass mark = 12 instead of 10) and see how classification changes.

---

## 🔎 EDA
- Descriptive statistics (`.describe()`)  
- Correlation analysis (split into academic, demographic, support features)  
- Group-wise insights (e.g., pass vs fail study time)

👉 Try adding/removing columns in correlation groups to explore different relationships.

---

## 📊 Visualization
- Distribution plots for grades, study time, absences  
- Correlation heatmaps (split into 2–3 smaller groups for readability)

👉 Change bin sizes or categories to see how plots vary.

---

## 🤖 Modeling
- Logistic Regression → Pass/Fail classification  
- Decision Tree → Simple interpretable model  
- Random Forest → Ensemble model for higher accuracy  
- Linear Regression → Predict actual grades  

👉 Beginners can tweak parameters (e.g., number of trees, max depth) and observe performance changes.

---

## 🎯 Goal
This notebook is **instructional and flexible**. A beginner should be able to:
- Run each section independently  
- Modify thresholds, parameters, or features  
- See how changes affect outcomes  

The idea is to **learn by playing with the values**.
