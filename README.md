# phase3_project

##### Business Overview

Churn rate is one of the most important metrics that a company with recurring payment customers can calculate, and is most often expressed as a percentage of subscribers that have canceled their recurring payment plans. The higher the churn rate, the more customers stop buying from the business.

#### Business Problem

The objective was to build a classifier to determine if a customer would ‘soon’ leave SyriaTel, and to determine if there were predictable patterns.The three objectives were:

- Determine if a customer would ‘soon’ leave SyriaTel
- Determine if there were predictable patterns
- Determine features of the dataset are primary determinants of customer churn and to what extent

#### Data Understanding

- The data is divided into train, test, and validation datasets. Each row of the train dataset represents a customer and each column represents a feature.
- The data set contains 3333 rows and 21 columns with both categorical and numerical features

#### Data preparation

- Categorical features are encoded as dummy variables
- The churn column being the target(y)was compared to other features to determine their correlation.
- Data preprocessing was done to normalize the data and to split the data into train, test, and validation datasets
- After inspecting and analysis,the data was viable for modeling.

#### Data Modeling

- Logistic Regression was used to predict churn
- Decision Tree Classifier was used to predict churn
- Random Forest Classifier was used to predict churn

#### Data Evaluation

- Logistic Regression achieved an accuracy of 86%
- Decision Tree Classifier achieved an accuracy of 95%
- Random Forest Classifier achieved an accuracy of 94%

#### Conclusion
