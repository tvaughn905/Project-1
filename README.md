Project Title
Project Description
# What was the motivation
# Why did we build this project
# What problem does it solve
# What did we learn
# What makes the project standout?

Freedom component: Kathryn Kessler

Freedom component: Kathryn Kessler

Title: (whatever name the group came up with).
Background: Used data from: World Happiness website found on Kaggle. 
https://www.kaggle.com/datasets/unsdsn/world-happiness?resource=download (for 2015-2019 data years).
And
https://worldhappiness.report/ed/2022/#appendices-and-data (for 2022 data).
** All members of the group used the 2015-2019 and 2022 .csv files (downloaded).
I focused on the columns for measuring the amount of Freedom a country has had in correlation to their happiness levels. 
Description of Data Exploration:  I compiled the “Freedom” component/factor of the 2015, 2016, 2017, 2018 and 2019 data, cross-checking it with countries listed in the data set who have a recorded “level” of happiness.  Also did cross-checking on the 2022 yearly report of happiness data to freedom “levels” as well. 
Data Analysis:  I created dataframes and used a “clean” version of the merged .csv files that was jointly used by all members of the team.  Duplicate and “NaN” data was dropped out of the dataset.  
I created a dataframe of the “clean” combined .csv file, gathering the “Freedom 2015, 2016, 2017, 2018, 2019 and 2022” data columns.  I created a second dataframe gathering the columns marked for “Happiness Score” for the years 2015, 2016, 2017, 2018, 2019 and 2022; also grabbing the “Country” names. Next, I created data loops going through country by country, year by year, a listing of the happiest freedom level countries, and also the worst of bottom of the list. I captured the percentage rates. I then created bar charts for each calendar year, showing the trend of “Happiness” and “Freedom” scores broken down by year, visually.  Next, I created scatter plots with the same data and included the regression line for each; again, year by year. Freedom versus Overall Happiness scores. Next, I created a second .ipnyb file where the original same combined, “cleaned” .csv data set was used, for the years (2015-2019), as one combined unit.  I found the average, (a/k/a “mean” scores for both “x”=Overall Happiness and “y”=”Average Freedom” scores. I created a scatter plot, showing the combined averages of “Overall Happiness” to “Freedom” scores and how they appear with a regressions line. A second scatter plot was also created, in a similar manner, but just with the 2022 data. I noticed the same 5 top countries kept appearing as the “Happiest for Freedom” of the bunch. They are (in order): Switzerland, Iceland, Denmark, Norway and Canada. 
Limitations of the dataset for future consideration:  I think this should be a combined group response.
Data source: I think this should be a combined group response as well. 

HealthAnalysis Jupyter Notebook
README.md by Sheila LaRoue
dated 2/14/2023
import dependencies
define variables and lists for the years covered for analyzation and the year groups tested
list the categories (factors) which are part of the study
pull in the merged and cleaned files which originally were separate years, 2015, 2016, 2017, 2018, 2019, and 2022
confirm lack of NaN values before processing
made a DataFrame with simply the Health Score data to review the data
made a DataFrame with simply the Overall Happiness Score data to review the data
review the top 5 ranked countries from the averages over the Health Scores from 2015 through 2019
review the top 5 ranked countries from the averages over the Health Scores from 2022
output just the countries with complete happiness scores throught the years for planned api processing
loop through the Health Happiness data for the data sets for 2015-2019 and for 2022 to created scatter plots of the Health vs Overall Happiness Scores
in this loop the r-value, pvalue, and slope intercept is calculated and printed
last , loop through the Overall Happiness Research, find the top 5 Overall Happy countries for the data sets for 2015-2019 and for 2022







Credits