# Penguins Species Classification

## Overview
This project is based on classification of penguin species using various data analysis and visualization techniques.

The dataset, provided by the Palmer Station LTER, includes physical measurements and categorical information for three species of penguins (Adelie, Chinstrap, Gentoo).

The objective is to perform data cleaning, exploratory data analysis, apply machine learning algorithms, and visualize results effectively.

## Technologies & Libraries Used
- **Python**: Primary language for analysis.  
- **Pandas**: For data manipulation and preprocessing.  
- **NumPy**: For array and numerical operations.  
- **Matplotlib & Seaborn**: For data visualization.  
- **Scikit-learn**: For encoding, modeling and evaluation.  
- **Google Colab**: For interactive notebook environment.  

## Methodology

### 1. Data Loading & Cleaning:
- Dataset loaded from CSV.
- Missing values handled using median/mode imputation.
- Data types and unique values examined.

### 2. Exploratory Data Analysis (EDA):
- Pair plots, violin plots, histograms, and correlation heatmaps used for understanding patterns.

### 3. Feature Encoding:
- Label Encoding for categorical features.
- One-Hot Encoding for modeling.

### 4. Model Training:
- Logistic Regression used to classify penguin species.
- Model accuracy, confusion matrix, and classification report evaluated.

### 5. NumPy Operations:
- Used for mathematical and statistical operations (mean, std, reshape, etc.).

## Results & Insights
- Bill length and flipper length showed strong species differentiation.
- Chinstrap penguins had the highest body mass among the three.
- The model achieved over 95% accuracy on test data.
- Visualizations clearly depicted the separation between species based on physical traits.

## Conclusion
This project demonstrates the full data science pipeline—from loading raw CSV data, through exploratory analysis and visualization, to encoding and modeling.

It emphasizes the importance of clean data and how simple models can perform well on well-structured datasets.

**Future Improvements:**
- Hyperparameter tuning
- Use of ensemble methods
- Model deployment
