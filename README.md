# Factors Influencing Obesity

# Problem to solve

The problem we’ve addressed in this project is that the obesity situation in Latin American countries of Mexico, Peru, and Colombia has become a significant public health concern, with high prevalence rates and associated health risks. Healthcare professionals, public health organizations, and individuals have the urgent need to understand the underlying determinants of obesity and promote healthier lifestyles.

By analyzing the data collected from Mexico, Peru, and Colombia, we aim to develop an effective predictive model to predict if one will become obese based on their individual conditions, and identify the key factors significantly contributing to obesity in terms of eating habits and physical activities.


# Method

# Data collection:
The data was originally collected using a web platform with a survey where anonymous users answered each question, then the information was processed obtaining 18 attributes and 34598 records.

# Data cleaning and transformation:
This step involves cleaning and preprocessing the data to remove any errors, inconsistencies, or missing values.

# Data visualization:
Tableau has been used to create various types of charts to gain insights into the distribution of variables, correlation between variables, and observe patterns and trends.

# Data Analysis:
For the predictive modelling and evaluation, I started with logistic regression as a baseline model due to its simplicity and interpretability. Then I utilized the KNN to develop the second model.

# Data interpretation: 
This step involves drawing conclusions from the data analysis.

# Key findings:

I found a model that had really good accuracy:
Logistic Regression : 92% prediction accuracy 

Compared with another model that is K-Nearest Neighbors (KNN) model.
got the accuracy of 79 %.

Overall, the logistic regression model in comparison to KNN model seems to be the preferred choice for this classification task based on the evaluation metrics.

# Conclusion:

Our analysis highlights the importance of both numerical and categorical factors in understanding and predicting obesity types. Weight, age, and several categorical variables such as family history with overweight and gender emerged as significant predictors of obesity types. The logistic regression model yielded high accuracy and precision, indicating its effectiveness in predicting obesity types based on the identified features.

# Recommendations & next steps:

For future research, the predictive accuracy of our model could be improved when new additional variables are collected and added into the data frame, such as occupation, working environment,area. Based on the current findings, some of additional in-depth research can be further conducted to probe into some unusual relationship that we found. For example, more research could done and more data could be collected to investigate why the group of people who always eat vegetables has higher probability of becoming obese.
