# An Analysis of Kickstarter Campaigns
## Overview of Project

### Purpose

Purpose of the work is to analyze the following document and make report to help Louise plan fundraising for project campaign. We analyzed the worksheets to eliminate extreme data points and create charts to visualize the data and present Louise with the big picture.

## Analysis and Challenges
We created two new analyses: Outcome based on launch date and outcomes based on goals. Louise wanted to inquire how various campaigns have progressed in outcomes by goal and launch date.

### Analysis of Outcomes Based on Launch Date 
- Since we had many campaigns that missed their goal amount by a small margin we needed to create new columns in order to find the percentage of a campaigns funding. We measured central tendency and variance and standard deviation , and found outliers of the dataset. 
- Pivot tables were created in order to visualize campaigns based on launch date. New column “Years” was created out of “Data Created Conversion” column. As a result, line chart was made to display the number of successful, failed and canceled projects by months.

### Analysis of Outcomes based on Goals 
- In This part, KickStarter worksheet were grouped based on goal amount. Functions Countifs() and sum() were used to populate the outcomes, goals and total projects.
- We created "Goal" column with dollar-amount ranges to group them based on goal amount and illustated with line chart, with goal amount ranges on x-axis and the percentage of successful, failed and canceled projects on y-axis.

### Challenges and Difficulties Encountered

In this project I had few challenges with worksheet “Outcomes Based on Goal”. After filling out the columns with data and making line chart I noticed some data were incorrect. And I found out that I forgot to put the $ sign in formulas. And missed the row in this worksheet.
https://github.com/NominBatj/Kickstarter-Analysis/issues/3#issue-1221886273

## Results
- From the chart “Theater Outcomes by Launch Date” we could make a conclusions that peak of launched successful projects is May, it has 111 successful projects. June is also shows good results however since then it goes down dramatically and stops on September, from 100 projects to 59. Three main months that are considered to be slowest are January, March and November. 
- Failed projects on the other hand, stays constant until October, if we see the chart the number of successful and failed projects on that month, we can assume that there are more failed projects then successful: 50 and 65, however with one difference, on that month there were no canceled projects.
- Outcomes based on Goals chart illustrates many fluctuations points. Depending on the goal numbers the successful and failed projects vary. Higher the goal, more gap between them occur. For example, the range between 45000 to 49999 shows huge difference as percentage of failed projects reaches 100%.

There were some limitations, line chart sometimes could lose clarity when there are to many data points. In Theater Outcomes By Launch Date chart, it visually shows that data of the failed projects on October is higher then the rest, but if we see the tables, May showed an upward trend with 52 failed projects.
Depending on what kind of information we are trying to visualize, we need to understand what exactly we are providing information on, if we need to show the relationship between values in datasets, compare the value points or show trends and patterns. In my opinion, we could add tables like average donations to see contributions and how it affects projects or currency column to the dataset. 


