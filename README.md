
   <img src="https://github.com/tvaughn905/Project-1/blob/main/Images/Project%20Banner.png" width=125% height=125%>


# Discovering the Best Places to Retire

Pulling data from the "World Happiness Report" from "kaggle", we will pull the top 5 countries to consider retiring to based on happiness levels considering six factors – economic production, social support, life expectancy, freedom, absence of corruption, and generosity. This project also considers pre-pandimc and post to output a forecast of the top 5 countries that retained their happiness ranks through one of the most difficult historic times.


## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
 - [kaggle](https://www.kaggle.com/datasets/unsdsn/world-happiness?resource=download (for 2015-2019 data years))
 - [World Happiness Report 2022](https://worldhappiness.report/ed/2022/#appendices-and-data)
 - [Make a Weather App in Python | Weather API | Python Project](https://youtu.be/Sz0_2fp27Q0)
 - [openweathermap](https://openweathermap.org/api)


## Questions To Be Answered From the Analysis

#### Question 1: 
What are the average happiness scores across the years and in what 
countries? Happiest, middle and least?

#### Question 2: 
What are the main factors that determine the highest levels of happiness?

#### Question 3: 
Are people happier in the pre or post Covid years?  Why? Why not?

#### Question 4: 
Which countries will be the best places to live in the next decade and why? 

#### Question 5: 
What are the Top 5 places forecasted to retire in 2027? 

#### Question 6: 
How can we track weather for the top 5 places to retire? Can we create a weather app and track weather?



# Contributing Factors Analysis

Economy (GDP)

<img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Economy1.png" width=40% height=40%>  <img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Economy2.png" width=40% height=40%>  

With GDP correlation to happiness, it is pretty strong with high GDP countries tending to be happier. Thsi was no surprise and the it is the #factor when considering overall happiness.
                                



Social


<img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Family_2015-19.png" width=40% height=40%>   <img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Family_2022.png" width=40% height=40%>  

This factor scored higher amongst all factors except GDP for all years. Iceland remains #1 pre and post Pandemic under this factor. Iceland In 2019, they were #1 on the happiness report. Some contributors are; very peaceful, never had an army, children can go places freely and play outside without supervision and it is illegal to pay women less than men. Also, there is a stronger correlation in 2022 than 2015-19 that this factor influences the Happy Score. Iceland, Denmark and Finland remained in the top 5 for scoring highest in this factor




Healthy Life Expectancy

 <img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Health%20(2015-2019).png" width=40% height=40%>  <img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Health%20(2022).png" width=40% height=40%>

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




Freedom

<img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Freedom1.png" width=40% height=40%>  <img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Freedom2.png" width=40% height=40%>

Chart represents the Average Overall Happiness to Freedom factor scores for years 2015-2019. According to the World Happiness Report, the chart represents 
well the shift in Freedom for a rise with eastern european countries and steady trends for northern countries. Looking at the individual years, 2015 through 2019, Freedom is not the highest factor determining happiness. Freedom moves from last place of the six factors to third from last place in 2019. 
(according to World Happiness Report website).




Corruption

<img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Coruption1.png" width=40% height=40%>  <img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Coruption2.png" width=40% height=40%>

Government trust has a slight correlation to happiness and that correlation has gone down in 2022.
With GDP correlation to happiness is pretty strong with high GDP countries tending to be happier.




Generosity

<img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Generosity1.png" width=40% height=40%>  <img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Generosity2.png" width=40% height=40%>

For generosity there is not much correlation to overall happiness, strangely the most generous places are most of the happiest countries and some of the least happiest countries. Most of the countries in between were at or below average generosity.





# Top 5 Countries To Retire To in 2027

Based on the analysis, a forecast was created to output what 5 countries would ideally be the best places to retire in 2027 based on historical data. 

<img src="https://github.com/tvaughn905/Project-1/blob/main/Images/Top5_Countries.PNG" width=50% height=50%>

# Weather as a Factor For 2027 Retirement

Using "OpenWeatherMap" API, we were able to source a code to create a weather app to be able to look up weather in the top 5 countries real time. This tool can be used daily or seasonal just to get a sense of if the weather can influence the decision to retire in one of these countries.

To use the app, an API key has to be generated from "OpenWeatherMap". The code will import the key from a text file that shuold be in the same directory as the code file. The code can be ran using Python in both Jupyter Notebook and Visual Studio. Once code is ran, a pop up window appears and user will have to enter the country in the text field. The code is located in "Weatherpy" directory and the outcome is below. 

 <img src="https://github.com/tvaughn905/Project-1/blob/main/Images/New_Zealand_2-15-23%20at%201013.PNG" width=50% height=50%>





