# Analyzing the Outcomes of Kickstarter Campaigns
## Overview of Project
Kickstarter is a crowdfunding platform that enables donaters around the world to donate to organizations and causes. 
### Purpose
To understand what makes a successful campaign, an analysis was performed on Kickstarter data from 2009 - 2017 for over 4,000 campaigns in a variety of categories, e.g. theater, concerts, and television. Our client. Louise, plans to launch a Kickstarter for her play, Fever, with a budget of $10,000, but would like information on the factors that dictate the success or failure of a campaign. The analysis revealed that the outcome of campaigns correlated strongly with their launch date, funding goals, and fundraising cateogry. 

## Analysis and Challenges
Outliers increased the average goal and average pledge. The dataset includes goals and pledges with large values that have no significance because Louise aims to raise $10,000, not 200,000, for example. Some campaigns had outlandishly high percent funding rates; this is because the campaign would set a goal of $1 just to have a goal, which misrepresented the color distribution for that column of data. In the blurb column, some characters were not translated correctly, hindering an analysis of the text. Although the dataset is in dollars, the actually currency must be taken into account, e.g. "$100" in USD is $100 as we would normally think of it, but "$100" in GBP is $126 in USD. 

![Kickstarter_Challenge](/Users/johnwhendricks/Desktop/classFolder/CrowdfundingAnalysis/Kickstarter_Challenge.xlsx)

A majority of the campaigns that failed set their funding goals far higher than the successful campaigns. The average goal was $5,050 for successful US kickstarters, but $10,550 for the failed fundraisers. However, the average pledge was $5,600 for those that succeded versus $560 for those that failed, meaning the unsuccessful kickstarters failed due to factors other than setting the price range too high. Regardless of campaign success, the average money pledged was greater than the majority of pledges, meaning a small group of unusually successful campaigns skewed the data. Although our client suggested setting a funding goal of $10,000, this is closer to the amount set by failed campaigns. For the successful campagins, the average pledged was $5,600 with $3,200 being the 50th percentile. Because of the larger average from unusually succesful campaigns, it is reccomended that the fundraising goal be placed closer to between $3,000-$4000, as this range is within the scope of what donaters have given in the past.


### Analysis of Outcomes Based on Launch Date
The second factor that determined campaigns success is the month the fundraising begins. As seen in the line graph, the month with the higest success rate was May, so this would be the best time to launch the kickstarter. The line graph for theater suggests that June and July are also viable options if the month of May is not possible. In other words, early summer is the best time to start a campaign. It is advised to avoid launching a campaign in October or November since the success rate decreases suddenly. The failure rate is steady of the course of the year.

![Theater_Outcomes_vs_Launch](/Users/johnwhendricks/Desktop/classFolder/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
The theater campaigns that succeeded the most frequently were those that set goals less than $5,000 - the success rate was roughly 65%. Nevertheless, theater campaigns that set a goal between $5,000 and $15,000 had success rate of roughly 55%. Beyond $15,000, the sucess rate plummets and the failure rate sharply rises, and these changes only reverse at goal of roughly $30,000, which is likely out of range for our client's budget.
![Outcomes_vs_Goals](/Users/johnwhendricks/Desktop/classFolder/resources/Outcomes_vs_Goals.png)


In the U.S. from 2009-2017, fundraising for theaters experienced a higher success rate than that of any other category. Among musicals, plays and spaces, plays had the highest success rate as seen in the second bar graph. This means a fundraising for a play would likely succeed in the U.S.

![US-Stacked-Bar-Chart](/Users/johnwhendricks/Desktop/classFolder/CrowdfundingAnalysis/US-Stacked-Bar-Chart.png)
![US-Subcat-theater-stacked-bar-chart](/Users/johnwhendricks/Desktop/classFolder/CrowdfundingAnalysis/US-Subcat-theater-stacked-bar-chart.png)

Of the 5 plays that the client preferred, all succeeded. Each play occurred in Great Britain and were launched between May and July. The monetary goal ranged from 1,000-4,000 pounds, and the pledges exceeded their goals by 1% more up to 172% more. 

Our client also expressed an interest in musicals. The box plot shows the distribution of musicals in Great Brigtain. Half the pledges ranged from 0.00-1,800.00 pounds, though 2,000 pounds was still within the interquartile range. Thus, a goal of 2,000 pounds would be a safer option for fundraising a musical in GB.

![Box-Plot-John-Hendricks](/Users/johnwhendricks/Desktop/classFolder/CrowdfundingAnalysis/Box-Plot-John-Hendricks.png)

In summary, initiating a kickstarter for a play in the early summer, especially the month of May, would likely be successful in the U.S. and Great Britain, as long as the funding goal is around $5000, preferrably between $3000-4000. Launching in June would be a viable second option.    
