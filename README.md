# An Analysis of Kickstarter Campaigns
Data analytics boot camp Module 1 Challenge
## Project Overview
Louise wants to create a play (*fever*) in theater in the US and estimates this will cost $12,000. The data analysis is to help Louise plan a fund rising campaign (the PROJECT).  The data used in this analysis is from Kickstarter, which is a crowdfunding platform. Scopes are, how campaigns fared in relation to: 
1. their launch dates. 
2. their funding goals.
## Analysis and Challenges
The data analysis on the data set shows that theater projects have higher chances to be successful in April, May, and June. More detailed analysis shows that for campaigns focus on plays in the theater category tend to be successful when they have lower goals.
### Outcomes Based on Launch Date
When looking at theater campaigns’ chances to be successful throughout months in all years, it is noticeable that total number of projects and chance of being successful show seasonal effects. Number of campaigns spikes up from March and reaches its peak in May. The number falls and reaches its lowest point in December. All months show that number of successful campaigns is higher than the number of failed campaigns. Number of canceled campaigns also varied throughout months with January being the highest, and October being the lowest.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/78275082/109400544-4db75000-7917-11eb-97c8-a0d6e3343f52.png)
*Figure 1 Theater Outcomes vs Launch Date*

### Outcomes Based on Goals
Further data analysis focused on how the campaigns end up with the trend of goals. The result shows that, for campaigns in theater category, plays subcategory, setting up lower goals renders campaigns higher possibility of being successful. More specifically, for projects with less than 1,000 in any currency, 141 out of 186 campaigns were successfully funded, which gives 76% being successful and 24% being failed. Only about 29% of campaigns with goals higher than 25000 in any currency were successful.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/78275082/109400546-5019aa00-7917-11eb-90e6-e557499567e2.png)
*Figure 2 Outcomes Based on Goals*

### Challenges
There are clear hints that the outcomes of campaigns have some correlations with seasons, where campaign population increases in warmer months and chance of being successful increases too. However, it is not entirely clear if the seasonal effect applies to campaign outcomes in the countries in southern hemisphere, due to lack of data.

Rates of being successful have a clear declining trend from lower goals to higher goals before 25,000. But when the goal range passes beyond 25,000, due to low data population, the declining trend is not clear. By combining all data above 25,000, an overall successful rate of 28.57% supports the conclusion that, rate of being successful decreases with the increase of goals.

## Summary
The outcomes of theater/plays campaigns in the past suggest launching the PROJECT in April, May, or June, with launching in May being the best option. If the PROJECT has unavoidable challenges of being launched in these months, Louise should try to avoid launching the project in October, December, and January.

The incentive of the PROJECT should be as low as possible. To have a higher than 50% chance of being successful, the goal can be set to be lower than $20,000. The $12,000 estimate given by Louise falls into this range. But to have a better chance of being successfully funded, the goal should be lowered as much as possible.

The data set used in this analysis only contains information from 2009 to 2017. If the project is scheduled to be launched in 2021, obtain and analyze data from 2020 is strongly recommended. Because market behavior may be different during COVID-19 pandemic.

More detailed data analysis should be done focusing on data of campaigns launched in the US.

Outcomes based on pledged can be helpful setting up the project goal. A range of goals where successful rate is high enough and percentage funded is slightly above 100% can be identified by analyzing percentage funded in different goal ranges. Moreover, more analysis can be done on correlations between project outcomes and fundraising time span. Choosing a reasonable deadline carefully can also contribute to the success of the PROJECT.
