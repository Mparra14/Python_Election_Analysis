# Python_Election_Analysis
## Overview of Election Audit: 

 Throughout this section we were given the task of finding the results of a Colorado precicnt elections by using Python. We were able to create a code that would iterate through all the votes, which were given to us by a CSV sheet, and find the candidate that won the election by popular vote. Not only were we able to find the candidate that won, we also appended the code to find which county had the most voter turnout.  

## Election-Audit Results:

  In this particular election, we were given 3 counties in this precinct elections: Denver, Jefferson, and Arapahoe. We had generate a vote count report that would include the winner of the election and which county had the largest amount of voters. Please see below for the count report generated. 
  
![vote_count_report](https://github.com/Mparra14/Python_Election_Analysis/blob/main/Voter_Count_Report.png)
* Looking at the report, we are able to see the total amount of votes casted in this congressional election was 369,711.
* In the second part of our report, we see the counties and the amount of votes casted in each county, as well as their percentage proportional to their amount of votes.The first county is Jefferson with a 10.5% of votes and a total amount 38,855 of votes casted. The second, is Denver with an 82.5% of votes and a total amount of 306,055 of votes casted. The last county is Arapahoe, with a total 6.7% of votes and total of 24,801 of votes casted. We were able to get these results by using the code below, which is able to go through our dictionary of County_votes and that everytime it sees a county it will count it becomes avariable known as county_vote.Once this is integrated in our equation we are able to get a percentage, and then we are able to print this out as it appear on the report.

  
Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

*Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
*Which county had the largest number of votes?
*Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
*Which candidate won the election, what was their vote count, and what was their percentage of the total votes?


Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.
