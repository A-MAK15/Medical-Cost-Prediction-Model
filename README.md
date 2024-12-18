## Medical Cost Prediction Model
This model provides insights for the medical prediction cost of an individual based on 
certain demographics that are taken into consideration. These demographics constitutes 
of age, sex, BMI, children, smoker quo, and region. The main goal of this report is to provide 
the study of the relationships between these demographics and how they were scaled to 
be of the same manner and range in order to produce the most quality prediction model 
based on the features provided. The quality of the data model for this medical prediction 
cost will thoroughly be assessed through the findings produced by the model itself.

The dataset was extracted from Kaggle, and there were no null values, meaning that there was no 
need for data imputation. However, there was a single duplicate of which it was dealt with 
by dropping the index that contained that duplicate. Linear regression is the type of data 
model that was utilized to construct the data model in question and the features that 
contained categorical data were converted to numerical data to ensure the best accuracy 
for the model. The numerical values of the features had a big range amongst each other and therefore 
the normalization of the features was also implemented to ensure that all features carry 
weight of the same range when predicting the target.

3.1 Variable Description 
