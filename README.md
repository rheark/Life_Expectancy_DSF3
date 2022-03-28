# dsai project

1) Compare Malaysia and Singapore:
2) Find correlation for LE against the variables for over 15 years for each country.
3) Filter 5 most significant factors with the highest correlation
4) We use time series to predict the most signi

Time-series 
https://machinelearningmastery.com/time-series-forecasting-supervised-learning/

INSIGHTS:
1. What countries can do to improve life expectancy?
2. Comparing msia and sg with similar geographic location but why diff LE?
3. 
METHOD 1: GO GLOBAL!  --- FIND THE 5 MOST SIGNIFICANT FACTOR
- No time series-normal regression/classfication -> use all the variables + correlation
- each row(ignore time) treat as a record and do regression on it
- outcome: equation to predict the life expectancy 
- visualisation: time-series plotting

METHOD 2:
- use time-series
1) (Find correlation for LE against the variables for over 15 years for each country.
2) Filter 5 most significant factors with the highest correlation against LE) - METHOD 1


3) Using the 5 factors, we find the trend over the years for the country we trying to predict (time series) and then we need to predct the 4th year life expectancy using the trend and correlation (Sliding window -> 3 years as input + 1 output)
4) Predict the change in life expectancy - increase, decrease, remain the same

[led.csv](https://github.com/rheark/helloworld/files/8249369/led.csv)



Deadline: FRIDAY 1/4/22
UPDATED:
1) alcohol:
- Insight: alcohol boost life expectancy (+ve corr): alcohol in moderation may be beneficial  -- EDA
- for those >10 just not fill: justify inaccuracy, bias
- else will fill with interpolation:  justify although not really accurate cos is at the end, but it is better than filling with artificial data(mode, median, mean) from other countries that doesn't follow a trend and have great variations
- scatterplot b/w alcohol and le --EDA

2) hepatitis:
- for those >10 just not fill: justify inaccuracy, bias
- else will fill with interpolation:  justify although not really accurate cos is at the end, but it is better than filling with artificial data(mode, median, mean) from other countries that doesn't follow a trend and have great variations
- go website and saw that it has a lot of null values

3) Anomaly detection using boxplot and scatterplot:
hopefully there is very little outliers, then we can justify and say the outliers is not a big issue so we not dropping
else, if there's a lot of outliers then can drop the whole outlier row then try again with ML

MACHINE LEARNING
- separate dataset with diff response var - 1 on life_expect and 1 on life_exp60 (using EDA justify that it is actually highly related)
- use random_state to set the train_test random split thing to fix the train and test datasets 
- use the same train test combi for comparing the 2 models
- linear regression don't need grid search cv

