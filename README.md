# Election Analysis
## Project Overview
The purpose of this election analysis was to assist a board of elections in determining the winning candidate, their number of votes, and their percentage of votes won by usilizing an excel CSV file and Python functions in VS Code. 

  The goals of this analysis were to determine:
  
      1. The total number of votes
      2. Who the candidates in the election were
      3. Determine how many votes each of the candidates received 
      4. Determine percentage of the votes won by the candidate
      5. Finally, determine who the winning candidate was 
      
## Resources
This analysis was possible to perform by using:

    Data Source: the election_results.csv (downloaded from the module itself) 
    Software used: Python 3.7.6 and VS Code 
    
## Summary 
This analysis returned the following results: 

    -There were 369,711 total votes cast in the election 
    - The 3 candidates in the election were:
        Charles Casper Stockham 
        Diane DeGette
        Raymon Anthony Doane
    -Candidate results were as follows:
        Charles Casper Stockham received 85, 213 ttoal votes, 23.0% of the votes 
        Diana DeGette received 272,892 total votes, 73.8% of the votes 
        Raymon Anthony Doane received 11, 606 total votes, 3.1% of the votes 
 After performing this analysis and determining the total number of votes and percentage of votes each candidate received, we are able to see that Diana DeGette was the winner of the election with 73.8% of the vote with 272, 892 total votes. 
  
## Challange Overview 
 The goal for this challenge is to determine more information on the counties the voting data was taken from. Our goal was to find out the voter turnout from each of the counties, the percentage of votes from the total votes for each county, and see which of the counties had the highest vote count. To do this, we utilized the election_results csv vile and VS Code. 
 
## Challenge Summary 
After performing the analysis, the county election results are as follows:

    There were 369, 711 total votes
    The county votes totaled up to:
      -Jefferson: had a total of 38, 855 total votes, 10.5% of the total vote 
      -Denver: had a total of 306, 055 total votes, 82.8% of the total vote 
      -Arapahoe: had a total of 24, 801 total votes, 6.7% of the total vote 
      
  Denver is the county that had the largest turnout with 306, 055 total votes, 82.8% of the vote. 
  These results were printed to the election_analysis text file after running the code in the terminal. 
  ![Election_Results](https://github.com/aarce21/Election_Analysis/blob/main/Resources/Election_Results.PNG)
  
## Business Proposal 
The way this script was written and performed can also be used to determine either more information about this election or it can be used for elections ran in the future. We could take this election analysis further by looking deeper into the voter distribution in each of the counties. With the current way that we ran the analysis, we only found out the number and percentage of total votes for the county. However, we do not know the number of votes that each candidate received from each county, which would give us more specific data for the analysis. We can add this kind of analysis for this election, or any other election in the same or a different state, by changing the names and counties in the lists and dictionaries, to gather more information about vote/voter distribution. 

This election was also focused on county votes. If we wanted to look at a bigger picture on a grander scale, we could apply a script of this kind for state or country votes and voter count. 
