# Module_1_Kickstarter_Analysis

Title:  
Kickstarter: What Is the Best Month To Launch ‘Fever’ Fundraising Campaigns and For What Goals Amounts? 

Overview of Project:
A play called Fever had many fundraising sources.  The purpose of the analysis is to see how different fundraising campaigns performed in relation to their launch dates and funding goals using Kickstarter data set.  Based on the analysis, what would be the recommendation.
Analysis was done using excel pivot tables and pivot charts.

Outcomes Based On Launch Date:
To perform analysis regarding fundraising outcomes based on launch dates, I  created a pivot table, and filtered by “Parent Category” and “Years”.  Then filtered column labels to show “success”, “failed”, and “cancelled”.  Grouped row labels to show months of the year.  
Did another filter from the “Parent Category” to show “theater”. Created a line chart with filtered results.

Outcome/Results: Resulting analysis shows that the most successful campaigns launched in May, June second.  October is not a good month for launch since it shows as themonth with the most failed
launch.

Outcomes Based On Goals:
First, created the following columns to hold data: Goal, Number Successful, Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed, Percentage Canceled. Filtered “outcome” column from goal column.  
I used countifs() function to populate Number Successful, Number Failed, Number Canceled.  I used Sum() function to populate “Total Projects” column.  The rows are the number of successful, failed, and canceled projects. Pivot chart was then used to visualize the results.

Outcome/Results:
Analysis shows that there are more successfull campaigns (in number) with fundraising of goals of less than $1000k.  However, percentagewise, fundraising campaigns with goals 
more than $50,000 have the highest percentage of failure. 
