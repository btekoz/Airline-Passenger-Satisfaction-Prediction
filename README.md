# Airline-Passenger-Satisfaction-Prediction

## *About Dataset*
This project utilizes a dataset retrieved from Kaggle that encompasses information gathered from an airline survey assessing the satisfaction levels of passengers based on several factors. The dataset comprises 25 columns, encompassing passenger demographics like age, gender, and travel class, as well as variables influencing customer satisfaction such as on-board service, cleanliness, seat comfort, and baggage handling. Additionally, the dataset features a column labeled "satisfaction," which delineates the overall satisfaction level of each passenger. This categorical variable can assume two values: "neutral or dissatisfied" and "satisfied." The "satisfaction" feature serves as the label feature, reflecting the overall customer experience based on their ratings for other factors. The dataset comprises 103,904 records for the training set and 25,976 records for the test set.

## *Exploratory Data Analysis*

Exploratory Data Analysis is done for the dataset. The categorical variables are identified. There are 310 missing values in the training dataset and it belongs to the feature of Arrival Delay in minute. There are 83 missing values in the test dataset and it belongs to the feature of Arrival Delay in minute. 


## *Feature Selection*


To identify relationships between features, a correlation map was created. The top ten features were chosen using the Chi-square method, which evaluates the association between categorical variables. The importance of features was assessed employing both wrapper methods and feature permutation importance techniques.
The correlation of categorical variables and numerical variables was checked.

 ## *Models*

 Random Forest
 Logistic Regression
 Support Vector Machine

 ## *Conclusion*
The selected best algorithm (Random Forest) gives the better performance with estimated best parameters.

 
