# Health-Insurance-Premium


The purposes of this exercise is to look into different features to observe their relationship, and plot a multiple linear regression based on several features of individual such as age, physical/family condition and location against their existing medical expense to be used for predicting future medical expenses of individuals that help medical insurance to make decision on charging the premium.

An important part of this project is to look at the Exploratory Data analysis via the Uni-variate Analysis from which we have drawn the following conclusions:

In Fig 1,we can clearly see here that the distribution of expenses is rightly skewed and they show a variation ranging from $ 1121 to $ 63770 in the given plot for a dataset of 1338 current health insurers.

In Fig 2, the age has been put in age bin category for clearer visuals, and from the countplot below one can make out that age group of 20-30 and 40-50 each, make about 30 per cent of the current health insurers. This could be accounted for the fact that todays younger generation is more aware about the importance of purchasing health insurances, whilst for 40-50 age group, they consist of the older generation,that are more prone to health issues henceforth its justified.

In Fig 3, one can see a kind of a balanced dataset as the proportion of males is only 1 per cent higher then that of females.

In Fig 4,out of the total people who had current medical insurance expenses as listed in this dataset, around 42.9 per cent of them have no children. 

In Fig 5, the dataset consisted of an imbalanced ratio of 79.5 per cent people who have current medical insurance expenses to be non-smokers whilst 20.5 per cent were smokers.

In Fig 6, out of all the current health insurers in this dataset, people belonging to the South east region seem to be the highest.

In Fig 7, the countplot suggests that body mass index (BMI)  which have been put into categorical bins for a clearer understanding, show that the obese people are the highest in number to have current medical insurance expenses which makes sense as high BMI is typically associated with higher risk of chronic disease.

This brings us to the the Multi-variate Analysis from which we have drawn these conclusions:

In Fig 8, the plot gives us an undertsanding that people who have 2 and 3 children consisted of having higher medical expenses throughout as compared to having more or less children then that.

In Fig 9,the south east region have the highest medical insurance expenses as people who smoke in the northeast is the highest as compared to thier counterparts.

In Fig 10,for the age-expenses plot we see that smokers tend to pay more than non-smokers but the line slope seems almost the same, implying that the increase of medical expenses with respect to the age is the same for both categories.

In Fig 11, for the bmi-expenses plot  we see that smokers pay more than non-smokers but here the line slope is much higher, resulting in a massive medical expenses increase when the bmi raises.The scatterplot above suggests that body mass index (BMI) and expenses are positively correlated, where customers with higher BMI typically also tend to pay more in insurance premium.

Sailing through the feature engineering which included label encoding categorical variables, and feature scaling to standarise the data we tested the dataset on five models of Random Forest Regressor, Gradient Boosting Regressor, KNeighbours Regressor, Decision Tree Regressor & Linear Regression from which Random Forest Classifier seemed to be the best model with test accuracy of 90 percent and MSE of 3957.90

