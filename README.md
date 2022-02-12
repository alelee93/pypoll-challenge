# Overview of Election Audit

A csv file with election results was provided for this analysis. The purpose of this election audit analysis is to calculate the voter turnout for each county, the percentage of votes from each county out of the total count and the county with the highest turnout. The calculations should be done in Python, using for loops and conditional statements and the results should be printed in a txt file.

# Election Audit Results

- Number of votes:
  - 369,711 votes were cast in this congressional election
- The breakdown of the number of votes and the percentage of total votes for each county in the precinct was as follows:
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
- The county with the largest number of votes was Denver
- The breakdown of the number of votes and the percentage of the total votes each candidate received was as follows:
  - Charles Casper Stockham: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11,606)
- Diana DeGette won the election, with the following metrics:
  - Winning Vote Count: 272,892
  - Winning Percentage: 73.8%

# Election-Audit Summary

This script can be used to calculate the results for any election as long as the election results’ csv dataset is organized and located in the same way/place as in this analysis and the election_analysis.txt file is not moved. More specifically:

## The csv file

Format: the second column shows the county, the third column shows the candidate, and the file’s first row includes the headers.

The csv file is named election_results.csv and is located inside the “Resources” folder (which should be on the same level as the “PyPoll_challenge.py” file).

## The election_analysis.txt file

The file should be located inside the “analysis” folder, which should be on the same level as the “PyPoll_challenge.py” file

## Script updates that may be needed to calculate other election results

- If the name or location of the csv file is modified, then line 10 of the PyPoll_Challenge.py should be updated to reflect the updated name and location.

- If the column where the candidate’s name is shown in the raw data is modified, then line 51 of the PyPoll_Challenge.py should be updated to reflect the new index where the name is shown (which would be column number less 1).

- If the column where the county is shown in the raw data is modified, then line 54 of the PyPoll_Challenge.py should be updated to reflect the new index where the county is shown (which would be column number less 1).

- If the headers are removed from the csv file, then row 42 of the PyPoll_Challenge should be removed.

- If the name or location of the election_analysis.txt file is modified, then line 11 of the PyPoll_Challenge.py should be updated to reflect the updated name.
