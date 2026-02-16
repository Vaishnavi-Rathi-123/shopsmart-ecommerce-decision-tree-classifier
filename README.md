# 🛒 ShopSmart E-Commerce Purchase Prediction

## 📌 Project Overview

This project predicts whether a visitor will complete a purchase during a browsing session on the ShopSmart e-commerce platform.

The dataset contains **12,330 unique user sessions** collected over one year. Each session represents a different visitor to ensure unbiased insights and avoid the influence of repeat users, promotional campaigns, or seasonal trends.

The objective is to build a **Decision Tree Classifier** to identify high-intent users based on session-level behavioral features.

---

## 🎯 Problem Statement

ShopSmart struggles to accurately identify visitors who are likely to complete a purchase. This results in:

- Inefficient marketing strategies  
- Poor advertisement targeting  
- Lost revenue opportunities  

The goal is to develop a machine learning model that predicts purchase intent using browsing behavior data.

---

## 📊 Dataset Information

- **Total Sessions:** 12,330  
- **Feature Types:** Numerical and Categorical  
- **Target Variable:** Purchase (Yes / No)  
- **Dataset Nature:** Imbalanced  

Each row represents a unique browsing session.

---

## 🔎 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Purchase vs non-purchase distribution  
- User interaction and engagement patterns  
- Time spent on product and informational pages  
- Correlation between numerical features  
- Class imbalance evaluation  

---

## ⚙️ Data Preprocessing

- Encoding categorical variables  
- Handling missing values  
- Train-test split  
- Managing class imbalance  
- Feature selection  

---

## 🌳 Model Implementation

### Decision Tree Classifier

The Decision Tree algorithm was selected because:

- It is interpretable  
- It handles mixed data types  
- It performs well for classification tasks  
- It requires minimal preprocessing  

---

## ✂️ Model Pruning

To reduce overfitting, **Cost Complexity Pruning (`ccp_alpha`)** was applied.

Pruning helped:

- Reduce tree depth  
- Control model complexity  
- Improve generalization  
- Stabilize F1-score  

---

## 📈 Model Evaluation

Due to class imbalance, **F1-score** was used instead of accuracy.

**Benchmark Requirement:**  
F1-score ≥ 0.55  

The final pruned model met the benchmark requirement.

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 👩‍💻 Author

**Vaishnavi Rathi**  
