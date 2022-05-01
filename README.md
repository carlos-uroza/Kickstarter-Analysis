# Module 1 Challenge - Kickstarter Analysis

## Overview of Project

### Purpose

The purpose of this analysis is to determine the effectiveness of kickstarter fundraising campaigns for theatrical plays. Our customer, Louise, would like to find out how different campaigns fared in relation to their launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

In order to visualize campaign outcomes ("Successful", "Failed", and "Canceled"), this program generates a chart from a pivot table based on launch dates. Our analysis resulted in the following pivot chart:
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/103288980/166168889-8e1eae34-b48f-4b57-8838-4681dc0e3c2e.png)

### Analysis of Outcomes Based on Goals

In order to visualize the percentage of successful, failed, and cancelled plays; this program generates a chart based on the tiered funding goal amounts. The program applies the COUNTIFS() function to populate the table used to chart the outcome percentage (Y-Axis) and funding goal amount tiers (X-Axis). Our analysis resulted in the following line chart:
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/103288980/166168890-63d9f4b0-4076-4c00-8b48-c2b0bfff42a4.png)

### Challenges and Difficulties Encountered

- When using this program, please ensure only the correct filters are active as this could change the result of the analysis.
- If editing the COUNTIFS functions, please ensure the criteria range is inclusive as this could alter the percentages for each group.

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on the "Theater Outcomes Based on Launch Date" chart, we can conclude that May is on average the month with the most successful number of campaigns. The pivot chart generated during this analysis demonstrates theater campaigns were successful more often than they either failed or were cancelled.

### What can you conclude about the Outcomes based on Goals?
Based on the analysis of Outcomes based on Goals, we can conclude that most campaigns fall within the $1,000-$4,999 funding goal tier. The chart generated from our analysis demonstrates the first two tiers (<$1,000 and $1,000-$4,999) consists of the lowest percentage of failed campaigns for all ranges.

### What are some limitations of this dataset?
It is significant to note the goal amount values are provided as dollars. As the dataset camptures campaigns from different countries at different times, it is possible different exchange rates were used.
Another possible limitation of the dataset; the data contains uneven number of observations per year. For the "plays" subcategory, 2017 had 39 campaigns compared to 294 campaigns in 2016. This difference could skew our results in favor of certain years.

### What are some other possible tables and/or graphs that we could create?
Another analysis that could be of interest to the customer would be an evaluation of Outcomes based on lenght of the campaign. It is possible the amount of time a campaign is live has an influence on the pledged amount.
