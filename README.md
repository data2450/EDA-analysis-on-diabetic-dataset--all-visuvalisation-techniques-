# Applied some visualisation and basic statistics on the dataset
# benfits of visualisation
#1.helps to find the range of values that each feature takes on.
#2.we can see any unusal outliers that are very different from other points,and that might indicate noise or a missing feature or other problem with the dataset
#3.how likely ML algoritem could do well at predicting the different classes.By seeing how well clustered and well separeted the different type of objects are in feature space
## eda on diabetic dataset
created some basicplots based on the dataset .The dataset was clean, but there were some unusal values like there were enteries 0 in the some columns like Glucose, bloodpressure and bodymassindex .I removed that values because there is no person with 0 glucose level or 0 bp.
Initially there were 768 rows and 9 columns after the removal of "0" enteris in glucose and blood pressure columns
the new dataset has "728" rows and 10 columns 
## add new column based on "BMI" values
added new column called bmi_category
## plots
using the libaries seaborn and matplotlib visualised the data and created a heat map also
## conclusions 
the dataset consisted some unusal outliers and according to coorelation matrix the target column did'nt had very strong relation with the features only the glucose column and BMI
columns had some relation the correlation value for glucose was ".46" and for BMI it was ".29" and ".2" for age column
according to me simple machine learning will not perform good in this data set
