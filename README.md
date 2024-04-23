# Heathcare Insurance Cost Analysis

## Power BI Charts
Link: 


## Table of Contents
* [Power BI Charts](#Power-BI-Charts)
* [Motivation](#motivation)
* [Questions](#questions)
* [Normalizing the Data](#normaling-the-data)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Sources](#sources)
* [Conclusion](#conclusion)

## Motivation:
After working in the healthcare field for a number of years and seeing the increase in healthcare premiums go up. Looking at my paystub every two weeks to see how much of my income goes to healthcare insurance and thinking that's a nice car payment. I wanted to look further into the cost and find data that may show a reason why.

Factors include:
- Inflation
- Life Expectancy
- Unemployment


## Questions:
1) How does Single coverage compare to Family coverage annual cost?**
2) What is the percent change in single coverage vs family coverage? And dollar change?**
3) What year have the highest and lowest increase in cost in dollars and percentage?
4) What percent does the cost of single coverage and family coverage healthcare insurance make up of the average US household income?**
5) How does the change in cost of healthcare insurance compare to the change in average US household income? 
6) How does inflation % compare to the cost of healthcare insurance?**
7) Is there correlation between annual healthcare cost and the life expectancy, unemployment rate, inflation rate, or US household income?


## Normalizing the Data
I used multiple dataset based on the governments healthcare spending per person from 1960 to 2022. And also data sets for Employer-Sponsored health insurance the ranged from 1999 to 2023 for single coverage and family coverage. 
I also wanted to bring in the life expectancy to see how it would correlate with the price/cost of healthcare insurance.


## Problems and Hurdles
Trying to find historical data on the cost of healthcare insurance, life expectancy, single and family coverage breakdown, and average household income. 
Also trying to choose the many versions of how household incomes are calculated(went with the one that show dollars in that year vs 2022 dollars). Cleaning some of the infomation in python also took some time.

## Technologies Used
1) Excel - for pulling in some of the data and putting in csv format
2) Python / Pandas - for exploration, normalizing and aggregation of the dataset
3) Power BI - for creating interactive charts
4) PowerPoint - for introduction, history, motivation, charts and summary of Project
5) Git - for version control


## Data Sources
To answer the above questions I used the following sources to collect datasets for my analysis

1) KFF Kaiser Family Foundation- Single and Family Coverage.
https://www.kff.org/interactive/premiums-and-worker-contributions-among-workers-covered-by-employer-sponsored-coverage/

2) CMS.gov - Government exp
https://www.cms.gov/data-research/statistics-trends-and-reports/national-health-expenditure-data/historical

3) macrotrends - US Life Expectancy 
<a href='https://www.macrotrends.net/global-metrics/countries/USA/united-states/life-expectancy'>U.S. Life Expectancy 1950-2024</a>

4) HealthData.gov - US Life Expectancy
https://healthdata.gov/dataset/NCHS-Death-rates-and-life-expectancy-at-birth/4r8i-dqgb/about_data

5) OECD.Stat (Organization for economic co-operation and development)
https://data.oecd.org/unemp/unemployment-rate.htm

6) macrotrends - US inflation rate
<a href='https://www.macrotrends.net/global-metrics/countries/USA/united-states/inflation-rate-cpi'>U.S. Inflation Rate 1960-2024</a>

7) macrotrends - US unemployment
<a href='https://www.macrotrends.net/global-metrics/countries/USA/united-states/unemployment-rate'>U.S. Unemployment Rate 1991-2024</a>

## Conclusion
The data analysis shows that the trend that cost of healthcare insurance continue to go up every year, but the percentage of that increase has slowed. It also shows that there is correlation with average life expectancy and average household income, but not much correlation with the unemployment rate and inflation rate. 