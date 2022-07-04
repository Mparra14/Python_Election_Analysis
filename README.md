# Python_Election_Analysis
## Overview of Election Audit: 

 Throughout this section we were given the task of finding the results of a Colorado precicnt elections by using Python. We were able to create a code that would iterate through all the votes, which were given to us by a CSV sheet, and find the candidate that won the election by popular vote. Not only were we able to find the candidate that won, but we also appended the code to find which county had the most voter turnout.  

## Election-Audit Results:

  In this election, we were given 3 counties in this precinct elections: Denver, Jefferson, and Arapahoe. We had to generate a vote count report that would include the winner of the election and which county had the largest number of voters. Please see below for the count report generated. 
  
![vote_count_report](https://github.com/Mparra14/Python_Election_Analysis/blob/main/Voter_Count_Report.png)

* Looking at the report, we can see the total amount of votes casted in this congressional election was 369,711.

* In the second part of our report, we see the counties and the number of votes casted in each county, as well as their percentage proportional to their number of votes. The first county is Jefferson with a 10.5% of votes and a total amount 38,855 of votes casted. The second, is Denver with an 82.5% of votes and a total amount of 306,055 of votes casted. The last county is Arapahoe, with a total 6.7% of votes and total of 24,801 of votes casted. We were able to get these results by using the code below, which can go through our dictionary of County_votes and that every time it sees a county it will count it becomes a variable known as county_vote. Once this is integrated in our equation, we can get a percentage, and then we are able to print this out as it appears on the report.

![county_votes_code](https://github.com/Mparra14/Python_Election_Analysis/blob/main/County_Votes.png)

* The county that had the largest amount of voter turnout was Denver. This can be seen in the vote report on the 3rd section. 

* In this precinct election, there were 3 candidates: Charles Casper Stockham, Diana Degette, and Raymon Anthony Doane. Starting with the first candidate Charles Casper Stockham, he recieved 23% of the votes and a total of 85,213 of votes casted. Our second candidate, Diana Degette received 73.8% of the votes and 306,055 of votes casted. The last candidate Raymon Anthony Doane received 3.1% of the votes and 11,606 of votes casted. These results came about us using the code below, which is very similar to the code we used to find the percentage and the total votes in each county. In this code, we were able to go through the candidate names in the candidate_vote dictionary and every time it found a candidate name it would count it and this became a votes variable that was able to be integrated in the equation to get the percentage and used in the print function with the F-string.

![Candidate_Vote](https://github.com/Mparra14/Python_Election_Analysis/blob/main/Candidate_votes.png)

* The candidate that won the election was Diana Degette; she recieved 73.8% of the votes and a total of 306,055 of total casted votes. You can say that she won by a very large margin in this precinct. 

## Election-Audit Summary: 

As it can be seen, using this code we were able to automate the election ballot results in this congressional precinct election in a matter of minutes, this makes the system of tallying votes much more efficient and less time consuming. one of the perks of using this code in python, specifically with VSC, if there was an error, we can find the root of that error and fix it, which is why this code became essential in these elections, and it can even help in other ways or other elections. Let's take this election for example, we could add a code that would be able to calculate which county corresponds to the highest percentage of candidate votes, meaning that we would be able to find which candidate was voted for the most in each county.

If we were to take this code and refactor it for local elections, we would have to add a few more variables since citizens are able to vote for several position in the local government. While the code itself would be much longer, it should not be a problem. Let's say that we were to create a variable for county of clerks, we would iterate through the ballots and find the row that is in, and we would create similar code to the one seen here, the only thing that would be different is that ballots might be in different sheets, we would just have to make sure that our code is looking directly in that sheet for that specific local role.


