# SECB3203_25261
Programming For Bioinformatics

This is a repository which served as central hub for the students to showcases their projects. In this courses, students will equipt with essential programming skills in bioinformatics. It introduces computational tools and techniques for solving biological problems. Students will explore Python programming as a core language for bioinformatics applications. Emphasis is placed on applying programming to address practical challenges in biological data analysis and problem-solving. The course is taught through lectures and hands-on labs, with active learning and a strong emphasis on practical problem-solving and applied programming skills. By the end of the course, students will be able to use Python programming to analyze biological data and design computational solutions. They will also develop autonomy, leadership, and responsibility in approaching bioinformatics tasks.

## GROUP MEMBERS
- IDLAN HARRIS - A25CS0069; [idlanharris@graduate.utm.my](mailto:idlanharris@graduate.utm.my).
- NABIL IKHWAN - A25CS0115; [nabilikhwan@graduate.utm.my](mailto:nabilikhwan@graduate.utm.my).
- DANIA AQEELAH - A25CS0382; [daniaaqeelah@graduate.utm.my](mailto:daniaaqeelah@graduate.utm.my).

# 🫁 Asthma Diagnosis Prediction System

## 📋 Project Overview
A machine learning pipeline for predicting asthma diagnosis using patient symptoms and demographics.  
This project demonstrates a complete ML workflow from data cleaning to model evaluation and deployment readiness.

> ⚠️ **Educational use only** — not for clinical decision-making.

---

## 🎯 Project Objectives
- Clean and prepare synthetic medical data
- Perform exploratory data analysis (EDA)
- Train and compare multiple ML models
- Evaluate and refine models using advanced metrics
- Extract interpretable medical insights

---

## 🔄 Project Progress Flow

### Progress 1–2: Data Preparation & Wrangling
**Input**
- `data.csv` (raw synthetic dataset)

**Processing**
- Remove duplicated records (≈98% duplicates)
- Merge one-hot encoded symptoms into single columns
- Create binary target: `Has_Asthma` (1 = Asthma, 0 = No Asthma)
- Remove invalid / unknown severity values

**Output**
- Cleaned dataset with **4,320 patients**

---

### Progress 3: Exploratory Data Analysis & Data Enhancement
**EDA Performed**
- Descriptive statistics
- Group comparison by asthma status and severity
- ANOVA statistical testing
- Correlation analysis

**Data Enhancement**
- Injected realistic medical patterns:
  - Asthma patients: 70% chance of breathing difficulty
  - Non-asthma patients: 30% chance
- Created meaningful symptom–diagnosis relationships

**Result**
- ML-ready dataset with realistic behavior

---

### Progress 4: Model Development
**Models Trained**
1. Logistic Regression  
2. Random Forest Classifier  
3. Support Vector Machine (SVM)  
4. K-Nearest Neighbors (KNN)  
5. Decision Tree Classifier  

**Analyses**
- Accuracy, Precision, Recall, F1-Score
- Confusion matrices
- Feature importance
- Linear & polynomial regression
- Decision threshold tuning

**Best Model**
- **Random Forest Classifier** (≈90% F1-Score)

---

### Progress 5: Model Evaluation & Refinement
**Advanced Evaluation**
- ROC curves & AUC
- Overfitting / underfitting detection
- Ridge regression (regularization)
- GridSearchCV for hyperparameter tuning
- Cross-validation

**Outcome**
- Optimized, stable, generalizable model

---

## 📊 Key Findings

### Top Predictive Features
1. Difficulty-in-Breathing
2. Dry-Cough
3. Symptom_Count

### Model Performance (Typical)
- Accuracy: 86–92%
- Precision: 85–90%
- Recall: 88–93%
- F1-Score: 87–91%

### Medical Insights
- Breathing-related symptoms dominate prediction
- Symptom count increases with asthma severity
- Age and gender show weak correlation

---

## ⚙️ Technical Stack

### Libraries
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- SciPy

### Algorithms
- Classification: Logistic Regression, Random Forest, SVM, KNN, Decision Tree
- Regression: Linear, Polynomial, Ridge
- Model Selection: GridSearchCV, Cross-validation
- Metrics: Accuracy, Precision, Recall, F1, ROC-AUC

---

## ⚠️ Limitations
- Synthetic data only
- No clinical validation
- Not suitable for real medical decisions

---

**🎓 Educational Project | ⚕️ Not for Clinical Use**
