# Kickstarting with Excel- Modul 1 

## Overview of Project
Louise is getting closer to launching  the campaign for a play "Fever" with the budget $10000. Based on the data from "Kickstarter_Challenge" on similar campaigns, it will be determined what would be  the best time  to launch the campaign and predict the success of it based on the fundraising goal.  

### Purpose
The goal is to identify what's the outcome for different campaigns based on their funding goals and lunch dates, and predict the success of Louise's campaign.

## Analysis and Challenges

The "Kickstarter" database  was utilized for my analysis. I used pivot tables to summarize and analyze the  data. The  graphs were used to visualize  findings and identify trends. 

I’ve created 'Theater Outcomes by Launch Date' Pivot table to identify which month was the most successful to launch the campaign for the Parent category "Theater". The conclusion was made based on the data on 1369 campaigns that were launched from 2009 to 2017. The only challenge I had was that I didn't know how to get rid of Year and Quarter in  the Pivot table. The solution is to use the Grouping function. 

Pivot table 'Outcomes Based on Goals"  was created to identify if there is any relation between fundraising goal and the success, failure and cancellation of the campaign for theater play. I used the COUNTIFS formula with the conditions to separate plays  from other subcategories, set the goal range and separate the outcomes. I forgot to put one of the conditions ("plays' '), and then had to go back and fix each and every formula. The other challenge I had was that my graph didn't reflect  all lines. It appeared I picked the wrong 2 D line graph. The issue was resolved  when I switched from "100% Stacked line with Marks" to "Stacked line with Marks". 

### Analysis of Outcomes Based on Launch Date
Based on my Analysis, May is the month that launched the most of the theater campaigns and most of them were successful. If we look into the numbers, 166 campaigns were launched and 111 of them were successful. 67% of the theater Kickstartes became successful. December is the worst month to start the campaign, there will be only a 49% chance it will be successful. 

### Analysis of Outcomes Based on Goals

Based on my Analysis, most of the campaigns had a goal between 1000 and 4999. 73% of them became successful. It's interesting  that  campaigns with even lower goals ( less than 1000), had an even higher success rate - 76%. The trend I identify is that the higher the goal, the lower is  chance to succeed. Louise might need to reassess the goal. Her initial budget was $10000. 


## Results

Based on Launch Date Outcomes pivot table and data visualization images, I'd like to advise Louise to launch her campaign in May, the latest June. As we see on the graph, the worst month to launch the campaign is December. Based on Goals analysis outcomes, I'd advise Loise to reevaluate her funding raise goal and lower it to $4000 or raise it at least to 35000-45000. The trend is that most of the successful campaigns had the lowest goals. 

I think we need  to know some of the other variables to make a better prediction like the genre of the plays. 

I'd also create a pivot table and a graph to  compare the goal of the pledge based on the backers count. 



