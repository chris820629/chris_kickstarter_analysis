# Kickstarting with Excel

## Overview of Project

### Purpose
Understand the most ideal campaign launch dates and funding goal for Louise's play Fever

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The launch date was converted to year-month-date format first. A pivot table was generated from the Kickstarter tab sheet. The rows were dragged from the launch date (later filter to month unit), the columns use the outcomes. The values also use the outcome to count the total cases for each outcomes (succesful, failed, canceled). Since Louise's campaign is within theater category, the pivot table was later added with the theater filter. The pivot analysis chart was generated from this result. 
![Outcomes_vs_Goals.png](https://github.com/chris820629/chris_kickstarter_analysis/blob/main/Outcomes_vs_Goals.png)
### Analysis of Outcomes Based on Goals
Several formulas were used to perform this analysis
1. countifs was used to count the number of campaigns that fall into two scenarios (goal range and outcome)
2. Sum was used to calculate the total number of campaigns within each goal range
A line chart was later generated/inserted into the sheet 
![Theater_Outcomes_vs_Launch.png](https://github.com/chris820629/chris_kickstarter_analysis/blob/main/Theater_Outcomes_vs_Launch.png)
### Challenges and Difficulties Encountered
Challenge: when i first generated the chart, I used the scatter plot but it was not displaying the correct x-axis label (e.g. Less Than 1000). I later fixed it by changing the chart type to line chart. The x-axis was eventually showing the intended labels (texts in Goal column)
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Within theater category, May seems to be the month with highest number of successful campaigns as well as success rate 
2. The canceled campaigns seem to be constant across the entire year

- What can you conclude about the Outcomes based on Goals?
The best goal for Louise to list the campaign should be less tahn $24999. Beyond $24999 the percentage of failure starts fluctuates, winning over the success percentage. Hence goal of lower than $24999 will be the safest.
- What are some limitations of this dataset?
1. Seems like the data was only collected up to March 15th 2017
- What are some other possible tables and/or graphs that we could create?
1. The correlation of campaign duration vs. outcomes
2. What is the most succesful category in each country

