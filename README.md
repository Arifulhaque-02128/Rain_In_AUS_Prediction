# Rain_In_AUS_Prediction

## Problem Statement
The problem is to develop a predictive model that accurately predicts whether it will rain in Australia on the next day based on various meteorological features and historical weather data. The goal is to assist residents, farmers, and relevant authorities in making informed decisions and preparations, such as planning outdoor activities, agricultural practices, water resource management, and potential flood prevention measures.

## Dataset
The dataset is collected from https://www.kaggle.com/jsphyg/weather-dataset-rattle-package .

## Summary 
1. Data Loading: The dataset was loaded into the project, likely in a format such as a CSV file, to start the analysis.

2. Data Pre-processing: To ensure data quality, several pre-processing steps were carried out. Firstly, any rows or columns containing null values were dropped from the dataset to avoid issues during modeling. Additionally, label encoding was applied to transform categorical variables into numerical representations for compatibility with machine learning algorithms. Finally, the data was split into features (input variables) and the target variable (whether it will rain or not).

3. Data Visualization: To gain insights and understand the relationships between variables, data visualization techniques using libraries such as matplotlib and seaborn (sns) were employed. Plots, such as scatterplots, histograms, or bar charts, were created to visualize the distribution of variables and observe any patterns or trends related to rainfall.

4. Train-Test Split: The pre-processed data was divided into two sets: a training set and a test set. The training set was used to train the models, while the test set was kept separate and used to evaluate the models' performance on unseen data.

5. Model Selection and Evaluation: Two machine learning algorithms, logistic regression and decision tree, were applied to the training data. Logistic regression is a popular choice for binary classification problems like predicting rain. Both models were trained using the training data.

6. Model Evaluation: The trained models were evaluated using evaluation metrics to assess their performance on the test data. In this case, the accuracy metric was used to measure the proportion of correct predictions. The logistic regression model achieved an accuracy of 85%, while the decision tree model achieved an accuracy of 79%.

Based on the evaluation results, it was observed that the logistic regression model outperformed the decision tree model in terms of accuracy, indicating that it was more successful in predicting rain in Australia based on the given features.

## Finding and Insights
1. Feature Importance: Through exploratory data analysis and modeling, it was found that certain features have a significant impact on predicting rain in Australia. These features are temperature, humidity, wind speed, rainfall in the previous day.
2. Model Performance: After training and evaluating the logistic regression model, it was observed that the model achieved 85% accuracy. These metrics provide insights into the model's ability to predict rainfall accurately.

