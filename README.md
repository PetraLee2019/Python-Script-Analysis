## Python Scripts Analyzing Financial Records and Voting Results
## PyBank - Background
![alt tag](https://github.com/PetraLee2019/Python-Scripts-Analyzing-Financial-Records-and-Voting-Results/blob/master/Images/Financial-Statements.jpg?raw=true)
Create a Python script to analyze the financial records of a company that will be provided as data set called [budget_data.csv]. The dataset is composed of two columns: Date and Profit/Losses.

The Python script will analyze the financial records to calculate each of the following:
- The total number of months included in the dataset
- The total net amount of "Profit/Losses" over the entire period
- The average change in "Profit/Losses" between months over the entire period
- The greatest increase in profits (date and amount) over the entire period
- The greatest decrease in losses (date and amount) over the entire period
Result:
  ```
  Financial Analysis
  ----------------------------
  Total Months: 86
  Total: $38382578
  Average  Change: $-2315.12
  Greatest Increase in Profits: Feb-2012 ($1926159)
  Greatest Decrease in Profits: Sep-2013 ($-2196167)
  ```


## PyPoll - Background
![alt tag](https://github.com/PetraLee2019/Python-Scripts-Analyzing-Financial-Records-and-Voting-Results/blob/master/Images/polling-station.jpg?raw=true)
Create a Python script to analyze and modernize the vote-counting process for a small, rural town using a set of poll data called [election_data.csv]. The dataset is composed of three columns: Voter ID, County, and Candidate.

The Python script will analyze the votes and calculate each of the following:
The total number of votes cast
A complete list of candidates who received votes
The percentage of votes each candidate won
The total number of votes each candidate won
The winner of the election based on popular vote
Result:
  ```
  Election Results
  -------------------------
  Total Votes: 3521001
  -------------------------
  Khan: 63.000% (2218231)
  Correy: 20.000% (704200)
  Li: 14.000% (492940)
  O'Tooley: 3.000% (105630)
  -------------------------
  Winner: Khan
  -------------------------
  ```
## Tips
- Import modules like csv; to read and write files in various formats
- Store contents in variables, lists, and dictionaries
- Iterate through basic data structures
