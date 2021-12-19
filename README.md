# Kickstarting with Excel

## Overview of Project

#### The purpose of this analysis is two-fold – one, to analyze overall theater crowdfunding campaign outcomes based on the launch date of the campaign, and two, to analyze how theater crowdfunding campaign outcomes (in this case, specifically play outcomes) perform based on the dollar goal set for each campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

#### A pivot table was created to show the number of successful/failed/canceled theater campaigns by month (based on the month of the launch date of each campaign).  A pivot line chart was then created off of the data in the pivot table to reflect these results.

![image](https://user-images.githubusercontent.com/95199679/146692630-ee8c6468-a9aa-4811-9128-b71da559f214.png)

### Analysis of Outcomes Based on Goals

#### A table was created showing the number of successful/failed/canceled campaigns for plays only based on different $ ranges of target fundraising goals, and the subsequent percentages of successful/failed/canceled for each goal range.  The table used the *countifs* function to calculate each column of successful/failed/canceled campaigns based on each target goal range and the subcategory “plays”.

![image](https://user-images.githubusercontent.com/95199679/146692617-b6cfe423-5436-45a1-84b9-6bb4fdf24087.png)

### Challenges and Difficulties Encountered

#### I did not encounter any challenges with this project, however a couple of possible challenges I see are:
- If the "date created conversion" formula was calculated incorrectly, the "years" column would also be calculated incorrectly, since this column is calculated using values in the "date created conversion" column.

![image](https://user-images.githubusercontent.com/95199679/146692640-2a54b94e-2ecd-40ac-9378-de57eb67bebf.png)

- The “countifs” formula needs to be calculated using all of the correct criteria (using the correct operators and goal range values, ensuring to use the subcategory “plays” as a criteria) or else you will not calculate the correct data for the table and the chart will not be accurate.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

  1. Based on the data, campaigns launched in the summer months (particularly May and June) have the highest success rate.
  2. Based on the data, only about half of campaigns launched in December will be successful.

- What can you conclude about the Outcomes based on Goals?

  - Based on the graph, campaigns with goals less than $5,000 have a high successful percentage rate, roughly half of campaigns with goals within the $5,000-$25,000 range are successful, and there are not enough campaigns with goals larger than $25,000 to confidently conclude whether the campaign will be successful or not.

- What are some limitations of this dataset?

  - A big limitation of the dataset is the lack of more detailed levels of data – for example, there may be different outcomes based on the region analyzed within each country, the premise/subject matter of each play, etc. 

- What are some other possible tables and/or graphs that we could create?

  - Could create a bar chart for “outcomes based on goal” to show the number of failed vs successful campaigns for each goal range, rather than the % of successful vs failed – the percentages provide a bit of a skewed picture, as the sample size is very small for larger goal ranges, so the results should be interpreted with this context.
  - Could also create a graph showing outcome based on length of campaign instead of just start date.
