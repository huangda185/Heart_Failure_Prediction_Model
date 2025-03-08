### Heart Failure Prediction Model
Da Huang

#### Executive summary

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, 
which accounts for 31% of all deaths worldwide. Heart failure is one of the most common and frequent occurances cased by CVD.
With the help of of machine learning, we can provide early detection and provide patients a chance to decrease their chances of heart failures.

#### Rationale
Use of machine learning can provide early detection, we can determine certain features in our data that drives the likely of heart failure.

#### Research Question
Predict whether a patient will develop patient disease based on a number of factors.
Helps to identify patients that have potential to develop heart disease. 
Can be used to predict and possible prevention of heart disease.
Focus on certains attributes that plays a bigger role in increased risk.
People who are likely to have heart disease can get preventive treatment or lifestyle modification.

#### Data Sources
Heart Failure Prediction Dataset that includes 11 clinical features for predicting heart failures.
Source of the data was provided by Kaggle
https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction/data

Description of Files
'data' - Dataset that includes 11 clinical features for predicting heart failures.



'heart_failure.ipynb' - this file contains the code that compares the different classifying models.

#### Methodology
Compare different classifers and their accuracy scores to determine what is the best classifer to help predict if a patient will develop heart disease.
Also review and determine what are the best features that attributes to a likelyhood of heart disease.

#### Results
- The accuracy score for the training and test scores for logistic regression and svc models rate the highest with logistic regression with the best test score.
- Although svc has the higher training score, the test score is more crucial as it provides a better estimate of the model's performance in real-world scenarios with unseen data.

| model      | train score      | test score      | time      |
|---------------|---------------|---------------|---------------|
| knn | 0.865772 | 0.860000 | 0.155018 |
| logisticregression | 0.854027 | 0.893333 | 0.187075 |
| svc | 0.904362 | 0.880000 | 0.189232 |
| decisiontreeclassifier | 0.895973 | 0.820000 | 0.136952 |

#### Next steps
Narrow data features to focus more on those that have high co_eff that affects target feature.
