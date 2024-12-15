# Overview
Let's say you work at an Internet Service Provider (ISP) and you've been tasked with improving the email filtering system for its customers. You've been provided with a dataset that contains information about emails, with two possible classifications: spam and not spam. The ISP wants you to take this dataset and develop a supervised machine learning (ML) model that will accurately detect spam emails so it can filter them out of its customers' inboxes.

You will be creating two classification models to fit the provided data, and evaluate which model is more accurate at detecting spam. The models you'll create will be a logistic regression model and a random forest model.

## Evaluation Metrics
### Logistic Regression Model
- Model score with training data was 0.9295652173913044
- Model score with test data was 0.9278887923544744

### Random Forest Classifier Model
- Model score with training data was 0.9997101449275362
- Model score with test data was 0.9669852302345786

## Results
So we can see that the **Random Forest Classifier Model** performed **better** than the **Logistic Regression Model** for both training data as well as test data by a decent margin. RFC Model at first glance felt overfitted as the training data based score was very close to 1 but the results with testing data were equally impressive. 