# Wine Quality Prediction using ANN
Predicting the Quality of Red Wine using Deep Learning Algorithms for Classification Analysis, Data Visualizations and Data Analysis.

## Context
The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).

This dataset is also available from the UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality.

## Content
For more information, read [Cortez et al., 2009].

##### Input variables (based on physicochemical tests):

1 - fixed acidity 

2 - volatile acidity 

3 - citric acid 

4 - residual sugar 

5 - chlorides 

6 - free sulfur dioxide 

7 - total sulfur dioxide 

8 - density 

9 - pH 

10 - sulphates 

11 - alcohol 

##### Output variable (based on sensory data): 

12 - quality (score between 0 and 10) 

## Steps

1. Import Required Libraries
2. Import Dataset
3. Understand the dataset
4. Perform the EDA
5. Check for outliers
6. Separate the data into input features and target feature
7. Perform feature scaling on input features
8. Check the correlation among the data
9. Handle the imbalanced data
10. Spilt the data into training and testing
11. Create a model
12. Make sure if the data is flattened and encoded properly
13. Build the model
14. Train the model
15. Predict the model
16. Check for accuracy and classification report
17. For satisfied performance of the model repeat steps 13, 14, 15, and 16 by hypertunning the model

## Dataset Information
- The dataset contains 1599 rows and 12 columns. The target variable 'quality' has values ranging from 3 to 8, with most wines having a quality of 5 or 6.
- The dataset has no missing values, and all features are of type float64. The describe function provides statistical summaries of the numerical columns.

## Exploratory Data Analysis (EDA)
EDA involves visualizing the distribution of each feature and exploring the imbalanced nature of the quality variable.

## Outlier Check
Visualizing box plots for each feature to identify potential outliers in the data.

## Data Preprocessing
Scaling the features using StandardScaler to ensure uniformity in feature scales.

## Correlation Heatmap
Creating a heatmap to visualize the correlation matrix of the features.

## Handling Imbalanced Dataset
Utilizing SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset.

## Model Building - Neural Network
Splitting the data into training and testing sets and building a neural network model for predicting wine quality.

# Conclusion
This notebook covers the entire process of wine quality prediction, from data exploration and preprocessing to building a neural network model. The handling of an imbalanced dataset using SMOTE and the creation of visualizations provide insights into the wine dataset.

## Acknowledgements
This dataset is also available from the UCI machine learning repository, https://archive.ics.uci.edu/ml/datasets/wine+quality.

Please include this citation if you plan to use this database: P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.

## Relevant publication
P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.
