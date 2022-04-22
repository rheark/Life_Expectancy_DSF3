# World Life Expectancy


## About
This a mini project which we aim to gain more insight regarding the world life expectancy based on WHO national life expectancy dataset we obtained from kaggle (https://www.kaggle.com/datasets/mmattson/who-national-life-expectancy)

## Contributors
- Bong Jia Hui (@bjiah) - Machine Learning
- Celine Tan (@Cttan178) - Data Preparation and Cleaning
- Rhea Kenneth (@rheark) - Exploratory Data Analysis

## Github Folder
### World Life Expectancy Slides
A brief summary of our project. It covers the details on how we derived our problem statement, the insights we obtained through EDA, how the machine learning model help us to answer our problem statment and conclusion we obtained from our work.

### ipynb
Detailed walkthrough of our work on national life expectancy dataset

### Video Presentation 
Presentation on the summary of our work.

### who_life_exp.csv
CSV file of WHO national life expectancy 


## Motivation & Problem Statement
The motivation behind our problem statement is the stereotype that people living in less developed countries tend to have worse health conditions that lead to low life expectancy compared to those in developed countries. Thus, we would like to find out if it is a fact or if it is just a myth that people are exposed to on social media. For example, a stereotype is that most African kids are suffering from diseases due to severe malnutrition. By investigating the factors affecting life expectancy, we try to figure out what possible solutions can be implemented in order to narrow down the gap if there is one. <br />
This lead to our problem statement: <br />
**Does life expectancy inequality really exists and if yes, what are the indicators of such scenarios and are there possible solutions to narrow the inequality?**

## Dataset Description
- This national life expectancy dataset is provided by World Health Organization (WHO) where this dataset was made using Global Health Observatory (GHO) and United Nations Educational Scientific and Culture Organization (UNESCO) information.
- The dataset consists of life expectancy of 183 countries cover the years 2000-2016.
- Some of the variables from UNESCO datasets have overlapped with the variable from GHO datasets and there are significant number of missing values, which is about 70% in those variables. Thus, we decided to remove these variables which are hospitals, une_poverty, une_edu_spend, une_literacy, une_school from UNESCO datasets.
- Following are the data description for the variables we have included:

| Data            | Data Description                                                                                        |
| -------------   | --------------------------------------------------------------------------------------------------------|             
| country         | Country name                                                                                            |
| region          | Global region of country                                                                                |
| year            | year                                                                                                    |
| life_expect     | Life expectancy at birth (years)                                                                        | 
| life_exp60      | Life expectancy at age 60 (years)                                                                       |
| adult_mort_rate | Adult Mortality Rates of both sexes (probability of dying between 15 and 60 years)                      |
| infant_mort_rate| Death rate up to age 1                                                                                  | 
| age1-4_mort_rate| Death rate between ages 1 and 4                                                                         |
| alcohol         | Alcohol, recorded per capita (15+) consumption (in litres of pure alcohol)                              |
| bmi             | Mean BMI (kg/m^2) (18+) (age-standardized estimate)                                                     |
| age5-19thinness | Prevalence of thinness among children and adolescents, BMI < (median - 2 s.d.) (crude estimate) (%)     |
| age5-19obesity  | Prevalence of obesity among children and adolescents, BMI > (median + 2 s.d.) (crude estimate) (%)      |
| hepatitis       | Hepatitis B (HepB) immunization coverage among 1-year-olds (%)                                          |
| measles         | Measles-containing-vaccine first-dose (MCV1) immunization coverage among 1-year-olds (%)                |
| polio           | Polio (Pol3) immunization coverage among 1-year-olds (%)                                                |
| diphtheria      | Diphtheria tetanus toxoid and pertussis (DTP3) immunization coverage among 1-year-olds (%)              |
| basic_water     | Population using at least basic drinking-water services                                                 |
| doctors         | Medical doctors (per 10,000)                                                                            |
| gni_capita      | Gross national income per capita (PPP int. $)                                                           |
| gghe-d          | Domestic general government health expenditure (GGHE-D) as percentage of gross domestic product (GDP)(%)|
| che_gdp         | Current health expenditure (CHE) as percentage of gross domestic product (GDP) (%)                      |
| une_pop         | Population (thousands)                                                                                  |
| une_hiv         | Prevalence of HIV, total (% of population ages 15-49)                                                   | 

## Something New Learnt in This Project
- Filling in null values for time series datas using linear interpolation method instead of using median or mean of the data
- Training model using Random Forest Regressor and Gradient Boosting Regressor 
- Finding the best parameter for the estimators used and reducing the possibility of overfitting by using Grid Search Cross Validation
- Collaborating on GitHub

## References
https://www.kaggle.com/code/mmattson/exploring-cleaning-and-modeling
https://towardsdatascience.com/how-to-interpolate-time-series-data-in-apache-spark-and-python-pandas-part-1-pandas-cff54d76a2ea

