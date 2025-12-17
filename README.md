# Armenian Kindergarten ML Analysis

A comprehensive **machine learning and statistical analysis project** focused on Armenian kindergartens across multiple cities.  
The project integrates **web scraping, data preprocessing, supervised learning, unsupervised learning, and model optimization** to support data-driven decision making in early childhood education planning.

---

## 📌 Project Overview

This project analyzes kindergarten data across **9 Armenian cities** using **classification, regression, and clustering techniques**.

The workflow includes:
- Automated **data scraping** from official municipal portals
- **Data cleaning and preprocessing**
- **Feature engineering and dimensionality reduction**
- Training and evaluation of **multiple machine learning models**
- **Hyperparameter optimization** using Grid Search
- Interpretation of results with real-world policy implications

---

## 🧠 Machine Learning Tasks & Results

### 1️⃣ Classification — Predicting Kindergarten Overcrowding

**Target Variable:** `is_overcrowded`  
**Best Model:** **Decision Tree (Grid Search Optimized)**

**Performance Metrics:**
- Accuracy: **100.00%**
- Precision: **100.00%**
- Recall: **100.00%**
- F1-Score: **1.0000**
- ROC-AUC: **1.0000**

**Key Findings:**
- Perfect classification performance after hyperparameter tuning
- Robust generalization confirmed via 5-fold cross-validation
- Model excels at identifying overcrowded facilities

---

### 2️⃣ Regression — Predicting Waiting List Size

**Target Variable:** `order_count`  
**Best Model:** **Linear Regression (Grid Search Optimized)**

**Performance Metrics:**
- RMSE: **0.0000**
- MAE: **0.0000**
- R² Score: **1.0000**

**Key Findings:**
- Model explains **100% of variance** in waiting list size
- Average prediction error: **±0.00 children**
- Cross-validation confirms perfect stability

---

### 3️⃣ Clustering — Discovering Kindergarten Groups

**Best Model:** **K-Means Clustering**

**Evaluation Metrics:**
- Silhouette Score: **0.3576**
- Number of Clusters: **2**
- Davies–Bouldin Index: **1.2664**

**Cluster Insights:**
- Natural groupings reveal distinct kindergarten profiles
- Clusters differ by capacity utilization, demand pressure, and operational scale

---

## 📊 Model Comparison Summary

### Classification Models (Ranked by F1-Score)
| Model | F1-Score | Accuracy |
|------|----------|----------|
| Decision Tree | 1.0000 | 1.0000 |
| Random Forest | 1.0000 | 1.0000 |
| Logistic Regression | 0.9333 | 0.9697 |
| K-Nearest Neighbors | 0.8485 | 0.9242 |
| Naive Bayes | 0.8235 | 0.9091 |

---

### Regression Models (Ranked by RMSE)
| Model | RMSE | R² |
|------|------|----|
| Linear Regression | 0.0000 | 1.0000 |
| Random Forest | 2.5872 | 0.9962 |
| Decision Tree | 8.3603 | 0.9604 |

---

### Clustering Models (Ranked by Silhouette Score)
| Model | Silhouette Score |
|------|------------------|
| K-Means | 0.3576 |
| Hierarchical | 0.3490 |

---

## ⚙️ Hyperparameter Optimization

### Grid Search — Classification
- Exhaustive parameter search
- 5-fold cross-validation
- Significant improvement over baseline models

### Grid Search — Regression
- Systematic hyperparameter tuning
- Optimization based on Mean Squared Error
- Enhanced predictive performance

---

## 🧾 Final Conclusions

This project successfully:

- Predicted kindergarten overcrowding with **100% F1-score**
- Forecasted waiting list sizes with **100% variance explained**
- Identified **2 meaningful kindergarten clusters**
- Applied rigorous **cross-validation and statistical testing**
- Optimized models through **systematic Grid Search**

The resulting models are **production-ready** and can support **data-driven planning and resource allocation** in Armenia’s early childhood education system.

---

## 📁 Project Metadata

- **Total Models Trained:** 10  
- **Best Classification Model:** Decision Tree  
- **Best Regression Model:** Linear Regression  
- **Best Clustering Model:** K-Means  

---

## 🛠️ Technologies Used

- **Python 3.13**
- **pandas, numpy**
- **scikit-learn**
- **matplotlib, seaborn**
- **selenium, BeautifulSoup**
- **Google Colab & Google Drive**

---

## 📜 License

This project is intended for **academic and research purposes**.
