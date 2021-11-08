# Election_Analysis
## Overview of Election Audit: Explain the purpose of this election audit analysis.

#### The purpose of this election audit analysis is to obtain a data set, no matter where it is from and run the python script so that we can analyze the data to see the breakdown of county and candidate total votes and percentage of total votes. It also displays the winer as well.

##  Election-Audit Results:
Here are the results pulled from the election_results.txt

![election_results.txt](https://github.com/Samkyang/Election_Analysis/blob/main/resources/Election_Results.png?raw=true)

### How many votes were cast in this congressional election?

##### There were 369,711 votes casted in this specific election.

###    Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

##### County Votes:
* Jefferson: 10.5% (38,855)

* Denver: 82.8% (306,055)

* Arapahoe: 6.7% (24,801)

###   Which county had the largest number of votes?

##### Denver had the largest number of votes.

###    Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

#####
* Charles Casper Stockham: 23.0% (85,213)
* Diana DeGette: 73.8% (272,892)
* Raymon Anthony Doane: 3.1% (11,606)

###    Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

##### The winner is Diana DeGette with 272,892 votes. Diana had 73.8% of the total vote.

##  Election-Audit Summary:

##### This script is a very useful script because it can save a lot of time. The results seem simple but it can generate results really quick espcially if other elections wanted to utilize this script. If we were to just do an analyhsis for one election, using excel may have been quicker to see the total number of votes for each county and candidate and what the total percentage of the votes they got, but if we wanted to run an analysis on multiple elections having this script would help save time. The reason why it would save time is because as long as the columns have Ballot ID, County, and Candidate we can calculate what the results are.

How it could be modified to be used for any election is by editting the csv file name in the code below to whatever the file name is from a different election.

    # Add a variable to load a file from a path.
    file_to_load = os.path.join("Resources", "election_results.csv")
    
Another way that it could be changed is by editing the output file to have the election name so that the winners election outputs can be tracked.

    # Add a variable to save the file to a path.
    file_to_save = os.path.join("analysis", "election_results.txt")