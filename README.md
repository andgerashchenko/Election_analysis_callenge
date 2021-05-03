# Election_Analysis

## Project Overview
Purpose of the project is to complete election audit for Local Congressional Election in Colorado, providing summarized data of number of votes and percentages for candidates and counties, determibne the winner.

## Resourses
- Data Sourse: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election audit results
- There were 369,711 votes cast in the congressional election
- The election was held in following counties with corresponding number of votes and percentages:
    - Jefferson county had 10.5% of the vote and 38,855 number of votes.
    - Denver county had 82.8% of the vote and 306,055 number of votes.
    - Arapahoe county had 6.7% of the vote and 24,801 number of votes.
- As a result, Denver county had the largest number of votes.
- The candidates and their results were:
    - Charles Casper Stockham received 23.0% of vote and 85,213 number of votes
    - Diana DeGette received 73.8% of vote and 272,892 number of votes
    - Raymon Anthony Doane received 3.1% of vote and 11,606 number of votes 
- The winner of the election was Diana DeGette with 73.8% of vote and 272,892 number of votes. .

## Election audit summery
The script, used for election audit, had been written as unuiversal tool, wich can be utilized for almost any election data.
The only few lines of the code will be need to modified, such as initial data file path:
- 'file_to_load = os.path.join("Resources", "election_results.csv")'.

Or if the data file has different rows layout, just index numbers will be needed to correct:
- 'for row in reader:
    
    total_votes = total_votes + 1
    
    candidate_name = row[2]
    
    county_name = row[1]'
