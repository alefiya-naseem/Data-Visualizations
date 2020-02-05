#
DataVizHw4

Data Visualization Homework 4

## Overview

This homework assignment continues to use school data from the previous assignment.

Download the 2015-16 district-level fiscal data from the National Center for Education Statistics’ Common
Core of Data:
* [National Center for education Statistics' Common Core of Data](https://nces.ed.gov/ccd/f33agency.asp)

The 2015-16 performance statistics on graduation rate and state assessments on mathematics and reading/language arts are available from the EDFacts website:
* [Assessments on Mathematics and Realding/Language Arts Data](https://www2.ed.gov/about/inits/ed/edfacts/data-files/index.html)

Additionally, the 2015-16 district-level “universe” survey data provides statistics about enrollment disaggregated by demographics like gender, race, disability status, etc:
• [CCD Demographics data 2015-2016](https://nces.ed.gov/ccd/pubagency.asp)

These datasets can be linked based on the LEA IDs.

## Problem 1

For the districts you selected for budget cuts in HW 3 Problem 4, calculate and visualize the proportion of each district’s total funding that will be lost. Which districts will be affected by your budget cuts the most?

The plot below shows the proportion of each district's total funding that is lost.

<p align="center">
	<img width="560" height="420" alt="Proportion of each district’s total funding that will be lost" src="https://github.com/alefiya-naseem/Data-Visualizations/blob/master/4-NCES-Funding-Cut-Analysis/images/budget_cut_proportion.png">
</p>

The top 10 districts which are affected the most by the budget cuts are:

<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>LEAID</th>
      <th>NAME</th>
      <th>TOTALREV</th>
      <th>DEDUCT_15</th>
      <th>Proportion cut</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>15896</th>
      <td>4800191</td>
      <td>NORTHWEST PREPARATORY</td>
      <td>2000</td>
      <td>591.0</td>
      <td>0.295500</td>
    </tr>
    <tr>
      <th>10134</th>
      <td>3400059</td>
      <td>Galloway Community Charter School</td>
      <td>283000</td>
      <td>83599.0</td>
      <td>0.295403</td>
    </tr>
    <tr>
      <th>12352</th>
      <td>3800395</td>
      <td>ROUGHRIDER AREA CAREER &amp; TECHNICAL CENTER</td>
      <td>365000</td>
      <td>107822.0</td>
      <td>0.295403</td>
    </tr>
    <tr>
      <th>12944</th>
      <td>3901570</td>
      <td>Citizens Academy Southeast</td>
      <td>1499000</td>
      <td>442807.0</td>
      <td>0.295402</td>
    </tr>
    <tr>
      <th>15956</th>
      <td>4800291</td>
      <td>WINDHAM SCHOOL DISTRICT</td>
      <td>3203000</td>
      <td>946171.0</td>
      <td>0.295401</td>
    </tr>
    <tr>
      <th>15935</th>
      <td>4800261</td>
      <td>HARRIS COUNTY DEPT OF ED</td>
      <td>1831000</td>
      <td>540880.0</td>
      <td>0.295401</td>
    </tr>
    <tr>
      <th>15838</th>
      <td>4800091</td>
      <td>CHILDREN FIRST ACADEMY OF DALLAS</td>
      <td>147000</td>
      <td>43424.0</td>
      <td>0.295401</td>
    </tr>
    <tr>
      <th>2878</th>
      <td>09D0001</td>
      <td>COMMITTEE FOR SHARED SERVICES</td>
      <td>439000</td>
      <td>129681.0</td>
      <td>0.295401</td>
    </tr>
    <tr>
      <th>345</th>
      <td>400206</td>
      <td>Desert Springs Academy</td>
      <td>529000</td>
      <td>156267.0</td>
      <td>0.295401</td>
    </tr>
    <tr>
      <th>10142</th>
      <td>3400075</td>
      <td>Central Jersey Arts Charter School</td>
      <td>342000</td>
      <td>101027.0</td>
      <td>0.295401</td>
    </tr>
  </tbody>
</table>

## Problem 2

A common problem with purely data-driven solutions is that they can inadvertently perpetuate hidden pre-existing biases in the data, and further disadvantage groups that are already disadvantaged.

Calculate the proportion of enrolled students by race for each district, then visualize the distributions of these for districts that received budget cuts versus districts that did not receive budget cuts.

Comment on whether the distributions appear to be the same or different. Did your selection include any hidden biases, or manage to avoid them?

<p align="center">
	<img width="560" height="420" alt="Proportion of American Indian/Alaska Native enrolled students across districts that received budget cuts versus districts that did not receive budget cuts." src="https://github.com/alefiya-naseem/Data-Visualizations/blob/master/4-NCES-Funding-Cut-Analysis/images/proportion_cut_AM.png">
</p>

<p align="center">
	<img width="560" height="420" alt="Proportion of Asian enrolled students across districts that received budget cuts versus districts that did not receive budget cuts." src="https://github.com/alefiya-naseem/Data-Visualizations/blob/master/4-NCES-Funding-Cut-Analysis/images/proportion_cut_AS.png">
</p>

<p align="center">
	<img width="560" height="420" alt="Proportion of Hispanic enrolled students across districts that received budget cuts versus districts that did not receive budget cuts." src="https://github.com/alefiya-naseem/Data-Visualizations/blob/master/4-NCES-Funding-Cut-Analysis/images/proportion_cut_HI.png">
</p>

<p align="center">
	<img width="560" height="420" alt="Proportion of Black enrolled students across districts that received budget cuts versus districts that did not receive budget cuts." src="https://github.com/alefiya-naseem/Data-Visualizations/blob/master/4-NCES-Funding-Cut-Analysis/images/proportion_cut_BL.png">">
</p>

<p align="center">
	<img width="560" height="420" alt="Proportion of White enrolled students across districts that received budget cuts versus districts that did not receive budget cuts." src="https://github.com/alefiya-naseem/Data-Visualizations/blob/master/4-NCES-Funding-Cut-Analysis/images/proportion_cut_WH.png">
</p>

<p align="center">
	<img width="560" height="420" alt="Proportion of Hawaiian Native/Pacific Islander enrolled students across districts that received budget cuts versus districts that did not receive budget cuts." src="https://github.com/alefiya-naseem/Data-Visualizations/blob/master/4-NCES-Funding-Cut-Analysis/images/proportion_cut_HP.png">
</p>

<p align="center">
	<img width="560" height="420" alt="Proportion of Two or More Races enrolled students across districts that received budget cuts versus districts that did not receive budget cuts" src="https://github.com/alefiya-naseem/Data-Visualizations/blob/master/4-NCES-Funding-Cut-Analysis/images/proportion_cut_TR.png">
</p>

From the above plots we can see that there isn't alot of difference between districts that might face budget cuts versus those that will not. The paired violin plots do not show a lot of difference in their proportions for eachof the identified ethnicities. The only distinction we can see between them is of the outliers. Thus, it seems like the method used here, for selection of which schools will face a budget cut manages to avoid any hidden biases.

## Problem 3

Calculate the proportion of enrolled students by disability status (students with an IEP under IDEA) for each district, then visualize the distributions of these proportions for districts that received budget cuts versus districts that did not receive budget cuts.

Comment on whether the distributions appear to be the same or different. Did your selection include any hidden biases, or manage to avoid them?

<p align="center">
	<img width="560" height="420" alt="Proportion of enrolled students by disability status across districts that received budget cuts versus districts that did not receive budget cuts." src="https://github.com/alefiya-naseem/Data-Visualizations/blob/master/4-NCES-Funding-Cut-Analysis/images/proportion_cut_disability%20status%20students.png">
</p>

<p align="center">
        <img width="560" height="420" alt="Proportion of each district’s enrolled students by disability status" src="https://github.com/alefiya-naseem/Data-Visualizations/blob/master/4-NCES-Funding-Cut-Analysis/images/budget_cut_proportion_disability_students.png">
</p>

From the above plots it can be observed that the distribution of students with disability status for districts with and withput funding cut are more or less similar. We can see a higher proportion of students clustered near the top end of the "No budget cut" group and lower proportion for students with "budget cut" though this difference is very small. We can also see from the above histogram that the number of students on IEP is highly skewed on one side and hence, one cannot ocnfidently say if the method slected for funcding cut avoids any hidden biases or no.

## Problem 4

Choose and critique one of your fellow classmates’ selection of schools for budget cuts in HW 3 Problem 4 and Problem 5. What was the justification of their selection? Discuss any advantages or disadvantages of their approach.

Link to the hw3 submission: ![](https://github.com/tonytontian/DS5500/blob/master/hw3/hw3.ipynb)

The classmate suggests to cut off 15% for every district which gets a positive number of federal funding. As it is the most equal way to do so.

The advantage of this method is that it is quite straightforward and simple. This approach makes it easy to understand how the budget cut takes place.

It is interesting to note that the author believes this is the most fair method. It does not take into consideration any other factors such as the performance of a particular school district or their financial condition if it is debt or no. It would be unfair to cut the budget from school districts that are already struggling and might also affect  students that are performing well in these schools despite of the low federal funding. Cutting of these schools budget might also lead to less extra curricular activities for this school in turn which might lead to students not performing well.

## Problem 5

Summarize and comment on what you learned from one the special topics lectures (MapReduce + Hadoop, Visualization, Causal Inference, or the Industry Panel) of your choice.

I would like to summarize and comment on what I learned from the Industry Panel i.e. "Data Science in the Real World: a practitioner’s panel" which was hosted on November 18, 2019. The panel consisted of the moderator: Faye Zheng who is a Data Scientist at Gamalon; and 4 panelists-
* Michelle Tat who is currently a Population Health Data Analyst at Haven Healthcare
* Daniel Hannah who is a data scientist at Vectra AI
* Katie Porter who is a Sales Engineering Lead at Tamr
* Luke Winslow who is a Data Science Manager at Wayfair

One interesting thing to note here was that all of them have very different job titles, responsibilities and acadmeic backgrounds but how each of those still intertwines and meets the principles of data science in their day to day tasks.

As a student who is actively looking to make a future in Data Science roles and looking for a job this talk was extremely helpful in setting expectations and understanding not only the job market but also it's needs.

A few key takeaways from the discussion were:

* Your background is not the only factor that decides whether you can get a data scientist job or no. Your interests are important too, the domain you want to work on and the path you want to take in your career depends on the company's values and the job offered too. Hence, research while applying  for a position. Do your interests match the company's interests too? You may not fit a 100% into their criteria but even then if you think that is somethign you can do then apply.

* Do the work. Know your data. Explore the data. Clean it. Graph it. Repeat. Look at the top 10 most frequent values. Study the outliers. Check the distributions. Group similar values if it’s too fragmented. Look for correlations and missing data. The more you know about your data, the better you will be able to ask questions and answer them.

* There’s a lot of communication involved in understanding the problem and delivering constant feedback to the stakeholders. But this is just the surface of the importance of communication – a much more important element for a data scientist is also asking the right questions. Data scientists are much more likely to fall into a trap of the curse of knowledge cognitive bias than any other occupation. This bias “occurs when an individual, communicating with other individuals, unknowingly assumes that the others have the background to understand.” When the data scientist is scoping out a problem together with the stakeholders or presenting the first findings, it is vital to be as explicit and detailed as possible and not assume that stakeholders know as much as you do. This is very hard as the number of assumptions and underlying methodologies that a data scientist makes can be counted in dozens, even hundreds.
