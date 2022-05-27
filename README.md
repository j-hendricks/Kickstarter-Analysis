# Analyzing the Outcomes of Kickstarter Campaigns

## Overview of Project
Kickstarter is a crowdfunding platform that enables people around the world to donate to organizations and causes. Our client wishes to organize a play caled **Fever**, and aims to raise $10,000 on Kickstarter to accomplish this. In order to advise the client on how to organize the campaign, the Kickstarter outcomes of different theater campaigns were analyzed across different variables, such as the campagin launch date and monetary goal. Visualizations of the data suggest that our client should start their fundraising in the early summer, especially May, since theater campaigns have the highest success rate during this time of the year. As for finances, plays with a fundraising goal between $10,000-$14,999 have a success rate of roughly 55%, and those between $5,000-$9,999 were roughly 55% as well. From these rates, it is advised that the cient avoid lowering the goal much below $10,000 because there will not be a higher success rate until the $1000-$4,999 range. In addition, client should avoid raising the funding goal above $10,000, because the success rate for plays drops significantly near $15,000, and the fail rate increases as well. 

### Purpose
To understand what makes a successful campaign, an analysis was performed on Kickstarter data from 2009 - 2017 for over 4,000 campaigns in a variety of categories, e.g. theater, concerts, and television. Our client, Louise, plans to launch a Kickstarter for her play, **Fever**, with a budget of $10,000, but would like information on the factors that dictate the success or failure of a campaign. The analysis revealed that the outcome of campaigns correlated strongly with their launch date, funding goals, and fundraising cateogry. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The month of the launch date dictated the success and fail rates for plays in the U.S. As seen in the line chart, the month with the higest success rate was May, so this would be the best time to launch the kickstarter. The line graph for theater suggests that June and July are also viable options if the month of May is not possible. In other words, early summer is the best time to start a campaign. It is advised to avoid launching a campaign in October or November since the success rate decreases suddenly. The failure rate is steady over the course of the year, so the fail need not be addressed.

![Theater_Outcomes_vs_Launch](/Users/johnwhendricks/Desktop/classFolder/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
As seen in the line chart below, the theater campaigns that succeeded the most frequently were those that set their goal less than $5,000 - the success rate was roughly 65%. Nevertheless, theater campaigns that set a goal between $5,000 and $15,000 had success rate of roughly 55%. Beyond $15,000, the sucess rate plummets and the failure rate sharply rises, and these changes only reverse at goal of roughly $30,000, which is out of range of our client's budget. It should be noted that the fail rate steadily increases from $1,000 to $5,000 but then levels off from $5000 to $15,000. Therefore, a goal of $10,000 should not be changed in either direction because both the fail and success rates are steady between $5,000 and $10,000.

![Outcomes_vs_Goals](/Users/johnwhendricks/Desktop/classFolder/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

Outliers in the dataset increased the average goal and average pledge amounts, inhibiting data analysis. For example, some campaigns had outlandishly high percent funding rates - the campaign would set a goal of $1, likely because they needed a goal on paper, and when they received a small donation of, say, $100, the percent funding would amount to 10,000%. As a result, the outliers misrepresented the color scaling for the percent funding column. 

An analysis was to be performed on the blurb column, but some characters were not translated correctly from the csv file to the Excel file. Even without this issue, it would be difficult to turn the words into a variable that could be analyzed against the play outcomes. As a result, the wording of the fundraising blurs were not analyzed. Using Machine Learning, an analysis of the wording could be possible.

Another issue arrises when analyzing monetary data across different countries. Although the dataset is in dollars, the actually currency must be taken into account. For example, $100 in GBP is $126 in USD. In this project, there was no analysis of financial data between countries, but if Louise wished to compare the success of plays between Great Britain and the U.S., as she mentioned previously, then the currency would have to be accounted for. 

![Kickstarter_Challenge](/Users/johnwhendricks/Desktop/classFolder/CrowdfundingAnalysis/Kickstarter_Challenge.xlsx)

## Results

A majority of the campaigns that failed set their funding goals far higher than the successful campaigns. The average goal was $5,050 for successful US kickstarters, but $10,550 for the failed fundraisers. However, the average pledge was $5,600 for those that succeded versus $560 for those that failed, meaning the unsuccessful kickstarters failed due to factors other than setting the price range too high. Regardless of campaign success, the average money pledged was greater than the median pledged, meaning a small group of unusually successful campaigns skewed the data. Although our client suggested setting a funding goal of $10,000, this is closer to the amount set by failed campaigns. For the successful campagins, the average pledged was $5,600 with $3,200 being the 50th percentile. Because of the larger average from unusually succesful campaigns, it is reccomended that the fundraising goal be placed closer to between $3,000-$4000, as this range is within the scope of what donaters have given in the past.

In the U.S. from 2009-2017, fundraising for theaters experienced a higher success rate than that of any other category. Among musicals, plays and spaces, plays had the highest success rate as seen in the second bar graph. This means a fundraising for a play would likely succeed in the U.S.

![US-Stacked-Bar-Chart](/Users/johnwhendricks/Desktop/classFolder/CrowdfundingAnalysis/US-Stacked-Bar-Chart.png)
![US-Subcat-theater-stacked-bar-chart](/Users/johnwhendricks/Desktop/classFolder/CrowdfundingAnalysis/US-Subcat-theater-stacked-bar-chart.png)

Our client also expressed an interest in musicals. The box plot shows the distribution of musicals in Great Brigtain. Half the pledges ranged from 0.00-1,800.00 pounds, though 2,000 pounds was still within the interquartile range. Thus, a goal of 2,000 pounds would be a safer option for fundraising a musical in GB. Of the 5 plays that the client preferred, all succeeded. Each play occurred in Great Britain and were launched between May and July. The monetary goal ranged from 1,000-4,000 pounds, and the pledges exceeded their goals by 1% more up to 172% more. 

![Box-Plot-John-Hendricks](/Users/johnwhendricks/Desktop/classFolder/CrowdfundingAnalysis/Box-Plot-John-Hendricks.png)

In summary, initiating a kickstarter for a play in the early summer, especially the month of May, would likely be successful in the U.S, as long as the funding goal is not much larger than $10,000. Launching in June would be a viable second option.    
