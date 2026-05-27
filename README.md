# 🚀 Data Science & AI Projects

> A collection of end-to-end machine learning systems spanning credit risk, healthcare, optimization, and autonomous AI agents.

---

## 🔍 Explainable Credit Risk Model

**Predicting loan default risk with full regulatory-grade explainability using ensemble methods and SHAP/LIME.**

| Metric | Value |
|--------|-------|
| 📊 Dataset | 50,000+ loan records |
| 🎯 Accuracy | 92% |
| 📈 AUC-ROC | 0.96 |
| ⏱️ Auditor review time | ↓ 40% |

**Models:** XGBoost · Random Forest · Logistic Regression

**Explainability:** SHAP (global + local feature importance) · LIME (instance-level explanations)

**Highlights:**
- Trained and compared three models; XGBoost achieved best AUC-ROC at 0.96
- Integrated SHAP summary plots and waterfall charts for model transparency
- LIME explanations surfaced per-prediction reasoning for compliance audits
- Reduced manual auditor review time by 40% through automated explanation reports

**Tech Stack:** `Python` `XGBoost` `Scikit-learn` `SHAP` `LIME` `Pandas` `Matplotlib`

---

## 🏥 Medical Disease Prediction System

**Multi-disease classifier for early clinical diagnosis across several conditions using engineered clinical features.**

| Metric | Value |
|--------|-------|
| 📊 Dataset | 20,000+ patient records |
| 🎯 Accuracy | 95% |
| 🔴 Recall | 98% |
| 🔬 Features engineered | 30+ clinical features |
| ✅ False negative reduction | 18% |

**Models:** Support Vector Machine (SVM) · Random Forest · Neural Networks

**Highlights:**
- Engineered 30+ domain-informed clinical features (vitals, lab ratios, symptom composites)
- Achieved 98% recall — minimizing missed diagnoses in high-stakes clinical scenarios
- Reduced false negatives by 18% vs baseline through threshold tuning and ensemble voting
- Benchmarked SVM, RF, and NN across multiple disease targets; best model selected per condition

**Tech Stack:** `Python` `Scikit-learn` `TensorFlow/Keras` `Pandas` `NumPy` `Seaborn`

---

## 🧬 Genetic Algorithm Optimizer (Knapsack)

**Evolutionary optimizer solving the 0/1 Knapsack problem — 60× faster than brute-force with near-optimal results.**

| Metric | Value |
|--------|-------|
| 🔢 Search space | 1,000+ item combinations |
| 🏆 Optimal solution rate | 97% |
| ⚡ Speed vs brute-force | 60× faster |
| 📉 Convergence improvement | 45% faster |
| 🔄 Generations | 50 |

**Algorithm:** DEAP Genetic Algorithm (selection · crossover · mutation)

**Highlights:**
- Implemented full GA pipeline: population init, fitness evaluation, tournament selection, uniform crossover, and bit-flip mutation
- Tuned population size, crossover rate, and mutation probability to maximize convergence speed
- 97% optimal solution rate across 1,000+ test combinations within 50 generations
- 45% faster convergence vs standard GA baseline through adaptive parameter tuning

**Tech Stack:** `Python` `DEAP` `NumPy` `Matplotlib`

---

## 🤖 LangGraph AI Agent

**Autonomous multi-step AI agent built with LangGraph for dynamic task planning, tool use, and execution.**

| Feature | Detail |
|---------|--------|
| 🧠 Framework | LangGraph (stateful agent graphs) |
| 🔄 Architecture | Multi-node DAG with conditional routing |
| 🛠️ Capability | Autonomous task planning & execution |
| 🔗 Tools | Integrated external tools & APIs |

**Highlights:**
- Designed a stateful LangGraph pipeline with planning, tool-calling, and reflection nodes
- Implemented conditional edge routing to dynamically re-plan based on intermediate results
- Agent autonomously decomposes high-level goals into sub-tasks and executes them sequentially
- Supports human-in-the-loop checkpoints for approval on critical steps

**Tech Stack:** `Python` `LangGraph` `LangChain` `OpenAI API` `LangSmith`

---

## 🛠️ Tech Stack Overview

```
Languages       Python
ML / DL         Scikit-learn · XGBoost · TensorFlow · Keras · DEAP
Explainability  SHAP · LIME
AI Agents       LangGraph · LangChain · OpenAI API
Data            Pandas · NumPy
Visualization   Matplotlib · Seaborn
Tracking        LangSmith
```

---

*Feel free to explore each project folder for notebooks, results, and detailed documentation.*
