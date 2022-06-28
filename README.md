# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidated received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Calculate the voter turnout by county.
7. Calculate the percentage of votes by county.
8. Determine which county had the largest voter turnout. 


## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Code, 1.68

## Election-Audit Results
- There were a total of 369,711 votes cast in the election.
- The results by county were as follows:
  - Jefferson county had 10.5% of the votes cast; a total of 38,855 votes.
  - Denver county had 82.8% of the votes cast; a total of 306,055 votes.
  - Arapahoe county had 6.7% of the votes cast; a total of 24,801 votes.
- The county that had the largest number of votes cast was Denver with 82.8% of the votes cast and 306,055 number of votes.
- The candidate results were
  - Charles Casper Stockham received 23.0% of the votes cast; a total of 85,213 votes.
  - Diana DeGette received 73.8% of the votes cast; a total of 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the votes cast; a total of 11,606 votes.
The winner of the election was:
- Diana DeGette who received 73.8% of the votes cast and 272,892 votes.

### Results printed to the terminal
![this is an image](https://github.com/eneubauer2022/Election_Analysis/blob/main/results_in_terminal.png)

### Results printed to a txt.file
![this is an image](https://github.com/eneubauer2022/Election_Analysis/blob/main/results_in_txtfile.png)

## Election-Audit Summary
The election committee could use this script for any election, with some simple adaptations. For instance, if the election committee wanted to breakdown the results by county, rather than state, to see how the candidates performed in each individual county. This could also be done on a national level, where the county is replaced by state and the overall winner could be winner of a Presiential election (assuming it was based off popular vote). 

We could also look to collect additional pieces of information - such as political party affiliation. This could help us determine if the winning candidate was part of a certain political party or performed better in a county that had a higher voter turnout from that same political party. We would just need an additional data point collected from the voters to help us gather than information. 
