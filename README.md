
# Kickstarting with Excel: Kickstarter Theater Project<!--Photo below by Donald Tong from Pexels-->
<img src="https://github.com/tn64/kickstarter-analysis/blob/main/Resources/pexels-donald-tong-109669-edited.png" width="1000">


## Overview of Project

### Purpose
In the assignment, we were asked to perform analysis using Excel formulas to analyze the data provided for a client who was considering using a Kickstarter campaign to raise funds for the production of an original play. The analysis was intended to analyze data regarding successful Kickstarter campaigns, with specific consideration given to launch date and funding goals. By using Excel formulas we were able to filter and format the data, create pivot tables and charts to make the data more visual and therefore easier to understand.

## Analysis and Challenges

1. Performing the Analysis

After adjusting the data supplied (i.e. changing Unix timestamp to date, then retrieving the year from the "Date Ended" coulumn, and separating subcategories from parent categories)  we were able to filter for successful kickstarter campaigns by "Launch Date"b(date created, column S) and "Goals" (funding goals, colun D). The new Excel file is linked
<a href="https://github.com/tn64/kickstarter-analysis/blob/af8e8cfd43a39504ecf5075b5405f3f4599cd196/Kickstarter_Challenge.xlsx" target="_blank">here.</a>


We then created new Excel sheets for a variety of analyses. Specifically, we created sheets to analyze "Theater Outcomes by Launch Date" and "Outcomes Based on Goals". For "Theater Outcomes by Launch Date" we created a pivot table to fliter by the parent category "theater" by the year the Kickstarter campaings were launched (then narrowing to the months in which they were initiated), generating columns for whether the campaign was "successful," "failed," or "canceled" (and generating the total number for each category).
We found that the three best months to launch a campaign were May, June, and July (with the highest success in May, followed by June, and then July). You can see the chart generated here:

<img src="https://github.com/tn64/kickstarter-analysis/blob/af8e8cfd43a39504ecf5075b5405f3f4599cd196/Resources/Theater_Outcomes_vs_Launch.png">

We further analyzed the outcomes based on the fundraising goal for the subcategory "plays". To do this we segmented the goals in $5000 increments and determined the number of successful, failed and canceled campaigns. This would help the client to understand the likelihood of success of their campaign when compared to the success (or lack thereof) of other plays with similar funding goals. You can see the chart generated here:

<img src="https://github.com/tn64/kickstarter-analysis/blob/af8e8cfd43a39504ecf5075b5405f3f4599cd196/Resources/Outcomes_vs_Goals.png">

2. Challenges/Possible Difficulties

The biggest challenge faced was sloppy typing! Other possibile difficulties might be lack of familiarity with Excel functions. Fortunately, there is a significant amount of help via Excel's documentation, other websites, and even YouTube channels that is readily available via Google search.


### Analysis of Outcomes Based on Launch Date

1. Funding Goals

The analysis of outcomes based on funding goals (see chart above) shows that campaings with goals over $5,000-$9,999 have a 50-50 chance of success. Given that $5,000 is on the low end of what it costs to produce a play (and was significantly below the scenario in the module), additional forms of fundraising would need to be implemented to reach the goal.

2. Launch Date

The analysis of launch dates by outcome (see chart above) indicates that May and June are the most successful launch months. The also have they not only have highest number of successful campaigns, they also have the highest number of campaign launches.


## Results

- Conclusions based on Launch Date
1. The two months in which the higest number of successful campaigns were launched are May and June.
2. The two months with the highest number of campaigns being launced are also May and June

- What can you conclude about the Outcomes based on Goals?
1. Campaigns with a goal lower that $5,000 had a better than 50-50 chance of success.
2. For a play with a fundraising goal such as envisioned in the module, other forms of fundraising will likely be necessary for the total funding goal to be met.

- What are some limitations of this dataset?
1. The data set does not include information on marketing plans.
2. The data set only includes "country" information. Additional, more "regional" data might be helpful for individual campaigns

- What are some other possible tables and/or graphs that we could create?
