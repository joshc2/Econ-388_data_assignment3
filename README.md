# Econ-388_data_assignment3

First off, my process of cleaning the data was super jumbled and I unfortunately did not create a log file explaining all the transformations I did with the data. I was hoping to just give an overview of the general steps that I took.
1. Downloaded covid death counts per county from https://www.nytimes.com/article/coronavirus-county-data-us.html, into file "covid_2020.csv".
2. Downloaded population counts and general county information from https://www.census.gov/data.html, into file "Other_info.csv".
3. Filtered the data in covid data set so I only got total counts at the end of the year, instead of running totals as the counts were set up as running totals over the course of the year.
4. I manually dropped variables, in excel, that I wasn't going to use from the other_info data set to make it easier to work with once I started using the data set in Stata.
5. I merged the 2 data sets together based on county and state.
6. Ran regression on different models to try to get the best one based on R-Squared value and intuition.
