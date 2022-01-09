# Kickstarting with Excel

## Overview of Project

### Purpose
    The purpose of this analysis is to visualize how different Kickstarter campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
    I first used Excel formulas on the Kickstarter sheet to create the Subcategory, Parent Category, Years, and Launch Date columns. Then, I created a Pivot Table against this data. Finally, I created a Pivot Chart again to visualize the results.
    ![Pivot Table: Theater Outcomes](/resources/Pivot_Table_Theater_Outcomes.png)
    ![Chart: Theater Outcomes by Launch Date](/resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
    I used COUNTIFS formulas to calculate values in the Number Successful, Number Failed, and Number Canceled columns. Then, I created a Chart to visualize the results.
    ![Screen Shot of COUNTIFS Forumla](/resources/COUNTIFS_Formula_Plays_Outcomes.png)
    ![Chart: Outcomes Based on Goal](/resources/Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
    The difficulties I encountered include the conversion of the launch date timestamp from a unix format to a month, day, and year format. This was overcome by Googling a widely used Excel formula to perform this conversion. In addition, I Googled Excel formulas to separate text and obtain the parent category in one column and subcategory in another.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    Kickstarter campaigns in the Theater parent category were most successful in the month of May, followed by October. Failed campaigns and canceled campaigns occur relatively consistently throughout all months of the year.
- What can you conclude about the Outcomes based on Goals?
    As goal amounts increase, the number of successful Kickstarter campaigns in the Plays subcategory decrease. However, campaigns with goal amounts ranging from $35,000 to $45,000 fared surprisingly well, bucking the downward trend for higher amounts.
- What are some limitations of this dataset?
    The dataset does not include any qualitative data on why a campaign was canceled, or why the campaign failed to meet it's goal. In addition, this dataset does not include any information on the source of amounts pledged. For instance, it may be useful to see whether the amounts pledged came from a private donor, non-profit organization, corporation, government agency, etc.
- What are some other possible tables and/or graphs that we could create?
    One possible graph that might paint a more accurate picture on campaign performance is to calculate the difference between goal amount and amount pledged to see the over/under variance. A graph of this variance would provide a more detailed visualization of just how successful or unsuccessful a campaign performed. Another possible graph would be to analyze campaign performance based on parent category to look for seasonal trends in different industries. We could also analyze the countries in which these campaigns took place.
# kickstarter-analysis
