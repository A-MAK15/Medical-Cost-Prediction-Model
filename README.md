## Medical Cost Prediction Model
This repository consists of a medical prediction cost model of an individual based on 
certain demographics that are taken into consideration. These demographics constitute 
of age, sex, BMI, children, smoker status, and region. The main goal of this model is to provide 
insights of the relationships between these demographics and how they were scaled to 
be of the same manner and range in order to produce the most quality prediction model 
based on the features provided and to also  support healthcare providers, insurers, and
policymakers in understanding cost drivers and optimizing healthcare resource allocation.

### Features
The dataset was extracted from Kaggle, and there were no null values, meaning that there was no 
need for data imputation. However, there was a single duplicate of which it was dealt with 
by dropping the index that contained that duplicate. Linear regression is the type of data 
model that was utilized to construct the data model in question and the features that 
contained categorical data were converted to numerical data to ensure the best accuracy 
for the model. The numerical values of the features had a big range amongst each other and therefore 
the normalization of the features was also implemented to ensure that all features carry 
weight of the same range when predicting the target.

### Dataset
The dataset consists of health-related demographics which include:-
- **Age**
- **Gender**
- **BMI**
- **Smoking Status**
- **Region**
- **Number of Dependents**
- **Medical Charges**

### Requirements
To run the project, ensure you have the following installed:

- **Python 3.8+**
- **Libraries**
  - **pandas**
  - **numpy**
  - **matplotlib**
  - **seaborn**
  - **scikit-learn**
    
### Results
Below is the evaluation of the model through the analysis of Coefficients, Intercepts and Coefficient of determination (r2_score). Using the Coefficients and intercept, the equation of the model can be deduced as y = 11693.22747931(age) + 235.01433099(sex) + 12454.42219238(bmi) + 2720.2412614(children) - 23893.09923609(smoker) + 884.04026991(region) + 21139.40669513. This is the equation that produces the predicted outputs and its accuracy is 79% as can be seen in the results below:-

- **Coefficients** : [ 11693.22747931,    235.01433099,  12454.42219238 ,  2720.2412614, -23893.09923609,    884.04026991]]
- **Intercepts**     : [21139.40669513]
- **Coefficient of determination (R^2)**	: 0.798

### Future Work
  - Add more health-related features with a goal to improve the model predictions.
  - Explore deep learning techniques for modeling.
  - Integrate the model into a web application for real-time predictions.
