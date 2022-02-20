# Kickstarting with Excel

## Overview of Project
Analyze the data to view the correlation between Outcomes and Launch Date, View (by percent) the number of successful, failed and cancelled kickstarts by the Goal ($) amount. 

### Purpose
Within the dataset we have numerous amounts of Kickstarter campaigns that are defined by 'Parent' Categories and 'Sub' Categories. The analysis conducted is based on the user preference, which in this case is: Parent Category- Theater; Subcategory- Plays. Through the kickstarters goal column, pledge amount and date launched, analysis can be done on how much should the goal amount should be, what moth the Kickstarter should be launched and vice versa. 

## Analysis and Challenges
The analysis takes a deeper dive into the success, failure and cancellations (defined as outcomes) of the subcategory of Plays through two approaches: 

1. The correlation between the date of when each individual Kickstarter began (by month) and its outcome and 
2. Each individual Kickstarter goal dollar amount from $0 through +50,000 and its correlation with the percentage of the type of outcome.

### Analysis of Outcomes Based on Launch Date

For reference to the Outcome Based on Launch Date Analysis, please see the chart belo

The Y axis represents the count (unit amount) of kickstarters.
The X axis represents the corresponding month the Kickstarters began. 
There are a total of 3 lines, each representing individual outcomes: Successful, Failed and Cancelled. Analyzing all three lines at a time, there is a slight trend that is followed by both the successful and failed lines. Hat start in January, go up in Feb, and down again in March. This is continued by an uptick in the months of April, and both reaching their annual peak in May (Successful: 111; Failed:52). Both lines then trend downward until reaching September, where both have an uptick in October and then proceed downward in November. It is only in December where there is a difference in trend. % Failed beats success % by 2%, meaning there are more failed kickstarters that successful kickstarters in the month of December.  
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/98041751/154826018-1ea081a8-2acb-48dc-8b56-e569ad945eb6.png)

### Analysis of Outcomes Based on Goals

_For reference to the Outcome Based on Goals Analysis, please see the chart below_

The Y axis presents the percentage of how many Kickstarters are successful, failed or canceled. The X axis presents the goal amount in 12 ranges (in $), beginning with kickstarters that began with <=$1,000 ending with >$50,000. 
There are a total of Three lines representing the % successful, % failed and % cancelled, however, there are two lines visible (successful & failed) since there is no data for cancelled. Meaning there were no cancelled Plays. 

Success Line: Projects that have a goal of <$1000 have the best success rate (76%). There is a huge jump when pursing the goal range of $35,000-$39,999 and $40,000-$44,999. These three goal amount ranges seem to be the best to pursue if someone would like to have a successful Kickstarter. 

Failure Line:  The failure rate begins very low, but at the goal amount increases, the failure rate also increases. This can be expected, the higher you raise your goal amount, the more likely someone will not be able to fulfill the goal amount. 
However, after the line peaks at 25,000-29,999, it declines significantly within the $35,000-$39,999 & $40,000 - $44,999 ranges, then dramatically increases as the goal amount surpasses $44,999. This means that the best goal amount to place is <1000 or between $35,000 - $44,999.
The correlation between the two lines, as one goes up, the other goes down. If the success percent increases, then by default, the failure rate must decrease simultaneously.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/98041751/154825942-408af1e9-634e-4fbe-aaf8-b37ec67b5aa6.png)

### Challenges and Difficulties Encountered
	User capabilities, comprehension and errors. 
  
  
## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1. The best month to begin a Kickstarter is in the month of May since May has the highest number of successful kick starters (111) compared to all other months. 
  2.  Failed campaigns are almost half the amount of successful campaigns. The failure chart line somewhat follows the same trend, although the failed kickstarter’s line on the graph seem to be more linear in nature, meaning it does not see as much change as the successful chart line it still has an uptick in the month of May. 

- What can you conclude about the Outcomes based on Goals?
  The best goal amounts to place are >$1000, OR between $35,000 - $44,999.  The worst amount to invest is $45,000 – $49,999 since there is 0 success%. 


- What are some limitations of this dataset?

  Each chart presents their own set of limitations, however, simultaneously they do not take into account the reasons the Kickstarter failed/succeeded. The genres with   correlation of country may also present changes to the country if certain countries have preferences. Both charts cannot determine outliers. 

  **Outcomes Based on Goal**: There are multiple Kickstarters that go beyond $50,000 and with this chart, we would not have a clue on how much the goal amount would be for those Kickstarters. Also, through the graph, we cannot determine how many kickstarters there were present. 

  **Theater Outcomes by Launch Date:** This is only a year’s worth of data and cannot be heavily relied upon because we do not know if there were one-time events that could affect the data. We also cannot see if it is a seasonal or rotational trend to follow since it is only a years’ worth of data. 

- What are some other possible tables and/or graphs that we could create?

  	Box and whiskers: To visualize where the medium is and compare it to the QLR and see what a reasonable goal and pledge amount would be. 
    Stacked Column Chart: To compare the number of successful, failed, and cancelled kickstarters  are to each other as a whole. 

