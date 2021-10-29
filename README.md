# Kickstarting with Excel

## Overview of Project

### Purpose

#### The purpose of this analysis is to generate visualizations to help Louse understand how different campaigns faired in relation to their launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

#### The first analysis of outcomes was based on launch date of campaigns by using pivot table. With the use of pivot table, only theater campains were selected based on launch months and total number of corresponding campaign results was visualized. Below illustration shows the theater outcomes based on launch date. Link to the spreadsheet is as below:

https://github.com/davidbaek90/kickstarter-analysis/raw/main/Kickstarter_Challenge.zip

![Theater_Outcomes_vs_Launch](https://raw.githubusercontent.com/davidbaek90/kickstarter-analysis/main/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals

#### The second analysis of outcomes is the outcome in percentage, based on campaign goals. For this analysis, line graph is used to visualize the relationship between the two inputs.

![Outcomes_vs_Goals](https://raw.githubusercontent.com/davidbaek90/kickstarter-analysis/main/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

#### The most prominent challenge that I encountered during creation of the pivot table. Without following the module instructions I would have easily made mistakes by mixing up placing correct parameters in the pivot table fields. Another mistake that could be made is switching the row and column data on the line graph.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - The first conclusion is that the total number of failed campaigns in the theater catogory remained relative consistant. Second conclusion is that the most successful theatrical campaigns launched in May, and campaigns were generally successful in the warmer months.

- What can you conclude about the Outcomes based on Goals?
  - Generally speaking, less ambitious campaigns tend to be most successful. Risk of not succeeding in the campaigns increase as amount of goal increases. Goals in the 35000 to 39999 and 40000 to 44999 range peaked, however the number of campaigns in this range is not sufficient enough to be accounted into the conclusion.

- What are some limitations of this dataset?
  - The number of calcelled data in the "Theatre Outcomes Based on Launch Date" is missing from the dataset, which could potentialliy impact the trend especially during the month of October where both successful and failed number of campains tend to peak locally. For the "Outcomes Based on Goals", the duration of the campaign (end date minus start date) is not consistant. Longer campaigns might be more successful because it can prolong the campaign long enough to raise close to the goal. Hence, it is not the most fair method to compare the success between the campaigns.

- What are some other possible tables and/or graphs that we could create?
 - We could create a pie graph to show a pattern of demographic outcome based on location. This way we could possible conclude certain countries might show successful campaign results compared to another. We could also reinfor our previous graphs with histogram that shows a rate of success based on the duration of the campaign held. This way we could look at multiple other variables that impacts the success of the campaigns.
