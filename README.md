# Handling-Nan--SubML_Method
For this i am using famous Titanic Data set.
In train Age column more that 177 values are missing which is account 20% of the total data point.
Step1 -Created another train and predict data set  from the existing Training data
       First data set contain all the points with valid Age values (Data_with_Age)
       Second data set contains all the points with Null Age Value (Data_without_age)
Step2 -Create a model using Data_with_Age.
       Train a model with Age as target and remaining columns including survival, as features
Step3 -Use this trained model to predict the missing age values in original training Data.
