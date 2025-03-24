### Heart Failure Prediction Model
Da Huang

#### Executive summary

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, 
which accounts for 31% of all deaths worldwide. Heart failure is one of the most common and frequent occurances cased by CVD.
With the help of of machine learning, we can provide early detection and provide patients a chance to decrease their chances of heart disease.

#### Rationale
Use of machine learning can provide early detection, we can determine certain features in our data that drives the likelyhood of heart disease.

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
Compare different classifers and their accuracy, f1, recall, and precision to determine what is the best classifer to help predict if a patient will or will not develop heart disease.
Also review and determine what are the best features that attributes to a likelyhood of heart disease.

#### Results
| Model      | Accuracy      | Precision      | Recall      | F1      |
|---------------|---------------|---------------|---------------|---------------|
| Random Forest | 0.880000 | 0.864865 | 0.888889 | 0.876712 |
| Logistic Regression | 0.860000 | 0.840000 | 0.875000 | 0.857143 |
| KNN | 0.860000 | 0.849315 | 0.861111 | 0.855172 |
| SVC | 0.853333 | 0.828947 | 0.875000 | 0.851351 |
| Gradient Boosting | 0.840000 | 0.815789 | 0.861111 | 0.837838 |
| Decision Tree | 0.826667 | 0.819444 | 0.819444 | 0.819444 |

#### Main takeaways
The model that performs the best is Random Forest at predicting heart disease with accuracy rate of 88% and a recall rate of 89%. We also have a relatively high precision and F1 scores which indicates a model taht excels at correctly identifying positive instances while minimizing false positives.

Identified main features that should be focused on are ST_Slope (exercising), Age, Chest Piain Type, and Exercise-induced angina.
Our model will be able to in health clinics and hospitals to flag high-risk patients before developing or worsening through
1) Preventive Care: Strategies designed to catch issues early or prevent them altogether.
or 
2) Proactive Monitoring: disease management/ assessments aimed at catching complications early.

#### Conclusion: 

Patient who don't exerercise as frequent and older patients should be more aware of habits in their daily living.
Although age is not controllable and should be monitor more closely as age climbs, the patient in general should be focusing on exercising and be aware of the type of check pains they are experiencing. 

#### Future Improvements
Track patients over time and predict the progression of heart disease.
Also look at other factors/features that may help increase our model accuract rates. 


