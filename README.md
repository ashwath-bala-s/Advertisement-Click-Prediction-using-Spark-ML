# Advertisement Click Prediction using Spark ML

**Introduction:**

In the digital advertising industry, understanding and predicting user behavior is crucial for optimizing ad campaigns and maximizing return on investment. Accurately predicting whether a user will click on an advertisement can help marketers tailor their strategies, improve targeting, and enhance overall campaign performance. This project aims to leverage Spark ML, a robust machine learning library for big data, to develop model that predicts the likelihood of advertisement clicks based on user and ad-related features.

**Problem Statement:**

The objective of this project is to build a machine learning model using Spark ML to predict whether a user will click on an advertisement. By analyzing features such as user demographics, browsing behavior, ad characteristics, and contextual information, the model will learn to identify patterns and factors that influence click behavior.

**Dataset:**

In this project, we have divided the dataset into 3 different parts:
   * **`TRAIN`** - It has 1400000 Rows which will be used to train the model.
   * **`VALIDATION`** - It has 350000 Rows which will be used to evaluate the model.
   * **`TEST`** - It has 350000 Rows on which we will test our final model.

   Each of the datasets has the following columns

 * `ID`:   Unique ID of the Click
 * `Country`:   Country Code
 * `Carrier':   Wireless Network Operator Code
 * `TrafficType`:  Whether the advertisement is for Adults or mainstream.
 * `ClickDate`:  Date at which the advertisement was clicked
 * `Device`:  Type of Device from which advertisement was clicked
 * `Browser`:  Type of Browser from which advertisement was clicked
 * `OS`:  Type of OS from which advertisement was clicked
 * `publisherID`:  Unique ID of publisher
 * `advertiserCampaignId`: Unique ID of campaign of advertisement
 * `Fraud`:  If the click was fraud or not
 * `ConversionStatus`:  If the click was fraud or not  ( `Target Variable` )

**Project Description:**

• Conducted Exploratory Data Analysis (EDA) to analyze insights and patterns in the click prediction dataset.

• Implemented Data Pre-Processing, Feature Encoding techniques, and Data Transformations to enhance the data prepared for the machine learning model.

• Built machine learning models such as Logistic Regression and Decision Tree to predict whether a particular advertisement will be clicked or not.

• Implemented techniques such as Cross-Validation and Grid Search to improve the model performance.

• Developed a Spark ML Pipeline for the logistic regression model.

• Achieved an AUC-ROC score of 0.738 with the Logistic Regression Model.

**Skills:** Spark ML · Spark · Exploratory Data Analysis · Data Pre-Processing · Data Transformation · Feature Encoding · Logistic Regression · Decision Trees · Grid Search · Cross Validation · Spark ML Pipeline · Hyper-Parameter Tuning 
