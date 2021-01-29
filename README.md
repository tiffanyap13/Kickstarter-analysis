# Kickstarting with Excel
## Overview of Project
This analysis reveals how the stakeholder’s previous theater campaigns fared in relation to their respective launch date and also the success of the theater/play campaigns based upon the different levels of funding goals.
### Purpose of Analysis
The purpose of this analysis fulfills two needs. First, it will help the stakeholder determine the best date to launch a theater campaign based on prior trends. Second, the analysis will give the stakeholder insight into the most advantageous goal of the fundraising dollar amount per crowdfunding campaign for plays, based on past success in fundraising goals for plays.
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
Using the raw data, I created a pivot table to reveal the successful, failed, and canceled outcomes based on the respective month for all years of attempted theater launches.  From the pivot table, I created a line chart that reveals the trends of successful, failed, and canceled campaigns by month. ![Screenshot Pivot](Screenshot_Pivot.png)Upon review, there were more successful campaigns than not; over half (approximately 60%) were successful and of those the top two successful months were May and June. Of the failed launches, the majority fell in May, June, and October. Less than 3% of the launches were canceled, with January being the highest month. [Outcome Based on Launch Date](Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
For the second analysis, I used the raw data to analyze the number of successful, failed, and canceled theater/play projects based on the predetermined crowdfunding levels.  This data was pulled using the following formula: 'COUNTIFS(Kickstarter!$D:$D,"<1000", Kickstarter!$F:$F,"successful",Kickstarter!$R:$R,"plays")' (formula was adjusted for each respective level of giving). Next, I looked at the results as a percentage based on each levels’ totals. Finally, I created a line graph to map out the results. ![Chart of Outcomes](Chart_Outcomes_Goals.png)  Per the data, there were no canceled plays with which fundraising was associated, unless they reimbursed the donors respectively.  Per the results, the two most successful crowdfunding levels seem to be below $1,000 and between $1,000 and $4,999.  Interestingly, the highest rate of failure occurred at the level of $1,000 to $4,999. [Outcomes vs Goals](Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
During my analysis I did not encounter any difficulties aside from not having full insight into the data.  In order to provide more impactful recommendations to the stakeholder, more insight into the details behind the data would be helpful, such as the composition of the donations and donors. 
## Results of Analysis
### Outcomes by Launch Date
Two conclusions were reached regarding the Theater Outcomes by Launch Date.  First, based on the date, it appears the two most successful months to launch a theater production are May and June.  Second, the largest failure of a launch occurred almost equally in the months of May, July, and October.
### Outcomes vs Goals
Analysis of Outcomes Based on Goals reveals that the most advantageous fundraising levels are less than $1,000 per crowdfunding activity, based on the success rate per project at each donation level.
## Limitations and Suggested Additional Analysis
One should note that there may be limitations of this data set. Other possible tables and/or graphs could be created to assist in answering the numerous questions that arose during my analysis.
### Launch Dates
Some other possible ways to analyze that would give more insight would be to look at the Launch Date data in percentage form. For example, as a percentage of overall launches, what was the success and failure rate?  We also could look at the analysis year over year to determine if there were significant differences in results between the years for theater outcomes by launch dates.  Finally, we may find it insightful to review the success in launch date by country.  The current pivot table could be manipulated to look at specific years, countries, and the totals changed to percentages instead of sums.  Finally, a stacked column bar chart graph could be used to look at the outcomes by month.
### Outcomes Based on Goals
Regarding the Outcomes Based on Goals, we do not know how the campaigns were approached. For example, were donors at each level targeted specifically or were donors allowed to determine their level of gift? If the latter, perhaps the analysis should cover the success to projects overall instead of at each level of crowdfunding.  Also, it is unknown if these are one-time donors or if a donor is accounted for multiple times if they have given at different levels based over a span of years.  Looking at the results by donor, by country, and also by year would be interesting and may provide different outcomes and further insight.  A pivot table could be used to pull in this additional analysis.  Finally, a different yet equally helpful way to view the current data would be the use of a clustered bar chart.

