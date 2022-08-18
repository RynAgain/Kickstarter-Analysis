# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this analysis is to help Louise gain insight into the how his play compared to other plays using Kickstarter.
Since his play was fairly successful in fundraising, he wants to know what factors couldn've played a role in that success.
This anlaysis will focus on the launch date of the kickstarters and their fundraising goals compaired to if they were successful.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

In figure 1 (Theater_Outcomes_vs_Launch.png) we can see a compairson of launch month and how many Theater type kickstarters were failed, cancled, or successful.
Given the low volume of canceled theater kickstarters, we will mostly focus on ones that were failed and successful.  The top grey line on the chart is shows that May is the best time to 
be launching the Kickstarter since it has the highest number of successful campainges. Any other time of the year would produce a lower success rate.

### Analysis of Outcomes Based on Goals
In Figure 2 (Outcomes_vs_Goals.png) we compare different ranges of fundraising goals to the general success rate of plays.  The graph shows two ranges that have a success rate higher than the both the failure rate and cancelation rate.
The first success range is $1 to $15000 and the second is 35000 to 45000.  Anything outside of these ranges has a higer chance of failing.

### Challenges and Difficulties Encountered
The main challenge I encoutered was an error with my 'Outcomes based on goals' sheet, where I basically over locked the 'total' cell for my Percentages.  This caused all my percentages to be based on the first row.
I didn't realize this was the issue untill i added the percentages together to insure that they added up to 100.  From there I just found the error with my formula and tiedously fixed each one.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
A.  Best time to launch a kickstarter is May.
B.  The worst time to launch is October, since it has the worst failed to successful ratio.

- What can you conclude about the Outcomes based on Goals?
A. Projects with small fundrasing goals tend to be very successful
B. Pojects with fundrasing goals between 35k and 45k also appear to have a decent success rate, however it is unclear why that might be.

- What are some limitations of this dataset?
First, limitation that comes to mind is if the fundraising amounts were actually converted to USD.  The column labled 'Currency' makes me suspicious if a proper conversion to one currency
actually occured.  If not, this would be a good time to use VBA coding to automate the process based on 'Currency' data.
Second, is the sample size of the data, especially when we filter down to just plays.  Having more data pull from always seems to help make more accurate conclusions. 

- What are some other possible tables and/or graphs that we could create?
For further analysis I would recomend adding the following data and correspoding charts:  First, I'd calculate the average donation per backer and comparing it to the success rate.
This could help find a relationship between how much money people can be asked to contribute and the success rate of the campagine.
Second, I'd also see if the country has any impact on success rate or fund raising amount.  It would be interesting to determine if there was a location bias in the data.
