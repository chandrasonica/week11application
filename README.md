Business Understanding:
We have given 426K data points for the price of used cars. Goal is to identify what features define the value of car. This will help dealer to predict price of used cars.

Data Understanding:
There are few questions I kept in mind while looking the data. 
1. Which columns/features had correlation with price, so we can keep those columns and the one which don’t we can drop those columns
2. Then we need to see, if there are columns which had lots of missing values, and if they did should we drop those columns or fill default values.
3. Which of the columns are categorical and which ones have multiple string values, this will help us in featuriztion during modeling

Data Cleanup
Based on above analysis, I cleaned up, unwanted columns, missing values and converted string values into numeric.

Modeling:
I could see that there was high correlation between price and odometer, year, manufacture,.
I used multiple models to and featurization techniques to come up best model possible.

Conclusion:
I can see that odometer,  year, manufacturer, model has highest value to the prices, It would be good to have more data. 
