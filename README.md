Task2_AI_ML_Internship_2026

Task 02: Exploratory Data Analysis (EDA)

Objective To understand the dataset using descriptive statistics and visualizations, and to identify patterns, trends, and anomalies.

Dataset

    Titanic Dataset (CSV)

Tools Used

    Python, Pandas
    Matplotlib, Seaborn
    Plotly optional

Steps Performed

    Data Loading & Overview
        Loaded the dataset using Pandas.
        Checked dataset structure using head() and info().

    Summary Statistics
        Generated descriptive statistics such as mean, median, standard deviation, min, and max.
        Used describe(), mean(), median(), and std() to understand numeric features.

    Missing Value Analysis
        Identified missing values using isnull().sum().
        Handled missing values using simple techniques (mean imputation / column removal).

    Univariate Analysis (Distribution of Features)
        Created histograms to understand data distribution.
        Used boxplots to detect outliers and skewness in numeric features.

    Bivariate & Multivariate Analysis
        Generated a correlation matrix to study relationships between numeric features.
        Created pairplots to visualize relationships and class separation.

    Pattern, Trend & Anomaly Detection
        Analyzed survival patterns based on gender and passenger class.
        Identified skewed distributions and outliers in Fare and Age.

Conclusion

This EDA helped in understanding the structure and behavior of the dataset, identifying important features, and discovering meaningful patterns.
Such analysis is essential before performing feature engineering or training any machine learning model.
