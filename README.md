# Election-Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete th election of a recent local congessional election

1. Calculate the number of votes cast.
2. Get a complete list of candidates 
3. Calculate Total number of votes of each candidate
4. Calculate the the percentage of votes each candidate won
5. Determine the winner of the election


## Resources
-Data Source: election_results.cvs
-Sofware: Python 3.6.1, VS Code, 1.38.1

## Summary
The analysis of the elections show that: 

-There were 369,711 total votes

-The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthny Doane

-The candidate results were
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes
  - Raymon Anthony Doane received 3.1% of teh vote and 11,606 number of votes

- The winner of the election was:
  -Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.
  
  ## Challenge overview
  The purpose of this election audit is to:
    - calculate the vote turnout of the election for each county
    - determine the percentage of votes registererd in each county 
    - determine the county with the highest turnout in the election
 
  
  
  ## Challenge Summary
  
  ### Election Results
 The results of the elections were as follow:
 
-There were a total of 369,711 votes
  
-The counties where the election took place were
   -Jefferson
   -Arapahoe
   -Denver
    
-The turnout results were:
   - 10.5% of the votes were registerd in Jefferson for a total of 38,855 number of votes
   - 82.8% were registered in Denver for a total of 306,055 number of votes
   - 6.7% of the votes were registered in  Arapahoe pr a total of 24,801 number of votes   
   
-Denver had the largest number of votes with a total of 306,055
   
-The candidate results were
   - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes
   - Diana DeGette received 73.8% of the vote and 272,892 number of votes
   - Raymon Anthony Doane received 3.1% of teh vote and 11,606 number of votes

- The winner of the election was:
  -Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.   
  
  
  ### Election Audit Summary
  The script written for this election can be used for elections for election of any sort. 
  The best way to duplicate the script is to define the list of candidates (candidate_options = []candidate_votes = {}) and 
  counties(county_options =[] county_votes ={}) to keep track of numbers. Depends on the type of files the results are presented in
  it might, we need to find a way to count the votes (candidate_votes[candidate_name] += 1). In our case we counted how many times the name
  of each candidate showed up in the csv file. Similar process were use to count the turnout of the counties (county_votes[county_name] += 1). 
  The code ran through the file vertically and counted the how many times each name showed uop to determine who won the election 
  and how many times each county was repeated to determine the turnout of each county. 
   
  
