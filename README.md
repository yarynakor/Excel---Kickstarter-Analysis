# Excel- Kickstarter Analysis 

In this task I am using the Excel table, modifying and analyzing the data of 4,000 past Kickstarter projects to uncover some market trends.

Using conditional formatting to fill each cell in the state column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

Creating a new column O called Percent Funded that uses a formula to uncover how much money a campaign made to reach its initial goal.

Using conditional formatting to fill each cell in the Percent Funded column using a three-color scale. The scale should start at 0 and be a dark shade of red, transitioning to green at 100, and blue at 200.

Creating a new column P called Average Donation that uses a formula to uncover how much each backer for the project paid on average.

Creating two new columns, one called Category at Q and another called Sub-Category at R, which use formulas to split the Category and Sub-Category column into two parts.

Creating a new sheet with a pivot table that will analyze your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

Creating a stacked column pivot chart that can be filtered by country based on the table I have created.
Creating a new sheet with a pivot table that will analyze initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

Creating a stacked column pivot chart that can be filtered by country and parent-category based on the table you have created.

The dates stored within the deadline and launched_at columns use Unix timestamps. Fortunately for us, there is a formula that can be used to convert these timestamps to a normal date.

Create a new column named Date Created Conversion that will use this formula to convert the data contained within launched_at into Excel's date format.

Create a new column named Date Ended Conversion that will use this formula to convert the data contained within deadline into Excel's date format.
Create a new sheet with a pivot table with a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years.

Now create a pivot chart line graph that visualizes this new table.

Create a report in Microsoft Word and answer the following questions.

Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?
What are some limitations of this dataset?
What are some other possible tables and/or graphs that we could create?

Bonus
Create a new sheet with 8 columns:

Goal
Number Successful
Number Failed
Number Canceled
Total Projects
Percentage Successful
Percentage Failed
Percentage Canceled

In the Goal column, create 12 rows with the following headers:

Less than 1000
1000 to 4999
5000 to 9999
10000 to 14999
15000 to 19999
20000 to 24999
25000 to 29999
30000 to 34999
35000 to 39999
40000 to 44999
45000 to 49999
Greater than or equal to 50000

Using the COUNTIFS() formula, count how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the Number Successful, Number Failed, and Number Canceled columns with this data.

Add up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.

Create a line chart that graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.
