# Election_Analysis
Module3 Assignment - Python

**Overview of Election Audit:**
The source file contains data for each ballot cast for a county and candidate. 
The goal is to analyze this data from source file and find out the following:
- Total ballots case
- Unique candidates and counties
- Count of ballots each county received
- Count of ballots each candidate received
- Find the resultant winner from county and candidate

**Election-Audit Results:**
- How many votes were cast in this congressional election? : 369,711
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  _We first counted the total votes, listed unique counties, looped through the data to find combination of county
  and vote, then added these votes one by one to each county to get the total votes per county.
  County Votes:
  Jefferson: 10.5% (38,855)
  Denver: 82.8% (306,055)
  Arapahoe: 6.7% (24,801)_
- Which county had the largest number of votes? :  Denver
  _We compared the vote counts each county got with each other, and got the county with largest vote count_
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  _Similar to county, we used the same logic to get the following data
  Charles Casper Stockham: 23.0% (85,213)
  Diana DeGette: 73.8% (272,892)
  Raymon Anthony Doane: 3.1% (11,606)_
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  _Again, similar to county, we compared each candidates data to find the winner
  Winner: Diana DeGette
  Winning Vote Count: 272,892
  Winning Percentage: 73.8%_

**Election-Audit Summary:** 
With some modifications, this script could be used for various other election analysis. Following are some examples on how this can be achieved:
- We could have State included as well. In this case, we will have to make another list and a dictionary which will hold data for statewise counties.
- As the data grows, we can place candidates in quartiles, find outliers, mean votes etc (learnt from the Excel modules)
- We can store the results back into Excel and generate graphs for visual representation of the data
