# **Exploring World Happiness**

### Hannah Allen, Chris Partee, Grace Olson
### GT Bootcamp: Project #1
### May 2, 2022

## **World Happiness Report Background:**
The World Happiness Report is a publication released every year detailing national happiness rankings for respondent countries. The report measures happiness using six indicators--GDP, Social Support, Life Expectancy, Freedom of Choice, Generosity, and Perception of Corruption--on a scale from 0-2.

## **World Happiness Report 2022: Initial Analysis**
In reviewing the World Happiness Report for 2022, we observed the total data set by comparing the top five countries with the highest happiness scores (Finland, Denmark, Iceland, Switzerland, and The Netherlands) to the bottom five countries with the lowest happiness scores (Botswana, Rwanda, Zimbabwe, Lebanon and Afghanistan). To visually compare these countries, we created a compound bar chart that compares the six variables used to determine happiness outlined above; the red dotted line on the bar chart separates our two country groupings. 

There is a clear difference between the top five and bottom five countries in 2022. Specifically:
* GDP (yellow bar): There is an obvious downward trend in GDP between the top five and bottom five countries- Switzerland had the highest score of 2.00. The other top 5 countries had scores between 1.80-1.95. Afghanistan had the lowest GDP score of 0.75. The other bottom 5 ranking countries had GDP scores between 0.75-1.50.

* Social Support (pink bar): Social Support followed a similar downward trend as GDP, declining with rank. However, the top five countries all had scores around 1.25 while the bottom five countries all had scores under 0.75. Rwanda and Afghanistan ranked even lower, with scores below 0.25. 

* Life Expectancy (green bar): The top five countries scored similar again for Life Expectancy, around the 0.75 mark. However, the bottom countries varied in scores. Lebanon had a score over 0.60, Rwanda scored around 0.40, while Botswana, Zimbabwe, and Afghanistan all had scores around 0.25. This variation among the bottom five countries was surprising and thus encouraged us to look at this indicator further in our analysis. 

* Freedom of Choice (light blue bar): The top five countries scored similar again for Freedom of Choice, all between 0.60-0.70. However, the bottom five countries also varied in scores again. Rwanda and Botswana had a score between 0.50-0.60. Whereas, Zimbabwe, Lebanon and Afghanistan all had scores between 0.00- 0.30. 

* Generosity (orange bar): The top and bottom five countries all scored below 0.25 for Generosity. Iceland and The Netherlands both had scores closest to 0.25. However, Finland had a score of 0.11. Botswana had a score of 0.01 compared to Rwanda which scored approximately 0.19. 

* Perception of Corruption (purple bar): Lastly, the Perception of Corruption varied between the top 5 countries and the bottom 5 countries. Finland, Denmark, and Rwanda all had scores close to 0.50. The Netherlands had a score close to 0.40. However, Iceland, Botswana, Zimbabwe, Lebanon, and Afghanistan all scored below 0.20. 

## **World Happiness Overtime (2015-2022):**
* We utilized gmaps to create a choropleth map that observes happiness over time. Generally, all countries represented in our dataset have declined in happiness, shown by a country's color getting darker over time. A marked difference in color was observed in 2020, likely attributable to the COVID-10 pandemic. A notable country to observe on the map is Canada, whose rank dropped from the top five to below 10 over our timeframe (2015-2022). 

* We also created a line plot of average happiness over time. Interestingly, although the general impression from the choropleth map is that countries get less happy over time, an analysis of average happiness shows that world happiness actually increases over time, with only a slight decline recently in 2021. Specifically, average happiness rose from 5.525 in 2015 to 5.675 in 2020 and continued to rise to 5.700 in 2021. It has since declined to 5.675 this year. 


## **Our Questions:**
After observing happiness over time, taking a deeper look at the most recent year's data, and doing some outside research, our team agreed on four happiness indicators (average income, weather, life expectancy, and alcohol consumption) to analyze further. We came up with four questions to drive our analysis: 
* Question 1: Are countries with higher average incomes happier?
* Question 2: Does the weather of a country (avg. sunshine) influence happiness? 
* Question 3: Are countries with longer life expectancies happier?
* Question 4: Does alcohol consumption influence happiness?

For each question, we created a scatter plot to show the correlation between happiness and the happiness indicator selected. We also created a bar plot to show where the top five and bottom five countries for that specific indicator ranked relative to average happiness and max happiness for the year. 

### **Question 1: Are countries with higher average incomes happier?**
There is a strong positive correlation between average income and happiness (r-square value of 0.698): as income rises, happiness scores increase from close to 3 points to between 7 and 8 points. The top five highest average income countries (Switzerland, The USA, Norway, Canada, and Australia) all had happiness scores close to or above 7 points. The countries with the lowest average income (Togo, Mozambique, Mali, Uzbekistan, and Malawi) generally all had scores between 4 and 5 points, with the exception of Uzbekistan whose happiness score was closer to 6 points. Outside factors potentially impacting average income and leading to Uzbekistan as an exception could be economic growth, inflation, population growth, etc. 

