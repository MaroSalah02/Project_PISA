# PISA Data Exploration 
## by Marawan Abdelrahman	


## Dataset

> I have used The PISA 2012 dataset Which you can get from [This link](https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip). This Dataset contains 
a survey of students' skills at the end of compulasory(obligatory) education in 68 different 
location around the world and describes how well are the student beyond this education. This aslo 
contains the scores of 485490 student who conducted PISA assesment in science, math and reading. I have chose 55 feautres from 635 features which was available in the dataset.
after some exploration with the data, I Found out some column as ("Troublesome") have almost 50% of the values are nan, some have only 5%.So,
 I decided to remove the nan values before visualizing each plot to prevent loosing valiable data.

## Summary of Findings

> In this exploration, I have found interesting outputs many of students' learning time for math or science ranges between 100 and 500 per week. They got the highest score in
assesment exam of PISA 2012 in the dataset which for me was Interesting. there was positive relation betweenthem but it wasn't strong. I found some outliers for students consumes 3000 minutes
per week and  geys the same average score of student who spend 100 or less.Second Insight was the effect of having father and mother at home. First I compared it with the average total score 
in math,Science and reading in the whole dataset and showed me that people without one of the parents at home got less score in average to the people who have any of the parents.
I wanted to confidence to this conclusion. SO, I get the top 10 countries in the average total score. I used this ten and made the same mother and father analysis on each country.
I got the same conclusion as the first one. I saw too that usually the students who got high total score agree that they are Quicl learner this answer to us why students with high score in math and 
science and math spends less time learning at the same time they rarely asks the teacher for help.<br>

> outside our main features, I saw that the students who doesn't have both parents at home they sometimes become more troublesome. Interesting fact, Almost 15 % of the students who 
conducted the test doesn't have internet.


## Key Insights for Presentation

> In, The presentation I focused on showing score of math,science and reading and the total score of students who conducted the test then conclue the charistricts of these students. <br>

> First, I showed the time distribution for all the students they consumed on studying math and science weekly. I made sure to use different plots shapes with different and meaningful color
palette. Then I magnified the scatter plot in the relation 
between time consumed per week for learning and student score in math and science.I used
the Quick learning with total score of student.After that I added the need of math of teacher factor to the math score and time consumed .Then compared each country with the other in the average
total score. I used the top 10 locations and made Facetated box plot for each country to the affect of absence mother and 
father from home. <br> 
Finally, I added a facetaed barplot which shows the negative effect of mother and father absence from home which 
showed that they become more troublesome. 

## Other people opinion. 

> I showed my work on some friends. They recommended to increase The fontsize of plots.I Took this opinion and done it.

## Documentaions I have used To understand and anlyse the data:

[link 1](https://www.oecd.org/pisa/keyfindings/PISA2012-Vol3-AnnexA.pdf)


[link 2](https://read.oecd-ilibrary.org/education/pisa-data-analysis-manual-spss-second-edition_9789264056275-en#page1)


[link 3](https://www.oecd.org/pisa/keyfindings/pisa-2012-results-overview.pdf)