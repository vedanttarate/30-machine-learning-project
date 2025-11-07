# Bank Marketing Dataset  
## Predicting Term Deposit Subscriptions  

This project focuses on predicting whether a customer will subscribe to a **term deposit** based on personal, contact, and campaign-related information. The dataset used is the **Bank Marketing Dataset**, which contains details of customers contacted during a marketing campaign.  

---

## Author
**Name:** Vedant Tarate  
**PRN:** 202301070134  

---

## Project Overview
The objective of this project is to:
- Perform data preprocessing and cleaning.  
- Encode and normalize features for modeling.  
- Train multiple machine learning algorithms.  
- Compare model performances based on key evaluation metrics.  

---

## Steps Performed

### 1. Load Dataset
- Imported the dataset `bank.csv` using Pandas.  
- Displayed the first few rows to understand the structure.  

### 2. Data Inspection
- Checked dataset information with `info()`.  
- Displayed descriptive statistics using `describe()`.  
- Verified missing values using `isnull().sum()`.  

### 3. Explore Categorical Columns
- Displayed value counts for all categorical features.  

### 4. Encode Categorical Columns
- Applied **Label Encoding** using `LabelEncoder()` from `sklearn.preprocessing` to convert categorical data into numerical form.  

### 5. Normalize Numerical Columns
- Used **MinMaxScaler** to normalize `duration` and `balance` columns to a 0–1 range.  

### 6. Split Dataset
- Split the data into **training (75%)** and **testing (25%)** sets using `train_test_split()`.  

### 7. Train and Evaluate Machine Learning Models
Trained and tested multiple classification models including:
- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Gaussian Naive Bayes  
- Bernoulli Naive Bayes  
- XGBoost  
- LightGBM  
- CatBoost  
- AdaBoost  

(Excluded MultinomialNB due to feature constraints.)

### 8. Model Evaluation
Each model was evaluated based on the following metrics:
- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC Score  

The performance metrics were stored in a results dictionary and displayed as a DataFrame for easy comparison.

---

## Results Summary
After training all models, the performance metrics were compared to identify the best-performing algorithm for predicting term deposit subscriptions.

---

## Technologies and Libraries Used
- **Python**  
- **Pandas**  
- **Scikit-learn**  
- **XGBoost**  
- **LightGBM**  
- **CatBoost**  
- **NumPy**  
- **Matplotlib** (optional for visualization)  

---

## Key Learnings
- How to preprocess categorical and numerical data effectively.  
- How to apply scaling and encoding for machine learning.  
- How to compare multiple classification algorithms using standard evaluation metrics.  
- Understanding the trade-offs between model accuracy, precision, recall, and F1-score.  

---

## Conclusion
This project demonstrates a complete machine learning workflow — from data cleaning and preprocessing to training and evaluating multiple models. The results can help identify which algorithms work best for predicting customer subscription behavior in marketing campaigns.
