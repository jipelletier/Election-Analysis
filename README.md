# Election Analysis

## Purpose
The purpose of this election audit analysis is to assist a Board of Election employee, Tom, audit the results for the U.S. Congressional precinct in Colorado. We will need to assist with reporting the total number of votes cast, the total number of votes for each candidate, the oercentage of votes for each candidate, and the winner of the election based on the popular vote. We are tasked with automating this process with python.

## Project Overview
A Colorado Board of Elections employee has given us the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast
2. Get a complete list of candidates who recieved votes
3. Calculate the total number of votes each candidate recieved
4. Calculate the percentage of votes each candidate won
5. Determine the winner of the election based on popular vote

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election
- The counties counted in the election were:
  - Jefferson County
  - Denver County
  - Arapahoe County
- The county results showed:
  - Jefferson county recieved 10.5% of the total votes casted at 38,855 votes cast
  - Denver county recieved 82.8% of the total votes casted at 306,055 votes cast
  - Arapahoe county recieved 6.7% of the total votes casted at 24,801 votes cast

- The county with the largest number of votes was Denver County with 306,055 votes cast recieving 82.8% of the total votes in the election

- The candidates were:
  - Charles Gasper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Gasper Stockham recieved 23% of the vote and 85,213 votes
  - Diana DeGette recieved 73.8% of the vote and 272,892 votes
  - Raymon Anthony Doane recieved 3.1% of the vote and 11,606 votes
- The winner of the election was:
  - Diana DeGette who recieved 73.8% of the vote and 272,892 total votes

## Election Audit Summary
The script used for this election audit is capable of being useful in other elections. It could serve as a template for nationwide elections with a few alterations. One would be to include additional datasets depending on the election. We could insert additional csv files with data by state if needed to analyze and count voting data. Another option is to insert additional code in otder to analyze the data further. For example, if we add another conditional statement, we could see which county voted for which candidate. This could be beneficial for campaign planning and targetting specific audiences.
