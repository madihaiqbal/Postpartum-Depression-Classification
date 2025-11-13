# Postpartum Depression Analysis & Classification

## Project Overview
This project explores **postpartum depression** using a dataset of new mothers. The goal is to understand the key factors contributing to postpartum depression and build predictive models to assess the risk of postpartum depression.  

We perform **exploratory data analysis (EDA)**, visualize patterns in the data, handle class imbalance using **SMOTE (Synthetic Minority Over-sampling Technique)**, and build **classification models** to predict postpartum depression risk.

---

## Dataset
The dataset is publicly available on Kaggle:  
[Postpartum Depression Dataset on Kaggle](https://www.kaggle.com/datasets/parvezalmuqtadir2348/postpartum-depression)

---

## Medium Blog Post
For a detailed write-up and insights, check out the Medium article:  
[Counting the Invisible: How Data Sheds Light on Postpartum Depression](https://medium.com/@madihaiqbal606/the-silent-battle-after-birth-what-the-data-reveals-about-postpartum-depression-a31019433629)

---

## Data Visualization
The repository contains Python scripts and notebooks for visualizing key patterns, including:
- Suicide attempts by anxiety status  
- Irritability towards baby and partner  
- Age group distribution of mothers  

All visualizations are created using **Matplotlib** and **Seaborn**.

---

## Machine Learning Models
We built two classification models to predict postpartum depression risk:  

1. **Support Vector Machine (SVM)**  
2. **Random Forest Classifier**  

### Handling Imbalanced Data
The dataset is imbalanced, so we used **SMOTE (Synthetic Minority Over-sampling Technique)** to generate synthetic samples for the minority class. This improves model performance on underrepresented cases.

### Model Evaluation
We evaluate models using the following metrics:  
- **Confusion Matrix** – to visualize true positives, false positives, true negatives, and false negatives  
- **Cross-Validation** – to ensure stability and reliability of model performance  
- **ROC Curve & AUC** – to assess the trade-off between sensitivity and specificity  

The notebook includes comparison of model performance **with and without SMOTE**, showing improvements in recall and F1-score for the minority class.

---

## Getting Started
To run the project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/madihaiqbal/Postpartum-Depression-Classification.git
