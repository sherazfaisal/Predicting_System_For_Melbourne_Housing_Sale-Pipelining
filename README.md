# Predicting_System_For_Melbourne_Housing_Sale-Pipelining
We have preprocessed the Melbourne Housing Data Set using Pandas and Sciket-learn. We applied pipelining to the preprocessed results to generate a predictor for housing sales. 
![Image of Yaktocat](https://hmp.me/dbus)

The dataset has been divided into categorical and numerical data. The Simple Imputer is used to tackle the missing values while one-hot encoding is applied to the categorical data. We used Column Transformer for the transformation of both types of data. We applied Random Forest Regresser to the transformed data for the modeling of data. All of these preprocessing and modeling steps are imparted on the pipeline for training the raw data. The Dataset is spilited into train and test data using Train Test Split. We applied pipeling to the train data and compare the predicted result of test data with actual data. We get the accuracy of 82% with minimum absolute error of 17648. This generates a predicting system for any kind of raw data related to the housing sales of Melbourne. We applied the results to the raw data. Here is the sneak peak of the predicted results.

![Image of Yaktocat](https://hmp.me/dbut)
