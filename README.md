# Election_Analysis

## Overview
The purpose of this analysis is to create an automated process using Python that can be used to audit elections. More specifically, it will report the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, and the winner of the election based on the vote count. It then aims to provide an analysis of votes based on county by returning the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout. 

## Election Audit Results
- Total Votes: 369,711
- County Votes:
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)
- Denver county had the largest number of votes.
- Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)
- Diana DeGette won the election with 272,892 votes and 73.8% of the total votes.

## Election Audit Summary
This script can be used to audit any election by changing the file path located in line 9 to reference the .csv file containing the results that you would like to analyze. One way the script could be modified is by making it more simple and intuitive for someone unfamiliar with coding to import their csv file. It can also be modified, as mentioned above, by changing the file path located in linee 9 to reference a new .csv file.
