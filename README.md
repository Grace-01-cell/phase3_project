# phase3_project


##### Business Overview

Churn rate is one of the most important metrics that a company with recurring payment customers can calculate, and is most often expressed as a percentage of subscribers that have canceled their recurring payment plans. The higher the churn rate, the more customers stop buying from the business.

#### Business Problem

The objective was to build a classifier to determine if a customer would ‘soon’ leave SyriaTel, and to determine if there were predictable patterns.The three objectives were:

- To identify ways that can reduce customer churning and how can SyriaTel implement cost-effective solutions
- To create predictive,supervised models that can predict churn
- To Determine features of the dataset are primary determinants of customer churn and to what extent
  image.png

#### Data Understanding

- This project utilises data from [SyriaTel Customer Churn](link) dataset from Kaggle.
- The target variable in this dataset that we aimed to predict was identified as the churn column.
- The data is divided into train, test, and validation datasets. Each row of the train dataset represents a customer and each column represents a feature.
- The data set contains 3333 rows and 21 columns with both categorical and numerical features

#### Data preparation

- Categorical features are encoded as dummy variables
- The churn column being the target(y)was compared to other features to determine their correlation.
- Data preprocessing was done to normalize the data and to split the data into train, test, and validation datasets
- After inspecting and analysis,the data was viable for modeling.

#### Data Modeling

The data seemed to be imbalance and SMOTE before scaling

- Logistic Regression was used to predict churn gave a recall of 72%
- Decision Tree Classifier was used to predict churn gave a recall of 74%
- Random Forest Classifier was used to predict churn with a 72% recall
- fined tuned Random Forest gave a 71% recall and then it became the best model in the churn prediction

#### Evaluation

All the objectives that were set were all met.Features such as customer servive calls,international plan and total day charge were among the major determinants of customers churning.

- Customers who churned were usually customers who churned frequently.
- to reduce the customer churning rate,Syria tel should target on:
  - addressing customer issues in a timely and effective manner
  - increasing customer loyalty by giving incentive,discounts and promotion to their loyal customer
  - increasing customer satisfaction by offering discounts and promotions
- Recall was our classification metric since a model with high recall (i.e., identifying most of the customers who are likely to churn) is prefered

#### Conclusion and Recomendation

- SyriaTel should target on addressing customer issues in a timely and effective manner, so as to reduce customer churn and improve overall customer satisfaction.
- Given that over 42% of international plan holders churn, further investigation into retention efforts for these customers might be a worthwhile effort.
- Further investigation should be devoted to looking into the other characteristics of these customers to find out why there was a need to make this many calls to customer service and how the company could better assist these customers.
