# Election_Analysis

## Project Overview

A Colorado Board of Elections has given you the following tasks to complete the election audits of recent local congressional election.

- Calculate the total number of votes cast.
- Get a complete list of candidates who received votes.
- Calculate the total number of votes each candidate received.
- Calculate the percentage of votes each candidate won.
- Determine the winner of the election based on popular vote.

## Ressources

- Data Source: election_results.csv (Resources folder)
- Python (3.8.5) and the editor Visual Studio Code (1.52.1)

## Summary

### Total votes

- There we 369,711 votes cast in the election.

### The candidates

- Charles Casper Stockham
- Diana DeGette
- Raymon Anthony Doane

### The candidate results

#### Figure 1: votes summary by candidates

<img src="https://github.com/poboisvert/Election_Analysis/blob/main/Ressources/Statistics.png" width="300" />

- Charles Casper Stockham received 23.0% of vote and 85,213 number of votes.
- Diana DeGette received 73.8% of vote and 272,892 number of votes.
- Raymon Anthony Doane received 3.1% of vote and 11,606 number of votes.

The winner of this election was:

- Diana DeGette received 73.8% of vote and 272,892 number of votes.

## Challenge Overview

With the previous information analyzed, the election commission has requested some additional data to complete the audit:

- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout

This additional information will provide a deeper insight on where the major votes come and will tell us the weight of each county.

## Challenge Summary

The election was done in three county (Jefferson, Denver and Arapahoe). Below is a comprehensive summary to understand the distribution of the votes accross the counties.

#### Figure 2: votes summary by county

<img src="https://github.com/poboisvert/Election_Analysis/blob/main/Ressources/election_analysis.png" width="300" />

After considering the figure 2, we can conlude: 

- Jefferson aggregated 10.5% of vote or 38,855 votes.
- Denver aggregated 82.8% of vote or 306,055 votes.
- Arapahoe aggregated 6.7% of vote or 24,801 votes.

The heawiest county across all is Denver (the largest turnout) with a total of 306,055 votes on a total of 369,711 votes. This tell us that if a candidate win Denver; he will mostly win the campaign.
