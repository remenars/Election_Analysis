# Election Analysis

## Overview of Election Audit

The purpose of this election audit is provide the election commission some additional data. They would like to know the voter turnout for each county, the percentage of votes from each county compare to the total count of votes, and the county with the highest voter turnout

## Election-Audit Results

* There were a total of 369,711 votes cast in this congressional election
* The breakdown by county:
  * Jefferson County had 10.5% of the total votes (38,855)
  * Denver County had the largest number of votes with 82.8% of the total votes (306,055)
  * Arapahoe County had 6.7% of the total votes (24,801)
* The breakdown by candidate:
  * Charles Casper Stockham had 23% of the total votes (85,213)
  * Diana DeGette: had 73.8% of the total votes (272,892)
  * Raymon Anthony Doane had 3.1% of the total votes (11,606)

Diana DeGette won the election 73.8% of the total votes or 272,892 votes.

## Election Audit Summary

This script can be used for any election as long as the csv file is updated with new election information and retains the same columns. The script doesn't necessarily have to change if the csv file is overwritten with new election information. If not, one needs to execute the script in a folder that contains a Resources folder and an analysis folder. The election data needs to be a csv file saved in the Resources folder. if it is not named election_data, the script will need to be updated to replace the old file name with the new file name (lines 36 and 37).
