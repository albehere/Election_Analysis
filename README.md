#For Module 3 of UofT Data bootcamp 
#Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Calculate the number of votes for each county
6. Determine the County with the highest turnout
7. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio code, 1.38.1

## Election-Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- County Turnout was 
  1. Jefferson: 10.5% (38,855)
  2. Denver: 82.8% (306,055)
  3. Arapahoe: 6.7% (24,801)
- Denver had the most votes.
- The candidates were
  1. Charles Casper Stockham
  2. Diana DeGette
  3. Raymon Anthony Doane

-The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.

-The winner of the election was:
  -Diana DeGette who received 73.8% of the vote and 272,892 number of votes.
  
  ## Election-Audit Summary
The script produced can be used for more than the just this election. The script picks up the names of the counties and the total votes from the source data. If in the future the results of the votes are tabulated in the same format as the source data then it can be fed into the exact script for results.

The script could be modified to fit other elections. If the election source data included spoiled ballets or null votes, then the code could be modified to take that into account. If there are additional hierarchy of vote counting areas, then blocks of code like the one used to count the counties could be added. 

