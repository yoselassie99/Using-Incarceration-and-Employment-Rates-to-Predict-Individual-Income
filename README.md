# Using Incarceration and Employment Rates to Predict Individual Income

## Background
It is often believed that children are simply a product of their environment, as their surroundings shape the adult they later become. Whether it be in or out of the home, the impressionable nature of children is well documented in social psychology circles. 







## Business Question
How does neighborhood incarceration and employment rate predict household income?

## Data Source
https://github.com/yoselassie99/Using-Incarceration-and-Employment-Rates-to-Predict-Individual-Income/blob/main/Opportunity%20Atlas%20Data%202.xlsx
All data was obtained from the Opportunity Atlas Database. Data was stratified by parent's income group (high, middle, low) to determine the role incarceration and employment rates have in predicting household income.


## Data Analysis
To begin the analysis, I thought it would be interesting to compare income, incarceration rates and employment rates between parents income groups just to determine a trend between the three income groups (high, middle, low).

![alt text](https://github.com/yoselassie99/Using-Incarceration-and-Employment-Rates-to-Predict-Individual-Income/blob/main/IncarcerationLinearRegression.png)

![alt text](https://github.com/yoselassie99/Using-Incarceration-and-Employment-Rates-to-Predict-Individual-Income/blob/main/EmploymentLinearRegression.png)

![alt text](https://github.com/yoselassie99/Using-Incarceration-and-Employment-Rates-to-Predict-Individual-Income/blob/main/HouseholdLinearRegression.png)

The simple linear regressions show a pattern of high employment rate and household income being associated to children of parents who were in the highest income bracket, followed by middle and low income brackets. The opposite is true for incarceration rates, as children whose parents are in the lowest bracket live in some of the most crime infested neighborhoods in DC.

Next, I decided to analyze how incarceration and employment rate, as variables, predict household income (the outcome) in each stratified group. The reason why I decided to investigate by stratified groups instead of one giant sample size was to measure social mobility, primarily for the children of parents in the low and middle income bracket. 

### High Income Bracket
![alt text](https://github.com/yoselassie99/Using-Incarceration-and-Employment-Rates-to-Predict-Individual-Income/blob/main/RegressionHighBracket.png)

### Middle Income Bracket
![alt text](https://github.com/yoselassie99/Using-Incarceration-and-Employment-Rates-to-Predict-Individual-Income/blob/main/RegressionMiddleBracket.png)

### Low Income Bracket
![alt text](https://github.com/yoselassie99/Using-Incarceration-and-Employment-Rates-to-Predict-Individual-Income/blob/main/RegressionLowBracket.png)

In all three multiple regressions, the p<0.05 which means the data is statistically significant (employment rate and incarceration rate influences household income). Incarceration rate coefficient is positive in all three groups, which is odd since crime does not positively correlate with increased income. 


# Summary
After constructing multiple regressions for each stratified group, we can concluded incarceration and employment rates help predict household income. It's interesting to see the coefficients for incarceration rate are positive, as high crime neighborhoods are historically associated with poverty. Another thing important thing to point out are the high standard errors. These large standard errors can be reasoned through social mobility, as individuals are capable of moving between different socioeconomic groups regardless of their environment. 
