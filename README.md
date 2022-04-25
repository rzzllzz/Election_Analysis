# Election_Analysis

## Project Overview
A Colorado Board of Elections employee requested the completion of an election audit of a recent local congressional election. The Board asked for a calculation of the total number of votes cast. In addition, the Board asked for the total number of votes and percentages each candidate in the race received as well as the winning candidate's total number of votes and percentage of the vote won. Finally, the Board wanted to know which county had the largest number of votes and thus the largest turnout. 

## Election-Audit Results 
The analysis of the election show that:
- There were **369,711** total votes cast in the election.
### The three counties in the precinct were:
  - Jefferson
  - Denver
  - Arapahoe
### The vote distribution for each county was:
  - Jefferson: 10.5% (38, 855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
### The county with the largest number of votes cast was *Denver* with 82.8% of votes cast in the election. 

### The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
### The candidate results were:
  - Charles Casper Stockam: 23.0% (85,213)
  - Diana DeGette: 73.8% (272,892)
  - Raymon Anthony Doane: 3.1% (11, 606)
### The winner of the election was:
  - **Candidate Diana DeGette**, who received 73.8% of the vote and 272,892 number of votes. 

Please see below image for screenshot of the text file where the results of the data analysis were printed.
![Election Results As Text File](https://user-images.githubusercontent.com/101225282/165023841-901d233f-e137-45d8-8efe-69618324387b.png)

## Election-Audit Summary
The code created for this analysis was done using Python and can be used for future election audits of varying sizes for the state of Colorado's purposes. This code interpreted data from a *csv* file and thus can read a much bigger file to suit a bigger election, such as a senatorial race. In the image below, the indexes read by the code on lines 50 and 53 can be changed to suit a different data structure, for example, replacing "county_name" with "city_name" to analyze the voter turnout from various cities in a senatorial race. This would require some refactoring of the code to change the variable names from county to city for the sake of clarity, but the structure of the code otherwise does not change.

![Screenshot from PyPoll Challenge code](https://user-images.githubusercontent.com/101225282/165024886-cb219f17-938d-42f1-9f20-0b22928a1a42.png)
