# Mobile Price Range Prediction

## Overview
This project aims to predict the price range of mobile phones based on their features such as battery power, camera megapixels, etc. The dataset used in this project contains information about mobile phones from various brands and their price range. The goal is to build a machine learning model that can accurately predict the price range of a mobile phone given its features.

## Dataset
The dataset used in this project is sourced from AlmaBetter. It contains information about mobile phones from various features such as Battery power, Ram, pixel size etc. The dataset has 21 columns and 2,000 rows. Each row represents a mobile phone and each column represents a feature such as battery power, camera megapixels, etc. The target variable is the price range of the mobile phone, which can take on one of four values: 0, 1, 2, or 3.


## Methodology
The following steps were followed in this project:

1. Data exploration and visualization to gain insights into the dataset and identify any patterns or relationships between the features and target variable.
2. Data pre-processing, which involved handling missing values, encoding categorical variables, and scaling the numerical features.
3. Model selection and training. Several machine learning algorithms were trained and evaluated, including logistic regression, decision tree, random forest, and support vector machine.
4. Hyperparameter tuning to optimize the performance of the chosen model.
5. Evaluation of the final model using various performance metrics such as accuracy, precision, recall, and F1 score.
6. Interpretation of the model using SHAP values to understand the importance of each feature in predicting the price range of a mobile phone.

## Results
The best performing model was the Logistic Regression, which achieved an accuracy of 92% on the test set. The most important features in predicting the price range of a mobile phone were battery power, RAM, and pixel size.

## Conclusion
In this project, we successfully built a machine learning model to predict the price range of mobile phones based on their features. The random forest classifier was chosen as the final model, which achieved an accuracy of 92% on the test set. The most important features in predicting the price range were battery power, RAM, and pixel size. This model can be used by mobile phone manufacturers or retailers to estimate the price range of a new mobile phone based on its features.
