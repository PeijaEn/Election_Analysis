# Election Analysis

## Purpose of Election Audit Analysis
The client was interested in analyizing a CSV (comma seperated value(s)) file containing election information such as the Ballot ID, Candidate's name, and the County. Utilizing the information provided, the client inquired about the following information and requested it to be delivered in an easy to read format:
```
    1) Total number of votes
    2) A list of all candidates that received votes
    3) The number of votes each candidate received
    4) Percentage of the votes per candidate
    5) The winner of the election based on the popular vote (most votes)
```
##### I created a python scipt to these tasks and below are my results

## Election-Audit Results
```
Election Results
-------------------------
Total Votes: 369,711
-------------------------

County Votes:
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)
-------------------------
Largest County Turnout: Denver
-------------------------
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)
-------------------------
Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%
-------------------------
```

The text above is written into the provided txt file and is the results of my Python script. As you can see, Denver was the County with the most votes (306,055 / 82.8% of the total voters) and Diana DeGette won the election with 272,892 total votes (73.8% of the total voters).

## Election-Audit Summary
Upon finishing the script, I proposed to the client that my Python script could be used in any election and could read any CSV file and extract it's information. THe main changes would be changing the file_to_load to be a user input and to change the rows assigned to values in the nested for-loops. Another change that could be implemented is to write the results to another spreadsheet as well where they can be further compared.