### **Question 2: Does the weather of a country (avg. sunshine) influence happiness?**
There is a weak negative correlation between average sunshine hours per year and happiness (r-square value of 0.294): as the number of sunshine hours per year increases, happiness scores appear to decrease. This relationship is supported in our bar plot showing the happiness scores of the top five sunniest countries (Namibia, Egypt, Cyprus, Israel, and Algeria) vs. the top five least sunny countries (Belgium, United Kingdom, Ireland, Norway, and Iceland). The least sunny countries all had happiness scores between 7 and 8 points. Three out of the top five sunniest countries had happiness scores below average happiness, while the remaining two were just slightly above. Outside factors potentially impacting a country's weather and leading to our two exception countries could be cloudiness, humidity, rainfall, temperature, etc. 

### **Question 3: Are countries with longer life expectancies happier?**
There is a positive correlation between average life expectancy and happiness (r-square value of 0.608): as life expectancy increases, happiness scores generally increase. This relationship is also visible in our bar chart showing the top five countries with the highest life expectancy (Japan, Korea, Switzerland, Cyprus, and Israel) and the bottom five countries with the lowest life expectancy (Zambia, Nigeria, Guinea, Zimbabwe, and Mozambique). The countries with the highest life expectancy all scored above average happiness, between 6 and 7.5 points. The countries with the lowest life expectancy scores all scored well below average happiness, between 3 and 5 points. Outside factors potentially impacting a country's average life expectancy and that may explain some of the variation in our scatter plot is country population, pollution levels, access to healthcare, violence rates, and war.

### **Question 4: Does alcohol consumption influence happiness?**
There is a very weak positive correlation between alcohol consumption per year and happiness score (r-square value of 0.309): it is hard to say that as alcohol consumption increases, happiness also increases. There is a general upward trend in happiness scores for countries that reported higher alcohol consumption per year, however, there is significant variation. In our bar plot, we compared the happiness scores of the heaviest drinking countries (Latvia, Moldova, Germany, Lithuania, and Ireland) to the least heavy drinking countries (Morocco, Iraq, Pakistan, Egypt, and Bangladesh. While the bar plot shows that all heavy drinking countries are above average happiness and all least heavy drinking countries are below average happiness, there are outside factors that may impact a country's average alcohol consumption not considered in our dataset, including religious reasons or society acceptance. 

### **Conclusions + Analysis Limitations:**

In reviewing the four happiness indicators we selected, average income and life expectancy had the highest r-square values (and thus the least varition with happiness), indicating the strongest relationship with happiness. Between average income and life expectancy, average income had the highest r-square and the least variation, thus we would conclude that, of the happiness indicators we selected, average income is the best indicator of happiness. However, one limitation of our analysis is that without the ability to conduct a multiple regression, we were not able to statistically prove that average income is the best indicator of happiness. Thus, we relied on r-square values to come to our final conclusion. 

Other limitations of our analysis include:
* The World Happiness Report dataset only comes from countries willing to participate.
* We were unable to code the gmaps to to be interactive to cycle through the years.
* In our attempt to compare happiness to weather, it was difficult to find a complete historical dataset to incorporate all weather factors that can affect mood (rainfall, cloudiness, temperature (historical weather APIs cost money), etc.)
* Lack of datasets that could look further into the impact of corruption.
* Lack of datasets having the same variables to further make comparisons: (ex. Male vs. Female)

###  **Further Considerations:**
* Research other happiness indicators: Job satisfaction, Population density, Rural vs. Urban living, Loneliness, Disease burden, Education level , Type of Government.

* Compare: Cost of living to happiness; Healthy habits to life expectancy, then to happiness; Other weather factors to happiness, Social drinking vs. Problem drinking to happiness.

### **Data sets Used:**
* World happiness dataset 2022: https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2022
* World happiness dataset 2015-2022: https://www.kaggle.com/datasets/mathurinache/world-happiness-report?select=2017.csv
* Median Income by Country: https://worldpopulationreview.com/country-rankings/median-income-by-country
* Sunshine Hours: https://www.kaggle.com/datasets/prasertk/sunshine-duration-by-city
* Alcohol Consumption by Country: https://worldpopulationreview.com/country-rankings/alcohol-consumption-by-country


### **Other Resources:**
* (1) https://www.forbes.com/sites/alexledsom/2021/02/07/new-study-shows-that-more-money-buys-more-happiness/?sh=25f35e9970d5
* (2) https://www.psychologytoday.com/us/blog/the-social-self/201604/does-warmer-weather-really-make-you-happier
* (3) https://www.science.org/content/article/happiness-associated-longer-life#:~:text=Happy%20people%20don't%20just,to%20ask%20them%20about%20it
* (4) https://pubmed.ncbi.nlm.nih.gov/27043371/
