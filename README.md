# 🤖 Machine Learning Projects

A collection of end-to-end machine learning projects covering classification, 
regression, and statistical hypothesis testing across diverse real-world domains.
All projects were independently developed by Soumita Chowdhury as part of her 
Post Graduate program in Artificial Intelligence and Machine Learning (2021).
---

## Projects

### 1. 🧠 Parkinson's Disease Detection via Voice Recordings
**Type:** Binary Classification | **Technique:** Ensemble Methods

Early detection of Parkinson's Disease using biomedical voice measurements 
(jitter, shimmer, HNR, RPDE, DFA, PPE). Compared multiple classifiers to 
identify the most reliable diagnostic model.

| Model | Test Accuracy |
|---|---|
| Random Forest | **89.83%** |
| Bagging Classifier | **89.83%** |
| Decision Tree | 84.75% |
| KNN | 83.05% |
| Logistic Regression | 81.36% |
| Gaussian Naive Bayes | 64.41% |

> **Best model: Random Forest / Bagging (89.83% accuracy)**  
> Key insight: Ensemble methods significantly outperformed single classifiers, 
> particularly on the minority class (healthy patients).

---

### 2. 🏦 Bank Loan — Customer Conversion Prediction
**Type:** Binary Classification | **Technique:** Multiple Classifiers

Predicting the likelihood of a liability customer purchasing a personal loan, 
enabling targeted marketing campaigns.

| Model | Test Accuracy |
|---|---|
| KNN | **95.33%** |
| Logistic Regression | 94.80% |
| Naive Bayes | 94.80% |

> **Best model: KNN (95.33% accuracy)**  
> Key insight: Class imbalance (90% non-buyers vs 10% buyers) was a key 
> challenge — precision/recall on the minority class was more meaningful 
> than overall accuracy.

---

### 3. 🏗️ Concrete Strength Modelling
**Type:** Regression | **Technique:** Linear → Polynomial → SVR → Random Forest + Hyperparameter Tuning + PCA

Predicting the compressive strength of high-performance concrete using 
component ratios. Demonstrated progressive model improvement through 
systematic experimentation.

| Approach | R² Score |
|---|---|
| Linear / Ridge Regression | 0.71 |
| Lasso Regression | 0.62 |
| Polynomial Regression | 0.78 |
| SVR | ~0.93 |
| Random Forest | ~0.93 |
| **Random Forest + RandomizedSearchCV** | **~0.94** |
| After PCA (2 features removed) | ~0.89 |

> **Best model: Tuned Random Forest (94% R²)**  
> Key insight: Hyperparameter tuning via RandomizedSearchCV yielded the best 
> result. PCA retained 89% accuracy with a reduced feature set — useful for 
> deployment in resource-constrained environments.

---

### 4. 💊 Medical Costs — Statistical Hypothesis Testing
**Type:** Inferential Statistics | **Techniques:** t-test, Z-test, ANOVA

Investigating factors driving medical insurance costs using rigorous 
statistical hypothesis testing.

**Hypotheses tested:**
- H₀: BMI of males and females are the same *(tested with t-test)*
- H₀: Proportion of smokers across genders are the same *(tested with proportions_ztest)*
- H₀: BMI of women remains the same regardless of number of children *(tested with ANOVA)*

> Key insight: Statistical significance was found across multiple hypotheses, 
> revealing meaningful gender and lifestyle-based differences in health metrics 
> — with direct implications for insurance pricing models.

---

### 5. 🌿 Plant Species Detection from Photos
**Type:** Multi-class Image Classification | **Technique:** CNN

Classifying plant species from photographs using Convolutional Neural Networks.

*See also: Deep Learning Projects repo for the DL-focused implementation.*

---

### 6. 📝 NLP Multi-Classifier
**Type:** Text Classification | **Technique:** Multiple NLP approaches

Demonstrating multiple NLP classification techniques across different 
text datasets.

*See also: Deep Learning Projects repo for the DL-focused implementation.*

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-orange)
![pandas](https://img.shields.io/badge/pandas-Data-lightblue)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-yellow)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Viz-green)
![SciPy](https://img.shields.io/badge/SciPy-Stats-purple)

---

## Author

**Soumita Chowdhury**  
[GitHub](https://github.com/soumita20) | 
[LinkedIn](https://www.linkedin.com/in/soumita-chowdhury-93934617/)
