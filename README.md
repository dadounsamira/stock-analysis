# stock-analysis


## Overview of project. 

Steve parent's are very passionate about grenne energy and decided to invest all their money in DAQO New Energy Corpwithout doing much research, Stve as new graduate and and finance passionate want to analyse handful of green energy stocks in addition to DAQO stocks to  diverify the portfolio and mitigate the risk of putting all the money in one product.
Included the source of this dataset [here](/VBA_Challenge.xlsm.xlsm)


## Results



### the stock performance in  2017

To visualize campaign outcomes based on Launch date, a pivot table and graphing were created based on kickstarter worksheet, applying the following fields :

*Parent category and years in filter

*Outcomes in the columns

*Outcomes in the Values

*Date created conversion in Rows

*the parent category is filtred on theater

*The row labels are changed to display the months of the year, and the campaign outcomes are sorted in descending order

*A line chart is created showing the number of successful, failed, or canceled projects by month

here is the graphic that shows the successful, canceled and failed campaign based on the month of launch, best time to launch fundraising is between Apil and August.


![here](/resources/Theater_Outcomes_vs_Launch.png)


### the stock performance in  2018

For this analysis we used the function COUNTIFS to visualize  the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis, applying the following fields:
* Goal, Number Successful,Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed and Percentage Canceled in columns 
* Amount ranging between less than 1000 and greater than 50000 in rows so  so projects can be grouped based on their goal amount

The formula for the Countifs is : =COUNTIFS(kickstarter_challenge!D:D, "<=1000", kickstarter_challenge!F:F,"successful",kickstarter_challenge!R:R,"plays")


![here](/resources/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered

I encountered some difficulties producing some visualizations because of my lack of knowledge in excel but the extra sessions with the assistant teacher helped me solve my issues, also had hard time getting familiar with github. 



## Results


### What are the advantages or disadvantages of refactoring code?

The graphic Outcomes by Launch Date shows that most successful projects are launched in May and June, May being the pick month, two factors explains this trend the weather and the end of tax return, as the weather get nicer people tend to be more joyful and more willing to put money in fundraising especially after getting some tax return.
Also to note that December is the worst month to launch a project as the failed and successful project tends to be in same level thats because of christmas, people tends to spend a lot of money during christmas.

### How do these pros and cons apply to refactoring the original VBA script? 

The dateset shows that there is a higher probability of successful projects lower the goal is however there is higher probability of successful funding projects with a goal between 20000 and 35000 and projects above 40000.
this might lead Louise to conclude that for smaller project it might be neccessary to try attracting a type of range of the population people with small income, student in art,.... and project with higher goals need to be directed toward middle higher income population.



