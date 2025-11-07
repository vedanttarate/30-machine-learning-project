
# Car Data Analysis

This project focuses on exploring and cleaning a car dataset to understand the factors that influence the selling price of cars. The goal is to perform data analysis, visualization, and preprocessing to prepare the data for further machine learning applications.

---

## What I Did

### 1. Data Loading and Inspection
- Loaded the `cars.csv` file using Pandas.
- Viewed the first and last few rows, checked dataset shape, column names, and data types.
- Generated statistical summaries and checked for missing values.

### 2. Univariate Analysis
- Plotted histograms for `selling_price` and `km_driven` to analyze their distributions.
- Created bar charts for categorical features like `brand`, `fuel`, and `owner`.

### 3. Bivariate Analysis
- Compared `brand` and `fuel` using bar plots.
- Computed correlation between numerical features and visualized with a heatmap.
- Used boxplots to identify and visualize outliers.

### 4. Data Encoding
- Applied **One-Hot Encoding** for categorical variables (`brand`, `fuel`, `owner`).
- Demonstrated **Label Encoding** as an alternative approach.

### 5. Feature Scaling
- Scaled numerical columns (`km_driven`, `selling_price`) using **StandardScaler** to normalize feature ranges.

### 6. Outlier Handling
- Detected and removed outliers using the **IQR (Interquartile Range)** method.
- Rechecked boxplots to confirm outlier removal.

---

## What I Learned
- How to explore, visualize, and clean data using **Pandas**, **Matplotlib**, and **Seaborn**.
- Techniques for encoding categorical variables.
- How to scale features and handle outliers effectively.
- Steps to prepare a dataset for machine learning.

---

## Tools and Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  


This project gave me hands-on experience in data preprocessing and exploratory data analysis, helping me understand how to prepare real-world data for modeling.
