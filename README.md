# Linear Regression Assignment on Bike sharing system

### Problem statement 

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
•	Which variables are significant in predicting the demand for shared bikes.
•	How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

### Business Goal:

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

### This Assignment consist following files 
- Nitin_Nagaich_BoomBikes_Assignment.pnyb
- Linear_Regression_Subjective_Question_Answers.pdf
- README.md
- day.csv
- Data_Dictionary.txt



## 1. data_processing_modeling.pnyb
This file consists of 
-  Data analyses
-  Data visualization
-  Data preparation
-  Model Building
-  Model Evaluation

## 2. Subjective_Q&A.pdf
This pdf consists of following subjective and general questions 
- i) Assignment-based Subjective Questions
-   1. From your analysis of the categorical variables from the dataset, what could you infer about their effect on the dependent variable?
-   2. Why is it important to use drop_first=True during dummy variable creation?
-   3. Looking at the pair-plot among the numerical variables, which one has the highest correlation with the target variable?
-   4. How did you validate the assumptions of Linear Regression after building the model on the training set?
-   5. Based on the final model, which are the top 3 features contributing significantly towards explaining the demand of the shared bikes?
- ii) General Subjective Questions
-   1. Explain the linear regression algorithm in detail. 
-   2. Explain the Anscombe’s quartet in detail. 
-   3. What is Pearson’s R? 
-   4. What is scaling? Why is scaling performed? What is the difference between normalized scaling and standardized scaling? 
-   5. You might have observed that sometimes the value of VIF is infinite. Why does this happen?
-   6. What is a Q-Q plot? Explain the use and importance of a Q-Q plot in linear regression.

## 3. day.csv
This file consists of the dataset to be analysed 

## 4. data_dictionary.txt
This file conatins the detailed information about the dataset

## 5. README.md
The file currently you are reading

## Conclusions

- All the positive coefficients like temp,weathersit_Good&Clear, yrindicate that an increase in these values will lead to an increase - in the value of cnt
- All the negative coefficients such as windspeed, holiday, spring indicate that an increase in these values will lead to an decrease in the value of cnt.
- Temp is the most significant with the largest coefficient.
- September Month has got good impact on number of rides
- holidays as usual has got negative impact on number of rides
### After analysing the model, the comapany should focus on the following features:
- Company should focus on expanding business during September.
- Based on previous data it is expected to have a boom in number of users once situation comes back to normal, compared to 2019.
- There would be less bookings during holidays, they can use these days for maintaing the health condition of bikes
- In winter the business could be expanded
- During the high wind speed which may cause thunder storms, business is shown steep reduction for obvious reasons

## Technologies Used
- [Python](https://www.python.org/) - version 3.11.7
- [Matplotlib](https://matplotlib.org/) - version 3.8.0
- [Numpy](https://numpy.org/) - version 1.26.4
- [Pandas](https://pandas.pydata.org/) - version 2.2.2
- [Seaborn](https://seaborn.pydata.org/) - version 0.12.2
- [Sklearn](https://scikit-learn.org/) - version 1.2.2
- [Statsmodels](https://www.statsmodels.org/) - version 0.14.0

## Contact
Created by [@NitinNag24] - feel free to contact me!