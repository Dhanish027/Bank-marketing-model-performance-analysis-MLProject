# Bank-marketing-model-performance-analysis-MLProject

Objective :The objective is to use all this info. to predict whether someone will end up saving money with the bank.This helps the bank to decide who to focus on when they're trying to get people to save money with them.

# Model Analysis

1. Logistic Regression: It achieved an accuracy of 77.3% & demonstrated good performance in classifying the target variable.
2. Decision Tree : It achieved an accuracy of 73.4%.
3. Random Forest : It achieved an accuracy of 79.9%.
4. Support vector machine : It achieved an accuracy of 78.8%
5. Gradient Boosting : It achieved an accuracy of 80.8%.
6. K-Nearest Neighbor : It achieved an accuracy of 73.4%.
7. Naive Bayes : It achieved an accuracy of 76.7%.

# Summarization:
Gradienet Boosting achieved highest accuracy among the classifiers tested, followed closely by Random Forest. These models demonstrated robust performance in predicting the target variable, Let's check it further

Double checking if the gradient boosting and random forest are the best among other classifiers comparing through precision , recall, F1 score

# Feature Importance
Feature Importance analysis is a technique used to determine the relative importance of each feature in predicting the target variable.

Extracting feature importance from Gradient Boosting and Random Forest classifier, considering they exhibited the best performance.

## Gradient Boosting:
 1. Duration : This feature has the highest importance, indicating that the duration of the calll has a significant impact on the outcome.
 2. Pdays : The no. pf days that passed after the client  was lasst contacted from a previous campaign  is also a crucial factor
 3. Age Group & Previous Contacts : These features have relatively lower importance but still contribute to the model.

## Random Forest:
1. Duration : Similarly, the duration of the call is the most crucial predictor in this model.
2. Jobs & campaign : Job type and no. of contacts during this campaign also have notable importance.
3. Education & Age Group : These features also contribute significantly to the model's prediction.

# conclusion;

 Both models highlight the importance of the call duration and economic indicators. Other factors such as job type, education level, and age group also play essential roles in predicting the outcome of the marketing campaign.
          Overall , these insights can guide marketing strategies to focuass on specific customer demographics  and tailor communication strategies based on economic conditions and call duration.
          
