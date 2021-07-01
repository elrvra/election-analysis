# PyPoll with Python

## Overview of Election Audit

### Explain the purpose of this election audit.
The purpose of this election audit is to assist a Colorado Board of Elections employee, Tom in an election audit of the tabulated results for US Congressional Precenting in Colorado. The task is to report the total of number of votes cast, the total number of votes for each candidate and county, the percentage of votes for each candidate and county and the winner of the election based on the popular vote as well as the county with the largest number of votes. 

This task is usually done in excel, but Tom’s manager wants to know if there is a way to automate the process using Python. If this audit is done successful with Python, the code Tom and I write will be used to audit not only other congressional districts but also senatorial districts and local election. There are three primary voting methods that Tom and I will take into account: mail in ballots, punch cards, and direct reporting electronic (DRE) copy machines. Mail in ballots is typically hand counted at the central office. Punch cards are collected and fed into a machine that tabulates the totals and sends results to central office. Memory cards for DRE counting machines are sent to the central office and read by computers. 

All together the votes cast by these three methods will determine the final election results. After the votes are counted, my job is to generate a vote count report to certify this US Congressional race. I will be using Python to write algorithms that will assist the confirmation and analysis of election results by using the provided .csv file that houses the election data.

## Election Audit Results

### Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary. 
1) How many votes were cast in this congressional election?

![alt tag](https://github.com/elrvra/election-analysis/blob/main/Resources/1_Total_Votes.png)

2) Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

![alt tag](https://github.com/elrvra/election-analysis/blob/main/Resources/2_County_Votes_Percentage.png)

3) Which county had the largest number of votes?

![alt tag](https://github.com/elrvra/election-analysis/blob/main/Resources/3_County_Votes_Largest.png)

4) Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

![alt tag](https://github.com/elrvra/election-analysis/blob/main/Resources/4_Candidate_Votes_Percentage.png)

5) Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

![alt tag](https://github.com/elrvra/election-analysis/blob/main/Resources/5_Winner_of_Election.png)


## Election Audity Summary

### In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

Statement: The script can be re-used for any type of election with data that is formatted in the exact same way, by re-naming the variables in the script and updating the .csv to use similar information of the same fields/columns. Examples are shown as follows...

1) Example: The variables for identifying the candidate name and county name are defined by column header (i.e row 2 for candidate name and row 1 for county name) as shown below in below picture. One could alter this information for another type of election, by: (a) overwriting the .csv file with the new information using the sames columns by copying over the data appropriately (b) making sure to update all other code where the previous variables names were mentioned and update with the revised variables names. 

