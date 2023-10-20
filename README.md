# HomePricevsIncome
This folder houses the practice exercises and final project from my Career Foundry course. 

**Data Source:**

**Median Home Sales Price**
https://www.kaggle.com/datasets/kylet550/median-home-sale-price?datasetId=513199

This external data was housed in Kaggle and pulled from Zillow. It includes multiple cities from each state, and the median sale price of homes in each city from 2008 to 2019. This data was chosen because it is based on a reputable source of housing data. There are 3881 lines and 146 columns primarily from median sales values separated into month and year information.

I found the states that are part of the southern region and labeled them, then created a pivot table for those states. Then I separated the price data by the first month of each quarter.  From there I stacked the state, quarter, year and price information together.


**Mortgage Interest Rates**
https://www.freddiemac.com/pmms

This data source is pulled from Freddie Mac. This is a well-known company who has tracked this data for decades and also provides home loans to families and individuals. The data consists of 2737 rows and 9 columns of weekly mortgage interest rates from 1971 to September 2023.

I took the Historical weekly interest document and deleted all information before March 2008. Data for April 1971- February 2008 was deleted which removed 1931 lines. I separated the month and year to make a concatenated month and year and then consolidated the month and Year averages into quarterly rates.

**Median Yearly Household Incomes**

I ran the southern state household income from this data for my desired years (2008-2020). I only gathered the yearly incomes for 1/1/20XX for each state.  
https://fred.stlouisfed.org/release/tables?rid=249&eid=259515&od=2008-01-01#  
