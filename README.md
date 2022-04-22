# World Life Expectancy

## Contributors
- Bong Jia Hui - @bjiah
- Celine Tan - @Cttan178
- Rhea Kenneth - @rheark

## About
This a mini project which we aim to gain more insight regarding the world life expectancy based on WHO national life expectancy dataset we obtained from kaggle (https://www.kaggle.com/datasets/mmattson/who-national-life-expectancy)

## Motivation & Problem Statement


## Dataset Description
- This national life expectancy dataset is provided by World Health Organization (WHO) where this dataset was made using Global Health Observatory (GHO) and United Nations Educational Scientific and Culture Organization (UNESCO) information.
- The dataset consists of life expectancy of 183 countries cover the years 2000-2016.
- Some of the variables from UNESCO datasets have overlapped with the variable from GHO datasets and there are significant number of missing values, which is about 80% in those variables. Thus, we decided to remove these variables which are hospitals, une_poverty, une_edu_spend, une_literacy, une_school from UNESCO datasets.
- Following are the data description for the variables we have included:
| Data            | Data Description                                                                                        |
| -------------   | --------------------------------------------------------------------------------------------------------|             
| country         | Country name                                                                                            |
| country_code    | Three letter country identifier                                                                         |
| region          | Global region of country                                                                                |
| year            | year                                                                                                    |
| life_expect     | Life expectancy at birth (years)                                                                        | 
| life_exp60      | Life expectancy at age 60 (years)                                                                       |
| adult_mortality | Adult Mortality Rates of both sexes (probability of dying between 15 and 60 years per 1000 population)  |
| infant_mort     | Death rate up to age 1                                                                                  | 
| age1-4mort      | Death rate between ages 1 and 4                                                                         |
| alcohol         | Alcohol, recorded per capita (15+) consumption (in litres of pure alcohol)                              |
| bmi             | Mean BMI (kg/m^2) (18+) (age-standardized estimate)                                                     |
| age5-19thinness | Prevalence of thinness among children and adolescents, BMI < (median - 2 s.d.) (crude estimate) (%)     |


## Conclusion

## References
https://www.kaggle.com/code/mmattson/exploring-cleaning-and-modeling


