# 🚦 Road Accident Risk Prediction

This repository contains my solution for the **Kaggle Playground Series – Season 5, Episode 10** competition.  
The goal of this challenge is to predict the **risk of road accidents** using structured tabular data.

🔗 **Competition Link:**  
https://www.kaggle.com/competitions/playground-series-s5e10  

📓 **Kaggle Notebook:**  
https://www.kaggle.com/code/saketjasuja/road-accident-risk  

---

## 📌 Problem Statement

Road accidents pose a serious threat to public safety.  
In this competition, the task is to build a machine learning model that accurately predicts the **probability of accident risk** based on various road, traffic, and environmental features.

The evaluation metric emphasizes ranking quality over raw accuracy.

---

## 📊 Dataset Overview

- **Train Dataset:** Includes features along with the target variable.
- **Test Dataset:** Contains the same features without the target.
- **Target:** Road accident risk probability.

The dataset is synthetic but closely resembles real-world road accident data.

---

## ⚙️ Methodology

The notebook follows a structured machine learning pipeline:

1. **Exploratory Data Analysis (EDA)**
   - Feature distribution analysis
   - Missing value inspection
   - Correlation analysis

2. **Data Preprocessing**
   - Missing value handling
   - Feature transformation
   - Memory optimization for faster training

3. **Model Training**
   - Gradient Boosting–based models
   - Stratified cross-validation
   - Out-of-fold prediction strategy

4. **Evaluation**
   - Competition-specific evaluation metric
   - Validation using cross-validation scores

5. **Submission**
   - Final predictions generated on the test dataset
   - Submission file created in Kaggle-required format

---

## 🤖 Machine Learning Algorithms Used

The solution primarily relies on **tree-based gradient boosting algorithms**, which are well-suited for structured tabular data:

- **Gradient Boosting Models**  
  Capture complex non-linear relationships and feature interactions efficiently.

- **Ensemble Learning Approach**  
  Combines predictions across multiple folds using out-of-fold (OOF) predictions to improve robustness and reduce overfitting.

- **Cross-Validation Strategy**  
  Stratified K-Fold cross-validation ensures stable performance across different data splits.

These models were chosen for their strong performance, scalability, and ability to handle feature importance effectively.

---

## 📈 Results

- Achieved a competitive leaderboard score
- Stable cross-validation performance
- Focused on generalization and robustness

(Note: Scores may change as the leaderboard updates.)

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Gradient Boosting Models  
- Kaggle Notebook Environment  

---

## 🚀 How to Run

1. Open the Kaggle notebook using the link above  
2. Run all cells sequentially  
3. Generate the submission file  
4. Submit predictions on Kaggle  

---

## ✍️ Author

**Saket Jasuja**  
Software Engineer | Machine Learning Enthusiast  

If you find this notebook useful, feel free to ⭐ it on Kaggle!
