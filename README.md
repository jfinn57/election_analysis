# Election Analysis
## Overview of Election Audit
Our friends Seth and Tom were overlooking the election for their hometowns and they enlisted our help to ensure votes were being tallied correctly. They had the raw data of the candidate that was voted for and the county the votes were coming from. After we helped them with a candidate summary, they wanted to use the data to summarize the county results including: the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout. These were our results.

## Election Audit Results

![Election Results](https://github.com/jfinn57/election_analysis/blob/main/election_results.PNG)

Our election results showed almost 370,000 votes were cast in this election. Almost 83% came from Denver county, with Jefferson County and Arapahoe county following up with 10.5% and 6.7% respectively.

The candidate race was not much closer. Diana DeGette ran away with the election, winning 73.8% of the vote compared the Stockham with 23.0% and Doane with only 3.1%

## Election Audit Summary

This script should be able to be used in future elections as long as the data stays in the same structure. If there's ever more fields that people want to analyze, it should be fairly simple to define the new field and use the same if statement we used for county data with adjusted names and variables. Going a step deeper, we could analyze how each candidate performed in each county. It would be a similar code but running results for one county at a time instead. This might show us that the winner really only won Denver County, but because of its size, that was all they needed to win the election.
