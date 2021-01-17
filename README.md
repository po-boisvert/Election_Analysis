# Election_Analysis

## Overview of Election Audit

A Colorado Board of Elections has given you the following tasks to complete the election audits of recent local congressional election.

- Calculate the total number of votes cast.
- Get a complete list of candidates who received votes.
- Calculate the total number of votes each candidate received.
- Calculate the percentage of votes each candidate won.
- Determine the winner of the election based on popular vote.

## Ressources

- Data Source: election_results.csv (Resources folder)
- Python (3.8.5) and the editor Visual Studio Code (1.52.1)

## Election Audit Results

### Total votes

- This election aggregated a total of 369,711 votes.

### The candidates list (total of 3)

- Charles Casper Stockham
- Diana DeGette
- Raymon Anthony Doane

### The vote result

The first step of this analysis is to aggregate the votes for each candidate in order to audit and confirm a winner (if possible).

#### Figure 1: votes aggregated by candidates

<img src="https://github.com/poboisvert/Election_Analysis/blob/main/Ressources/Statistics.png" width="300" />

From the election_results.csv, we aggregate row by row the Ballot ID and the candidate. Below is the summaary after having used the aggregation method:

- Charles Casper Stockham received 23.0% of vote and 85,213 number of votes.
- Diana DeGette received 73.8% of vote and 272,892 number of votes.
- Raymon Anthony Doane received 3.1% of vote and 11,606 number of votes.

### Candidate conclusion

By having only three counties and three candidates, the distribution give us a clear outpout on the votes. The figure 1 let us know the winner which is:

- Diana DeGette received 73.8% of vote and 272,892 number of votes.

### Additional information (Challenge Overview)

With the previous information analyzed, the election commission has requested some additional data to complete the audit:

- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout

The election was done in three county (Jefferson, Denver and Arapahoe). Below is a comprehensive summary to understand the distribution of the votes accross the counties.

#### Figure 2: votes aggregated by county

<img src="https://github.com/poboisvert/Election_Analysis/blob/main/Ressources/election_analysis.png" width="300" />

Again, to confirm additional information, we used the election_results.csv and we aggregate row by row the Ballot ID and the county associated to it. After considering the figure 2, we can conlude:

- Jefferson aggregated 10.5% of vote or 38,855 votes.
- Denver aggregated 82.8% of vote or 306,055 votes.
- Arapahoe aggregated 6.7% of vote or 24,801 votes.

### County conclusion

The heawiest county across all is Denver (the largest turnout) with a total of 306,055 votes on a total of 369,711 votes. This tell us that if a candidate win Denver; he will mostly win the campaign.

## Election Audit Summary

This project provide an easy way to quickly determine the weight of each county when analysing an election and aggregate the vote for each candidate. Improvement could be (1) a additional input at the beginning to manually type the candidate name and select the data file that include the vote and (2) an additional script that generate the most popular candidate by county will give an insight on the county winner against the overall winner.
