# Cloth Manufacturing Company Analysis

## Introduction

This project involves the analysis of a dataset from a cloth manufacturing company to predict whether a store is located in the United States (US) or not. The 'US' column is the dependent variable, and the remaining columns serve as independent variables.

## RandomForest Classifier

### Overview

The **RandomForest Classifier** is a versatile ensemble learning algorithm used for both classification and regression tasks. It constructs a multitude of decision trees and merges them to achieve more accurate and stable predictions.

### Significance

Random Forests offer several advantages:

- **High Accuracy:** By aggregating predictions from multiple trees, Random Forests often provide higher accuracy compared to individual decision trees.

- **Reduction of Overfitting:** The ensemble nature helps reduce overfitting, making the model more robust.

- **Feature Importance:** Random Forests can assess the importance of different features, aiding in understanding the key contributors to predictions.

- **Versatility:** Suitable for various types of data and tasks, making it a popular choice in machine learning applications.

### Use Cases

Random Forests find applications in diverse domains:

- **Finance:** Used for credit scoring and fraud detection due to their accuracy and ability to handle complex data.

- **Healthcare:** Applied in disease prediction models where interpreting feature importance is crucial for medical insights.

- **Marketing:** Utilized for customer segmentation and targeting in marketing strategies.

## Methodology

### 1. Data Preprocessing

#### 1.1 Importing Necessary Packages and Extracting Data

The project began by importing essential Python packages and extracting the dataset from the cloth manufacturing company.

#### 1.2 Handling Missing Values and Encoding Categorical Data

During preprocessing, it was observed that there were no missing values. Categorical columns were encoded into numerical format using label encoding.

#### 1.3 Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) involved using a heatmap for correlation analysis and boxplots to detect outliers.

#### 1.4 Outlier Detection and Imputation

Outliers were identified using boxplots, and imputation was performed with threshold values to maintain data integrity.

#### 1.5 Save Cleaned Data

The cleaned data was saved separately for future use.

### 2. Modeling

#### 2.1 Data Splitting and Scaling

The dataset was split into training and testing sets (80:20 split), and data scaling was performed using Standard Scaler.

#### 2.2 RandomForest Classifier

The RandomForest Classifier was chosen for modeling, with 'US' as the dependent variable and other columns as independent variables.

### 3. Model Evaluation

#### 3.1 Accuracy Assessment

The model was evaluated for accuracy by predicting 'US' values for the test set. The entire process was repeated 1000 times with different random states, resulting in an overall accuracy of 98.75%.

## Conclusion

The project successfully analyzed the cloth manufacturing company's dataset to predict whether a store is located in the United States. Through careful preprocessing, exploratory data analysis, and the implementation of a RandomForest classifier, the model achieved a high accuracy rate of 98.75%.

