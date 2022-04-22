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

                                             
                                             
Label	Count
18.70 - 26.83	15
26.83 - 34.96	38
34.96 - 43.09	106
43.09 - 51.22	141
51.22 - 59.35	186
59.35 - 67.48	199
67.48 - 75.61	160
75.61 - 83.74	246
83.74 - 91.87	434
91.87 - 100.00	1,554
18.7
100






## Conclusion

## References
https://www.kaggle.com/code/mmattson/exploring-cleaning-and-modeling


