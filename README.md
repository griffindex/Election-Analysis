# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.
In this project, our final Python script will need to be able to deliver the following information when the script is run: 

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes for each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Calculate the voter turnout for each county.
7. Calculate the percentage of votes from each county out of the total.
8. Determine the county with the highest turnout.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.60

## Election Audit Results
The analysis of the election shows that:

- There were 369,711 votes cast in the election.

- The candidates were:

    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:

    - Charles Casper Stockham received 23.0% of the vote, for a total of 85,213 votes.
    - Diana DeGette received 73.8% of the vote, for a total of 272,892 votes.
    - Raymon Anthony Doane received 3.1% of the vote, for a total of 11,606 votes.

- The winner of the election was:

    - Diana DeGette, who received 73.8% of the vote for a total of 272,892 votes.

- The voter turnout for each county was:
    - Jefferson county had a turnout of 38,855 voters which was 10.5% of the vote.
    - Denver county had a turnout of 306,055 voters which was 82.8% of the vote.
    - Arapahoe county had a turnout of 24,801 voters which was 6.7% of the vote.

- The county with the largest voter turnout was:
    - Denver county, which had 306,055 voters and 82.8% of the vote.

![Image of Election Results txt file](/resources/election_results.png)

## Election Audit Summary

This script demonstrates that Diana DeGette won the election by recieving 73.8% of the all votes with 272,892 total votes and how each county voted. The script can be used as-is with .csv files that are formatteed with the header rows Ballot ID, County, Candidate to verify election results. This means that a different csv file that includes different election data will produce a .txt file of results in the same format. Alternatively, another decision statement can be added to narrow down what percentage of the turnout in each county voted for a candidate. It can also be used to allocate resources to counties with low voter turnout in the next election season by renaming the variables associated with Line 112 and changing the if statement to calculate the county with the lowest turnouot. Overall, using a python script to iterate through a .csv file with a large amount of rows is an efficient way to audit election data and generate insights about current and future election outcomes.
