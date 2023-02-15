
   <img src="https://github.com/tvaughn905/Project-1/blob/main/Images/Project%20Banner.png" width=125% height=125%>


# Discovering the Best Places to Retire

Pulling data from the "World Happiness Report" from "kaggle", we will pull the top 5 countries to consider retiring to based on happiness levels considering six factors – economic production, social support, life expectancy, freedom, absence of corruption, and generosity. This project also considers pre-pandimc and post to output a forecast of the top 5 countries that retained their happiness ranks through one of the most difficult historic times.


## Acknowledgements

 - [Awesome Readme Templates](https://awesomeopensource.com/project/elangosundar/awesome-README-templates)
 - [Awesome README](https://github.com/matiassingers/awesome-readme)
 - [How to write a Good readme](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
 - [kaggle](https://www.kaggle.com/datasets/unsdsn/world-happiness?resource=download (for 2015-2019 data years))


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
Top 10? places to retire in 2023? Forecasted within the next 10 years? By 
2033?

#### Question 6: 
Tie in weather API for retirement places.



# Contributing Factors Analysis

Economy


<img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Economy1.png" width=40% height=40%>  <img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Economy2.png" width=40% height=40%>  

                                



Social


<img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Family_2015-19.png" width=40% height=40%>   <img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Family_2022.png" width=40% height=40%>  






Life Expectancy

 <img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Health%20(2015-2019).png" width=40% height=40%>  <img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Health%20(2022).png" width=40% height=40%>






Freedom

<img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Freedom1.png" width=40% height=40%>  <img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Freedom2.png" width=40% height=40%>


Corruption

<img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Coruption1.png" width=40% height=40%>  <img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Coruption2.png" width=40% height=40%>


Generosity

<img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Generosity1.png" width=40% height=40%>  <img src="https://github.com/tvaughn905/Project-1/blob/main/Figure_File/Generosity2.png" width=40% height=40%>



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







