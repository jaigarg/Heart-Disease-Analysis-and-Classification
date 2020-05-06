# Heart-Disease-Analysis-and-Classification
This is an analysis of various features explaining presence of Heart Diseases and various Classification models have been built to find the same. The Dataset can be found [here](https://www.kaggle.com/ronitf/heart-disease-uci).

The Dataset Contains following attributes:
  * age : age in years
  * sex : Male or Female (1 = male; 0 = female)
  * cp : Type of chest pain
  * trestbps : Resting Blood Pressure (in mm Hg on admission to the hospital)
  * chol : Serum Cholestoral in mg/dl
  * fbs : Fasting Blood Sugar > 120 mg/dl (1 = True; 0 = False)
  * restecg : Resting Electrocardiographic Results
  * thalach : Maximum Heart Rate achieved
  * exang : Exercise Induced Angina (1 = yes; 0 = no)
  * oldpeak : ST depression induced by exercise relative to rest
  * slope : The slope of the peak exercise ST segment
  * ca : Number of major vessels (0-3) colored by flourosopy
  * thal : 3 = normal; 6 = fixed defect; 7 = reversable defect
  * target : Have Disease or not (1 = yes; 0 = no)
  
Analysis is performed in order to find the features that can explain if a person is suffering from heart disease or not. 

After the EDA, various Classification models have been used to predict whether a person has a disease or not. 
Classification Models used are:
  * Logistic Regression
  * K-Nearest Neighbors (KNN)
  * Gaussian Naive Bayes
  * Support Vector Classifier
  * Decision Tree
  * Random Forest
  * Model using Gradient Boosting
  
Finally, all models have been compared to find the model that best describes the relationship between the given features and the actual dependent variable using various techniques such as `accuracy_score` and `ROC Curve`.
