# DataVizHw1
Data Visualization Homework 1

## Problem 1

#### What score did you receive? Did any of the answers surprise you?

I scored 31%. Surprised by my general misconception that things are getting worse but statistically they aren't.

##### Choose a question from the test, re-state it, and answer it using visualization and summarization. Provide a figure and any relevant output with your answer.

In the last 20 years the proportion of people living in extreme poverty worldwide, has...?

![](https://github.com/alefiya-naseem/Data-Visualizations/blob/master/1-Gapminder-Analysis/images/prob1_hw1.png)

After grouping 161 countries into 6 regions they belong to, we can see that almost all of them have seen their extreme poverty rate has almost halved. This could be due to the increase in industrialization across the globe after 1950's.

## Problem 2

#### Visualize the distribution of income (GDP / capita) across countries and continents, and how the distribution of income changes over time.

![](https://github.com/alefiya-naseem/Data-Visualizations/blob/master/1-Gapminder-Analysis/images/animated_prob2.gif)

#### Interpret the visualization and what you notice. Are they any notable trends and/or deviations from that trend? What caveats apply to your conclusions?

The GDP has constantly gone up for all countries, thus also the continents. We can observe Europe and America has a higher GDP per capita, while GDP for Africa is on par with other countries in the 1950's. This can be attributed to the civil wars in the African countries being a major cause of their low GDP in today's day and age. Once can say that industrialization has helped the boost in GDP pver across all countries. Countries like Russia, China and South Asia are catching up with America and Europe in terms of GDP. Saudi Arabia experienced a large change in it's after the 1950's which one can attribute to the rise of oil industry.

## Problem 3

#### Use visualization to investigate the relationship between income (GDP / capita), life expectancy, and child mortality over time. How does each measure change over time within each continent?

![](https://github.com/alefiya-naseem/Data-Visualizations/blob/master/1-Gapminder-Analysis/images/animated_prob3.gif)

#### Interpret your visualizations, noting any trends and/or outliers.

Life Expectancy remained almost stagnant for 100 years. We see a positive correlation between income, life expectancy and child mortality. Life expectancy gradually increased across all continents which explains the shift from left to right along x-axis. The shift of data upwards can be explained by the increase in income which can be seen in problem 2. Child mortality decreases over time and is much less in the areas of high income and life expectancy. Europe has the lowest child mortality per 1000 births. A drastic rise in GDP can be observed in Asia from 1950-1970. 

## Problem 4

#### Choose two variables you have not investigated yet, and visualize their distributions, their relationship with each other, and how these change over time.

I wanted to see how malnourishment and child deaths of children under 5 years has been trending with an increase in gdp and income over the years. For this purpose I have used the icome per person dataset, malnutrition percent of children under 5 years and total population of children under 5 years and the geographic data to distribute it.

![](https://github.com/alefiya-naseem/Data-Visualizations/blob/master/1-Gapminder-Analysis/images/prob4_hw1.png)

[Click here to view the visualization in play in notebook](https://github.com/alefiya-naseem/DataVizHw1/blob/master/DataViz-gapminder.ipynb)

#### Interpret your visualizations, noting any trends and/or outliers.

To get the above visulaization I have merged all the datasets due to which the data size reduced alot as the malnutrition dataset does not contain data for alot of years and for alot of the countries. One can see from the above visualization that the major geographic regions(continents) that have seen significant malnutrition are Africa and Asia. Even in these continents the percentage of children under 5 who face malnutrition has decreased over the years with an increase in GDP per capita. Even in Asia the major country facing malnutrition is India which could be attributed to the uneven rainfall that the region receives thus alot of the regions Like Vidarbha face droughts for years but one should not forget that India has a large population hence, the size of the bubble.

## Problem 5

#### Did you use static or interactive plots to answer the previous problems?

I have used static and interactive animated plots to answer the previous problems.

#### Discuss the advantages, disadvantages, and relative usefulness of using interactive/dynamic visualizations versus static visualizations.

Overall, I think both static and interactive plots have their own set of pros and cons. Advantages of animated or interactive plots can be they are fun and appealing. They also can be used to represent a wide number of features and how they perform over time. Disadvantages of using animations could be they aren't really useful in static documents like articles or journal especially printed materials. They can also be very time consuming and can confuse alot of people if not interpreted properly.

As for static images, their pros could be they can be used in printed material and be self-contained and can be simpler to interpret than their interactive plot counterparts. Their disadvantages could be you cannot reppresent a wide amount of information or features using them.

