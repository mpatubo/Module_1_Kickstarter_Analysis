# Module_1_Kickstarter_Analysis

Title:  
Kickstarter: What Is the Best Month To Launch ‘Fever’ Fundraising Campaigns and For What Goal Amounts? 

Overview of Project:
A play called Fever had many fundraising sources.  The purpose of the analysis is to see how different fundraising campaigns performed in relation to their launch dates and funding goals using Kickstarter data set.  Based on the analysis, what would be the recommendation.
Analysis was done using excel pivot tables and pivot charts.

Outcomes Based On Launch Date:
To perform analysis regarding fundraising outcomes based on launch date created a pivot table, and filtered by “Parent Category” and “Years”.  Then filtered column labels to show “success”, “failed”, and “cancelled”.  Grouped row labels to show months of the year.  Did another filter from the “Parent Category” to show “theater”. Created a line chart with filtered results.

Outcome/Results: Visualization shows that the most successful campaigns launched in May.  

Outcomes Based On Goals:
First, created the following columns to hold data: Goal, Number Successful, Number Failed, Number Canceled, Total Projects, Percentage Successful, Percentage Failed, Percentage Canceled. Filtered “outcome” column from goal column.  Used countifs() function top populate Number Successful, Number Failed, Number Canceled. Used Sum() function to populate “Total Projects” column.  The rows are the number of successful, failed, and canceled projects. Used pivot chart to visualize the results.

Outcome/Results: The successful campaigns were those with goals between $35000 and $45000.  The most failures were those with goals $25000 to $30000.  The highest number of failures were those with goals more than $50,000.   

Conclusion/Recommendation:  Analysis shows that May is the best month to launch fundraising campaigns for the play.   Furthermore, the successful campaigns tend to have goals between $35000 and $45000. So for future planning, one recommends to start fundraising campaigns in May with fundraising goals between $35000 to $45000.   
