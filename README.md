# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends in the theatre category

## Overview of Project
### Purpose
I conducted analysis through excel, based on Kickstarter data I downloaded in order to help an up-and-coming playwright named Louise. She is looking to start a campaign for her play, Fever. As this is Louise's first experince with Kickstarter and her budget for the play is ~$10,000 she wants to ensure she sets her campaign up for success. I leveraged excel to help her determine the specific factors (i.e funding goal, duration of campaign, date of campaign, etc.) that have made play campaigns successful in the past.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
The launch date of Kickstarter campaigns that fell under the 'theatre' category was analyzed in the dataset to determine if this date has any relationship to campaign success. The data included years 2009-2017 and the launch dates were aggregated by month. Campaign outcomes were categorized by 'successful', 'failed', and 'canceled'. The results of this filtering and categorization are summarized in the line graph below.
![Theatre_Outcomes_vs_Launch](https://github.com/asliwinski23/Kickstarter-Analysis/blob/main/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Another factor that was examined in order to see if there was a relationship to campaign success was funding goal. In the analysis of this factor, we filtered by the 'plays' subcategory. Then, 12 buckets were created for goal amounts in the dataset. Campaign outcomes were again categorized by 'successful', 'failed', and 'canceled'. The results of this filtering and categorization are summarized in the line graph below.
![Outcomes_vs_Goals](https://github.com/asliwinski23/Kickstarter-Analysis/blob/main/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
I had a bit of trouble creating PivotTables to include all of my columns in both of my analyses. Another issue I faced when creating my 'Outcomes Based on Goal' chart above was the '5000 to 9999' bucket data to populate correctly in the chart. The data for this bucket continually showed 0. The solution to both of these issues was to repeat the process multiple times until either all of the column heads populated into my PivotTable sidebar or the goal data began to be pulled correctly. 

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?

Theatre campaigns launched in warmer months tend to have higher success rates, notably May and June. Launch date appears to affect success rate more than failure and cancel outcomes. The failure and cancel lines on the 'Theatre Outcomes Based on Launch Date' graphs are fairly stagnant. Perhaps more volatility could be seen if we had broken the data down by year AND month.

- What can you conclude about the Outcomes based on Goals?

No Kickstarter plays were canceled between 2009-2017. There is a lot of volatility to the 'Outcomes Based on Goal' line graph. On the extreme ends of the graph (<1000 and >50000 buckets) we see the trend that higher goals tend to fail for plays and lower goals tend to have a successs rate of almost 80%. The area where Louise's budget fits in seems relatively inconclusive about whether her campaign will succeed or fail based on her $10,000 funding goal. However, the graph seems to favor success over failure of projects with a goal of $0-$14999. So, we would advise Louise to not go above her $10,000 budget. 

- What are some limitations of this dataset?

It was extremely interesting to dive into the downloaded Kickstarter dataset. However, there are definitely some limitations to the data. For example, when investors decide to invest in a dataset, the accomplishments of the person launching the campaign are undoubtedly brought into consideration. Some other factors that would have enriched our analysis would be market conditions (i.e recession, bull, or bear), investor types, play types (drama, horror, etc.) and perhaps marketing strategies (i.e. Twitter or other social media platforms). In terms of the dataset used for this analysis, it should have been filtered in the same way for the two analyses. Meaning, the launch-date-based analysis was filtered by category (theatre), but the goal-based analysis was filtered by subcategory (plays).

- What are some other possible tables and/or graphs that we could create?

Additionally, other tables/graphs could have been created to paint a clearer picture of what makes for a successful campaign. For example, it would have been useful to create a chart to graph how the duration of a campaign is linked to its success. Comparison charts for different, but similar categories such as 'film and video' or 'music' would be interesting as well. If campaigns in these categories have a higher success rate, then perhaps Louise could market her play to appeal to a larger audience of people who enjoy film or music.
