# Election Analysis

## Overview of Election Audit:
Main purpose of this election audit is to see which candidate out of three has the most vote in the state of Colorado. Election results came from three different counties: Jefferson, Denver, and Arapahoe. And the winning candidate was decided based on the total count of vote as well as the percentage of the total vote. 

## Election-Audit Results:

1. There were total of 369,711 votes in total in this election

2. The number of votes and the percentage of total votes for each county:
    -Jefferson has 38,855 votes with 10.5% of the total vote.
    -Denver has 306,055 votes with 82.8% of the total
    -Arapahoe has 24,801 votes with 6.7% of the total
3. As we can see from the result above, Denver has the most vote out of three counties with 306,055 votes, standing at 82.8%.

4. Three candidates with their results:
    -Charles Casper Stockham with 85,213 votes and 23.0% of the total vote
    -Diana DeGette won 272,892 votes with 73.8%
    -Raymon Anthony Doane with 11,606 votes and only at 3.1%

5. Diana DeGette is the winner in this election with the highest vote count of 272,892 which makes up 73.8% of the total vote.


## Election-Audit Summary:
If another election commission decides to use this script, I would recommend changing these two things. First, they need to replace the file path with the new election results csv file. For example, by changing this command line with folder name inside the first parentheses and then csv file name in the second one 'file_to_load = os.path.join("Resources", "election_results.csv")' Another command line they can possibly change to analyze another dataset is ![Script Modification_2](https://github.com/dilnigar1007/Election-analysis/blob/main/Election-Audit%20Modification.png). If another election analysis is on candidates vote results instead of counties, they can remove these commmand lines because the purpose of these lines is to create county name with its total vote. 
