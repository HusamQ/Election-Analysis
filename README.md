# Module-3-Challenge-
## Election Audit Analysis

We conduct analysis on the State of Colorado counties election polls. Retreiving the election results from the csv file (election_results) and conduct the analysis using python .
In this analysis, we calcualte the winning candidate along with the number of votes each candidate received per county. Then we derived the percentage of votes per county and decide the 
popular vote and then we determine the largest voter turnout. 

## Election-Audit Results: 
- Using a for loop that counts the total votes by incrementing the number of votes falling through the rows "total_votes = total_votes + 1"
There were 396711 votes cast in this congressional election. 
![election_result](https://github.com/HusamQ/Module-3-Challenge-/blob/31f8bd7ad1c682800e7b6c28ccff2f430ede2884/images/election-results.PNG)

- As show below is the breakdown of each county votes and the percentage of total votes for each county in the preceint. 
![votes_by_county](https://github.com/HusamQ/Module-3-Challenge-/blob/31f8bd7ad1c682800e7b6c28ccff2f430ede2884/images/votes_by_county.PNG)

- By counting each county's votes by for looping through the csv files, Denver, has the largest number of votes. 

- - Candidate Charles Casper Stockham received "23.0%" of the vote and "85,213" number of votes.
  - Candidate Diana DeGette received "73.8%" of the vote and "272,892" number of votes.
  - Candidate Raymon Anthony Doane received "3.1%" of the vote and "11,606" number of votes.
  ![Candidate Votes](https://github.com/HusamQ/Module-3-Challenge-/blob/31f8bd7ad1c682800e7b6c28ccff2f430ede2884/images/Candidate_received.PNG)
  
  - The election winner was candidate Diana DeGette. She won 73.8% of the votes 
  ![winner](https://github.com/HusamQ/Module-3-Challenge-/blob/31f8bd7ad1c682800e7b6c28ccff2f430ede2884/images/winner.PNG)
  
  # Election-Audit Summary:
  This script that we used to analyse the election is reusable for any future elections. 
  - This script can be modified to be used in other elections by adding additional column that holds weather the votes were casted by mail, in person ...etc to allow further analysis 
  and study the results for future elections. 
  - The same script can be used to analyse amunicipal voting or survey, by replacing the candidate name with the new ruling and county to Yay or Nay. 
