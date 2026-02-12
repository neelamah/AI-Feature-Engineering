# AI-Feature-Engineering
Feature Engineering means creating, modifying, or selecting variables (features) so that a machine learning model performs better.


Video Link : https://youtu.be/1Yw9sC0PNwY




Feature Engineering means creating, modifying, or selecting variables (features) so that a machine learning model performs better.

Feature Engineering = Transform + Scale + Create + Select + Clean features


Type:-
1️⃣ Feature Transformation
    🔹 Mathematical Transformations:- 
    Log transformation → log(x)
    Square / square root → x², √x
    Power transformation
    Box-Cox / Yeo-Johnson
    👉 Used when data is skewed.

    🔹 Encoding Categorical Variables
        One-Hot Encoding -> used for nominal caytegorial data(like gender, female which can not to rank)
        Label Encoding-> used for output column ( which is categorial)
        Ordinal Encoding -> used for caytegorial data (like poor, good exellent which can be ranked.)

2️⃣ Feature Scaling:- 
    Used especially in:- (used in where we measure distance)
    Logistic Regression
    KNN
    SVM
    Neural Networks

    🔹 Standardization
    (x−mean)/std    
    🔹 Min-Max Scaling
    (x−min)/(max−min)
    🔹 Robust Scaling
      Uses median & IQR (good for outliers)  

3️⃣ Feature Creation (Feature Construction)
    Creating new features from existing ones.
    Examples:
    BMI = weight / height²
    Age from Date of Birth
    Extract day/month/year from date
    Total purchase = quantity × price
    Interaction features → x1 * x2

4️⃣ Feature Selection
Choosing important features.
🔹 Filter Methods
    Correlation
    Chi-square
    ANOVA

5️⃣ Handling Missing Values
    Mean/Median imputation
    Mode imputation
    KNN imputation
    Model-based imputation

6️⃣ Handling Outliers
    Capping (Winsorization)
    IQR method
    Z-score method


🔟 Dimensionality Reduction
    PCA
    t-SNE
    UMAP



Important concepts:-
ColumnTransformer 
pipeline
multicolarity