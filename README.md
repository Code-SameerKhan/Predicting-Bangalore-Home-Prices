# Predicting Bangalore Home Prices
# Summary

1. Created a tool that predicts when an employee is going to resign in order to help perfect employee management and improve working space environment.
2. Based on the public release data available on Kaggle, the features are employed.
3. Engineered features to calculate dependencies of the target variable on the independent variables.
4. Optimized Logistic, Random Forest, Decision Tree and Naive Bayes classifier using GridSearchCV to reach best model.
5. Achieved an accuracy of 90.62% in correctly predicting the outcome.
6. Getting to understand employees is a major task in any successful organization. Various factors combine enough to create a snowball effect in the minds of employee on whether he/she sees the future of oneself in their current working environment.

Some of the major factors include Salary, Satisfaction level, promotion, average working hours, etc… By correlating the different features we can arrive on a decision based on the prediction. Since the output here is whether the employee leaves or not therefore it is termed as a classification problem.

The target variable price depends on numerous features but we can identify it's distribution by visualizing.
![](visuals/price-distribution.png)

# Relationship between various features
![](visuals/realationship.png)

By determining the correlation between the variables we can analyse the dependency as well as the correlation.
A classification model attempts to draw some conclusion from observed values. Given one or more inputs a classification model will try to predict the value of one or more outcomes.

![](visuals/heatmap.png)

Popular algorithms that can be used for binary classification include:
1. Logistic Regression
2. k-Nearest Neighbors
3. Decision Trees
4. Support Vector Machine
5. Naive Bayes

After deploying the various regression algorithms and using GridSearchCV to determine the optimal parameters we conclude-
Linear regression works the best with an accuracy of 90.62%
