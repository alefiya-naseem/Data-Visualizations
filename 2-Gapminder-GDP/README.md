# 
DataVizHw2

Data Visualization Homework 2

## Overview
This homework asks you to visualize data from the Gapminder Foundation [dataset.](https://www.gapminder.org)
Download the full Gapminder dataset from the Open Numbers Github repository:
* [Link to Open Numbers Github repository](https://github.com/open-numbers/ddf–gapminder–systema_globalis)

### Problem 1

See post on [Piazza](https://piazza.com/class/k05u5i0wc3w540?cid=229)

### Problem 2
Choose and critique one of the visualization by one of your fellow classmates for HW 1 Problem 2 (distribution of income across countries and continents over time). Include a link to the original. Describe the visualization and how it is similar and/or different from yours. Is it easy to interpret? Does it effectively visualize what is being asked? Why or why not?

For this question, I chose to critique the following plot:

[Problem 2 link](https://github.com/wzxqwe/DataVis-HW1/blob/master/5500HW1.ipynb)

This visualization is very intriguing as it is very different from that of my own. There are a couple of  differences that are easily noticeable. The first difference is that this user only showed one static plot comparing the GDP among countries over time. This is interesting in itself as this greatly reduces the amount of information the plot represents as the question does specify to visualize the distribution of income across countries and continents. Though this plot does visualize how the GDP/capita trend has changed over the years across the globe, it misses out on the finer details of the geographic locations which is available in the data. Though it is easy to interpret, it misses out on the distribution of GDP/capita across regions which might be able to answer more detailed questions like which area has seen more increase in income over the years than others? Are they, the developed countries or developing countries?

I do think the graph provides a very easy and sufficient interpretation when you want to see how the GDP/capita trends have changed over the years for the world as a whole. It doesn't provide the finer details of how individual continents or countries have been performing. A map alongwith a color gradient could provide a much better interpretation of how the increase or decrease of income is distributed over a region.

### Problem 3
Choose and critique one of the visualization by one of your fellow classmates for HW 1 Problem 2 (relationship between income, life expectancy, and child mortality over time). Include a link to the original. Describe the visualization and how it is similar and/or different from yours. Is it easy to interpret? Does it
effectively visualize what is being asked? Why or why not?


For this question, I chose to critique the following plot:

[Problem 3 link](https://github.com/stiangithub/DS5500-HW1#problem-3)

The user chose to visaulize the relationship between income, life expectancy and child mortality over time in three different plots. The plots become easy to interpret as you can see the relationship between all the different variables with time. It becomes difficult to visualize the relationship of all the variables over time together. The different aspects of plot like color, size and shape can be used to represent all the variables together on a plot.  

Althought, I liked how the user has made the breakdown of period into 3 parts: before 1900, 1900-1950, after 1950. The users plots are simple but yet informative and conclusive. The only other change I would suggest would be adding titles to the plots.

### Problem 4

Choose and fit one or more models to quantify the relationship betweem income (GDP per capita) and life expectancy over time. Justify your choice of model and comment on its appropriateness. (You are not required to handle the autocorrelation of time series, but should comment on how this impacts your analysis.) Visualize the model(s) and comment on what they tell you about the relationship between income and life expectancy over time.

![](https://github.com/alefiya-naseem/Data-Visualizations/blob/master/2-Gapminder-GDP/images/hw2_prob4_image1.png)
*GDP/capita over time across world regions*

![](https://github.com/alefiya-naseem/Data-Visualizations/blob/master/2-Gapminder-GDP/images/hw2_prob4_image2.png)
*Life expectancy over time across world regions*

Life expectancy – which measures the average age of death of a population – is one of the key measures of a population’s health.

Estimates suggest that in a pre-modern, poor world, life expectancy was around 30 years in all regions of the world.

Life expectancy has increased rapidly since the Age of Enlightenment. In the early 19th century, life expectancy started to increase in the early industrialized countries while it stayed low in the rest of the world. This led to a very high inequality in how health was distributed across the world. Good health in the rich countries and persistently bad health in those countries that remained poor. Over the last decades this global inequality decreased. No country in the world has a lower life expectancy than the countries with the highest life expectancy in 1800. Many countries that not long ago were suffering from bad health are catching up rapidly.

Since 1900 the global average life expectancy has more than doubled and is now above 70 years. The inequality of life expectancy is still very large across and within countries. in 2019 the country with the lowest life expectancy is the Central African Republic with 53 years, in Japan life expectancy is 30 years longer.

In 1950 the life expectancy of all countries was higher than in 1800 and the richer countries in Europe and North America had life expectancies over 60 years – over the course of modernization and industrialization the health of the population improved dramatically. But half of the world’s population – look at India and China – made only little progress. Therefore the world in 1950 was highly unequal in living standards – clearly devided between developed countries and developing countries.
This division is ending: Look at the change between 1950 and 2012! Now it is the former developing countries – the countries that were worst off in 1950 – that achieved the fastest progress. While some countries (mostly in Africa) are lacking behind. But many of the former developing countries have caught up and we achieved a dramatic reduction of global health inequality.

The world developed from equally poor health in 1800 to great inequality in 1950 and back to more equality today – but equality on a much higher level.

There's a clear linear relationship just by observing the data. So we'll first plot a linear regression to check fit (even though this seems naive as theres a temporal correlation here too). Let's treat this as a baseline. This is the result we get:

![](https://github.com/alefiya-naseem/Data-Visualizations/blob/master/2-Gapminder-GDP/images/hw2_prob4_image3.png)
*Predicted GDP versus True GDP*

We then fit a model using an algorithm that takes into account the temporal relationship. This is the result we get:

![](https://github.com/alefiya-naseem/Data-Visualizations/blob/master/2-Gapminder-GDP/images/hw2_prob4_image4.png)
*Predicted GDP versus True GDP*

##### What affects improvements in in life expectancy?

Knowledge, science and technology are the keys to any coherent explanation. Mortality in England began to decline in the wake of the Enlightenment, directly through the application to health of new ideas about personal health and public administration, and indirectly through increased productivity that permitted (albeit with some terrible reversals) better levels of living, better nutrition, better housing and better sanitation. Ideas about the germ theory of disease were critical to changing both public health infrastructure and personal behavior. Similarly, knowledge about the health effects of smoking in the middle of the twentieth century has had profound effects on behavior and on health. Most recently, the major life-saving scientific innovations in medical procedures and new pharmaceuticals have had a major effect, particularly on reduced mortality from cardiovascular disease. There have also been important health innovations whose effect has been mainly in poor countries: for example, the development of freeze-dried serums that can be transported without refrigeration, and of oral rehydration therapy for preventing the death of children from diarrhea.

Scientific understanding and technological progress makes some very efficient public health interventions – such as vaccinations, hygiene measures, oral rehydration therapy, and public health measures – cheaper and brings these more and more into the reach of populations with lower incomes

### Problem 5

Choose and fit one or more models to quantify the relationship betweem income (GDP per capita) and child mortality over time. Justify your choice of model and comment on its appropriateness. (You are not required to handle the autocorrelation of time series, but should comment on how this impacts your analysis.) Visualize the model(s) and comment on what they tell you about the relationship between income and child mortality over time.

![](https://github.com/alefiya-naseem/Data-Visualizations/blob/master/2-Gapminder-GDP/images/hw2_prob5_image1.png)
*GDP/capita over time across world regions*

![](https://github.com/alefiya-naseem/Data-Visualizations/blob/master/2-Gapminder-GDP/images/hw2_prob5_image2.png)
*Child mortality over time across world regions*

There's a clear linear relationship just by observing the data. So we'll first plot a linear regression to check fit (even though this seems naive as theres a temporal correlation here too). Let's treat this as a baseline. This is the result we get:

![](https://github.com/alefiya-naseem/Data-Visualizations/blob/master/2-Gapminder-GDP/images/hw2_prob5_image3.png)
*Predicted GDP versus True GDP*

We then fit a model using an algorithm that takes into account the temporal relationship. This is the result we get:

![](https://github.com/alefiya-naseem/Data-Visualizations/blob/master/2-Gapminder-GDP/images/hw2_prob5_image4.png)
*Predicted GDP versus True GDP*

Before the Modern Revolution child mortality was very high in all societies that we have knowledge of – a quarter of all children died in the first year of life, almost half died before reaching the end of puberty. Whether in Ancient Rome; Ancient Greece; the pre-Columbian Americas; Medieval Japan or Medieval England; the European Renaissance; or Imperial China: Every fourth newborn died in the first year of life. One out of two died in childhood.

During the last century the global mortality at a young age declined 10-fold. Over the last two centuries all countries in the world have made very rapid progress against child mortality. From 1800 to 1950 global mortality has halved from around 43% to 22.5%. Since 1950 the mortality rate has declined five-fold to 4.5% in 2015. All countries in the world have benefitted from this progress.

Child mortality in rich countries today is much lower than 1%. This is a very recent development and was only reached after a hundredfold decline in child mortality in these countries. In early-modern times, child mortality was very high; in 18th century Sweden every third child died, and in 19th century Germany every second child died. With declining poverty and increasing knowledge and service in the health sector, child mortality around the world is declining very rapidly: Global child mortality fell from 19% in 1960 to just below 4% in 2017; while 4% is still too high, this is a substantial achievement.

One reason why we do not hear about how global living conditions are improving in the media is that these are the slow processes that never make the headlines: A century ago every third child died before it was five years old, almost a century later the child mortality rate has fallen to 4%. We will not learn about this development from the news as such a slow development is never fast enough to make a headline. The headline that could have been published on every average day in the last century is “The global child mortality rate fell by 0.0008 percentage points since yesterday”.

Big countries like Brazil and China reduced their child mortality rates 10-fold over the last 4 decades. Other countries – especially in Africa – still have high child mortality rates, but it’s not true that these countries are not making progress. In Sub-Saharan Africa, child mortality has been continuously falling for the last 50 years (1 in 4 children died in the early 60s – today it is less than 1 in 10). Over the last decade this improvement has been happening faster than ever before. Rising prosperity, rising education and the spread of health care around the globe are the major drivers of this progress.

This is shown in the plot and confirmed by the mode, time and income together, contributed to the decrease in child mortality.
