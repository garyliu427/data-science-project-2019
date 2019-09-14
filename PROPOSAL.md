# Project Proposal

#### Data Science Project Proposal Practical 06 (Friday 4pm) Group E:

Michael Payne (45133956), Vincent Xu (44937113) Xiaotian Liu (44410573), Tianhao Tang(44030754)

### Summary

The 2019 Australian Federal election was held on Saturday the 18th of may, 2019 to elect the members of the 46th Parliament of Australia. Opinion polls of the 2019 election very clearly showed a large Labor lead throughout the entire polling process for Two party preferred vote, however in reality Liberal/National coalition held control of the government. Using census data from the Australian census could this result have been predicted based on the results of districts in previous elections? Our project aims to take previous results of the census and Australian elections to attempt to predict what the results might have looked like as a result of socioeconomic factors from previous years of the Census.

### Project Goal

The primary Goal of our project is to train our model to predict the results of the electorates for the 2019 election based on the Census results for 2016, using the 2016 election as test data, and then compare our result with the actual results of the election to determine the sufficiency of the Census demographic data. Our data can be displayed easily using a confusion matrix for predicted preferred candidate vs real results.

### Data Source and background

The Australian Bureau of Statistics contains vast amounts of statistical data that can be manipulated to produce information based on relevant indicators such as demographic, economic indicators (such as average weekly income) and other important factors relevant to determining someone's vote. Our chosen data set contains the following indicators:

* Weekly Income
* Ancestry 1st Response
* Education Status
* Number of Children 
* Average Age of Electorate

Our Data from the Australian Bureau of Statistics is 5 .csv files for all of these predictors, which can then be manipulated to determine averages. This will then leave us with a dataframe of 49 rows (each electorate in New South Wales) with 5 columns, containing socioeconomic information for each electorate.

The Australian Electoral Commission contains all historical data for Australian elections. We will be using the Historical two candidate preferred votes by party by division file to train our model. This data contains 94 rows and 9 columns containing information of two candidate preferred votes.

### Data Manipulation

We must calculate approximate averages for each electorate that allow us to plug in data to determine a response. In this case we must: 

1. use the responses to weekly income to determine an equally approximate weekly income for each district. 

2. use the responses to ancestry to determine what percent of the population belongs to the major reported ethnic response of the state. 
3. determine average age of each districts response.
4. use responses to education level to determine what percent of the population is high school or even university educated. 
5. determine average number of children of respondents in the area.

Techniques we plan to employ in this project We expect that our results will come from machine learning techniques such as K Nearest neighbour and logistic regression.

### Project Plan

Week 8: Cleaning and preparing the appropriate data sets for use

Week 10: Prepare our model and apply it to our data

Week 12: use confusion matrix to determine the fit of our data

Week 13: Prepare our report presentation