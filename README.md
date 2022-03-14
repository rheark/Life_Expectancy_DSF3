# dsai project
airline price:
https://www.kaggle.com/shubhambathwal/flight-price-prediction?select=Clean_Dataset.csv

movies ratings:
https://www.kaggle.com/danielgrijalvas/movies

Ukraine airspace:
https://www.kaggle.com/rtwillett/ukrainian-airspace

student exam performance:
https://www.kaggle.com/spscientist/students-performance-in-exams

world happiness report:
https://www.kaggle.com/unsdsn/world-happiness?select=2019.csv
https://www.kaggle.com/roshansharma/world-happiness-report

heart disease:
https://www.kaggle.com/meetnagadia/heart-disease

airfare price prediction:
https://www.kaggle.com/vinayshaw/airfare-price-prediction

life expectancy
https://www.kaggle.com/augustus0498/life-expectancy-who


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
