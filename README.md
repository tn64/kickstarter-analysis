
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
Explain any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered.

### Analysis of Outcomes Based on Launch Date
What are two conclusions you can draw about the Theater Outcomes by Launch Date?
1. Conclusion 1
2. Conclusion 2


### Analysis of Outcomes Based on Goals
What can you conclude about the Outcomes based on Goals?

### Challenges and Difficulties Encountered 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. 
2. 

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
