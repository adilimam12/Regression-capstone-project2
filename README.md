# Ted Talk Views Prediction

This repository contains code and resources for a project that focuses on predicting the number of views for TED Talks. The project aims to develop a machine learning model that can accurately estimate the popularity of TED Talk videos based on various features.





![Screenshot 2023-05-18 201535](https://github.com/adilimam12/Regression-capstone-project2/assets/113783902/093cce20-7f7a-4db8-92eb-08357c3b16d8)



**Project Overview**

The goal of this project is to build a predictive model that can forecast the number of views a TED Talk video is likely to receive. By understanding the factors that contribute to video popularity, such as topic, speaker, and presentation style, the project aims to provide insights into the factors that drive engagement and viewership on the TED platform.

**Project Features**

Data collection: Gathering a dataset of TED Talk videos, including features such as the title, speaker, description, duration, and tags.
Data preprocessing: Cleaning and preparing the dataset by handling missing values, transforming categorical variables, and normalizing numerical features.
Feature engineering: Extracting relevant features from the available data, such as sentiment analysis of the description, word count, or popularity of the speaker.
Exploratory data analysis: Analyzing the relationships between features and the target variable (number of views) to gain insights and identify patterns.
Model selection and training: Experimenting with different machine learning algorithms, such as linear regression, random forest, or gradient boosting, to build the predictive model.
Model evaluation: Assessing the performance of the trained models using appropriate evaluation metrics, such as mean squared error or R-squared.
Deployment: Deploying the trained model in a production environment or creating an API for real-time predictions.


**Models used:**

Linear Regression

Random Forest Regressor

XGBoost Regressor

**Conclusion:**

Starting with loading the data then performed Exploratory data analysis on various features, then carried out feature engineering and encoding of categorical columns, handled missing values in the dataset, dealt with outliers present in the dataset , performed transformations like log, sqrt and boxcox on numerical features to convert them to gaussian distribution, then carried out feature selection and build various models like Linear Regression, Random Forest Regressor and XGBoost Regressor. Evaluated these models on various metrics like MSE, RMSE, MAE ,R2 score and Adjusted R2 score. Finally selected the best model out of these.

In all these models our errors have been in the range of 2,00,000 which is around 10% of the average views. The model has been able to correctly predict views 90% of the time. After hyper parameter tuning, we have prevented overfitting and decreased errors by regularizing and reducing learning rate. Given that only have 10% errors, our models have performed very well on unseen data due to various factors like feature selection, correct model selection. After evaluating the performance of all the models, the best model is Random Forest Regressor based on MAE because MAE is linear and robust to outliers.

#**Python Libraries used**

**Datawrangling :**

Numpy

Pandas

**For Graphing :**

Matplotib

Seaborn

**Machine learning :**

Scikit-Learn

SK-Opt

XGBoost

CatBoost

**Miscellaneous :**

Google colab tools


