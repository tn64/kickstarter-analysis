
# Kickstarting with Excel: Kickstarter Theater Project<!--Photo below by Donald Tong from Pexels-->
<img src="https://github.com/tn64/kickstarter-analysis/blob/main/Resources/pexels-donald-tong-109669-edited.png" width="1000">


## Overview of Project

### Purpose
In the assignment, we were asked to perform analysis using Excel formulas to analyze the data provided for a client who was considering using a Kickstarter campaign to raise funds for the production of an original play. The analysis was intended to analyze data regarding successful Kickstarter campaigns, with specific consideration given to launch date and funding goals. By using Excel formulas we were able to filter and format the data, create pivot tables and charts to make the data more visual and therefore easier to understand.

## Analysis and Challenges

**1. Performing the Analysis**

After adjusting the data supplied (i.e. changing Unix timestamp to date, then retrieving the year from the "Date Ended" column, and separating subcategories from parent categories)  we were able to filter for successful kickstarter campaigns by "Launch Date" (date created, column S) and "Goals" (funding goals, column D). The new Excel file is linked
<a href="https://github.com/tn64/kickstarter-analysis/blob/af8e8cfd43a39504ecf5075b5405f3f4599cd196/Kickstarter_Challenge.xlsx" target="_blank">here.</a>


We then created new Excel sheets for a variety of analyses. Specifically, we created sheets to analyze "Theater Outcomes by Launch Date" and "Outcomes Based on Goals". For "Theater Outcomes by Launch Date" we created a pivot table to fliter the parent category "theater" by the year the Kickstarter campaings were launched (then narrowing to the months in which they were initiated), generating columns for whether the campaign was "successful," "failed," or "canceled" (and generating the total number for each category).
We found that the three best months to launch a campaign were May, June, and July (with the highest success in May, followed by June, and then July). You can see the chart generated here:

<img src="https://github.com/tn64/kickstarter-analysis/blob/af8e8cfd43a39504ecf5075b5405f3f4599cd196/Resources/Theater_Outcomes_vs_Launch.png">

We further analyzed the outcomes based on the fundraising goal for the subcategory "plays". To do this, we segmented the goals in $5000 increments and determined the number of successful, failed, and canceled campaigns. This would help the client to understand the likelihood of success of their campaign when compared to the success (or lack thereof) of other plays with similar funding goals. You can see the chart generated here:

<img src="https://github.com/tn64/kickstarter-analysis/blob/af8e8cfd43a39504ecf5075b5405f3f4599cd196/Resources/Outcomes_vs_Goals.png">

**2. Challenges/Possible Difficulties**

The biggest challenge faced was sloppy typing! Other possibile difficulties might be lack of familiarity with Excel functions. Fortunately, there is a significant amount of help via Excel's documentation, other websites, and even YouTube channels that is readily available via Google search.


### Analysis of Outcomes Based on Launch Date

**1. Funding Goals**

The analysis of outcomes based on funding goals (see chart above) shows that campaings with goals over $10,000 have a less than 50% chance of success. Those contemplating a Kickstarter campaign to raise a larger amount may need to seek additional funding to reach their goal.

**2. Launch Date**

The analysis of launch dates by outcome (see chart above) indicates that May and June are the most successful launch months. Not only do they have the highest number of successful campaigns, they also have the highest total number of campaign launches.


## Results

**- Conclusions based on Launch Date**

1. Because the two months in which the higest number of successful campaigns were launched are May and June, Kickstartr campaings for plays should be ready to launch in one of those months, preferable in May.
2. The two months with the highest number of campaigns being launced are also May and June

**- Conclusion drawn from Outcomes based on Goals:** Campaigns with a goal lower that $10,000 had a 50% or greater chance of success. For campaigns with higher goals, other factors should be addressed such as the marketing plan for the campaign and, perhaps, other forms of fundraising in order to meet the total fundraising goal.

**- Limitations of the dataset**

1. The data set does not include information on marketing plans.
2. The data set only includes "country" information. Additional "regional" data might be helpful for individual campaigns

**- Other possible tables and/or graphs**

1. It may be helpful to create table to show the range of donation amounts for successful campaigns.
2. It may also be helpful to create another chart showing the length of time the kickstarter campaigns lasted for successful campaigns.
