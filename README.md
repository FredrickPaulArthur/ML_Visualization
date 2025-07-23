# ML_Practice
Practicing ML for learning


The Dataset that is being analyzed and trained with is a Regression Dataset that I downloaded from Kaggle in order to demonstrate the all of stages of ML model training like,

1. Data Acquisition
    - loading structured data from csv, excel, SQL db, APIs or scraping the web.

2. Initial Data Analysis
    - Use .info(), .describe(), check null values.
    - Plot class distribution for classification problems.
    - Use pandas_profiling, sweetviz, or dtale for EDA reports.

3. Data Cleaning
    - Handle missing values (drop, mean/median imputation).
    - Remove or merge duplicates.
    - Handle inconsistent formats: dates, strings, booleans.
    - Outlier detection: IQR, Z-score, visual inspection via boxplots.

4. Feature Engineering
    - Encode categorical variables (Label, OneHot, Target).
    - Extract date/time features (month, weekday, etc.).
    - Binning (e.g., age groups).
    - Domain-driven feature creation.

5. Normalization or Scaling
    - Show histograms before and after scaling

6. Class balancing
    - Visualize imbalance (value_counts(), pie chart, bar plot).
    - Apply:
        - SMOTE (Synthetic Minority Oversampling Technique)
        - RandomOverSampler
        - class_weight='balanced'

7. Feature Selection/Elimination
    - Correlation matrix or Heatmap

8. ML Model selection
    - Try multiple models like - Logistic Regression, Decision Tree, Random Forest, XGBoost, SVM, K-Nearest Neighbors

9. Experimentation + Evaluation
    - Use:
        - train_test_split
        - cross_val_score
        - GridSearchCV, RandomizedSearchCV
    - Build Pipeline for preprocessing + training.
    - Evaluate using:
        - Accuracy, Precision, Recall, F1-Score
        - Confusion Matrix, ROC-AUC

10. Best Model Selection
    - Summarize results of all models in a DataFrame.
    - Use plots (e.g., bar chart) to compare metrics.
    - Pick best model based on:
        - Metric (e.g., recall for fraud detection)
        - Business impact