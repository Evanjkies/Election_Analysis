# Election_Analysis

## Project Overview
A Colorado Board of ELections employee has given you the following tasks to complete the election audit of a recent local congressional election

1. Calculate the total number of votes cast
2. Get a complete list of candidates who received votes
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_resulsts.csv
- Software: Python 3.7.6, Visual Studio Code, 1.38.1

## Summary
The analysis of the election show that:
- There were 369711 votes cast in the election
- The candidates were
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23% of the vote and 85213 votes
  - Diana DeGette received 73.8% of the vote and 272892 votes
  - Raymon Anthony Doane received 3.1% of the vote and 11606 votes
- The winner of the election was:
  - Diana DeGette who received 73.8% of the vote and 272892 votes
  
## Challenge Overview
In this section the objective was to establish the various characteristics about the county data in this election

1. Establish which counties took part in the vote
2. Determine how many votes each county receives
3. Calculate whhat percent of the total vote each county was responsile for
4. Determine the county that had the highest percent of the voter turnout

## Challenge Summary
The analyis of the county voting data show that:
- Jefferson, Denver and Arapahoe were the counties that had votes recorded
- Jefferson had 10.5% of the vote, Denver has 82.8% of the vote, and Arapahoe had 6.7% of the vote
- The largest county turnout was Denver with 306,055 votes accounting for 82.8% of the total vote

## Buisiness Proposal
I believe that this code could be applied to larger sets of election data with more candidates as well as more variables such as voter charateristics. If information about a voter such as their age or gender were to be added to the data set, another set of variables can be added at the top and with another for loop and a simple if statement, we could break down the data by gender or age range. This would prove useful to determine how a candidate polled amongst certain crowds. Another small piece of code that could be added to make the information more easily accessable would be the winning margin. This would jus take an additional condition to the existing loop that determines the winner where a second place finisher is established and then the votes assigned to this candidate name can be pulled from the ky as well as the percentage of votes accounted for by this candidate, and they can be subtracted from the winners same variable amounts.
