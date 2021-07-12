# Election Analysis (Module 3 Challenge)

## Overview of Election Audit
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election. The two people who contacted you, Tom and Seth, have helped you with this develop.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determina the winner of the election based on popular vote.
6. The voter turnout for each county.
7. The percentage of votes from each county out of the total count.
8. The county with the highest turnout.

This task usually is done in Excel, but they wanted to automate the task. If it is correct, the development could use for other elections.
The task was done as it was expected, and the result was delivered in the terminal and a text file. Evidence has been included in the repository.

## Election-Audit Results
According to the request, results were categorized to be presented in the terminal after running the Python code and into text file.
The following images were taken from the terminal.

  * Total Votes
  
  ![Total Votes](https://github.com/JackieCortes/ElectionAnalysis_Challenge/blob/main/Images/TotalVotes.png)

  * Breakdown of the number of votes and the percentage of total votes for each county in the precinct.

  ![County Breakdown](https://github.com/JackieCortes/ElectionAnalysis_Challenge/blob/main/Images/County_Votes.png)
  
  * County with the largest number of votes.
  
  ![Largest_County](https://github.com/JackieCortes/ElectionAnalysis_Challenge/blob/main/Images/Largest_County.png)
  
  * Breakdown of the number of votes and the percentage of the total votes each candidate received.
  
  ![Candidate_Breakdown](https://github.com/JackieCortes/ElectionAnalysis_Challenge/blob/main/Images/Candidates.png)
  
  * Election's winner.
  
  ![Winner](https://github.com/JackieCortes/ElectionAnalysis_Challenge/blob/main/Images/Winner.png)

_Note: Complete summary was printed in the text file. Please, review it in [elections_results.txt](https://github.com/JackieCortes/ElectionAnalysis_Challenge/tree/main/analysis)_

## Election-Audit Summary
As you can see, the current code to audit this congressional election is effective. Its performance in speed terms exceed the expected time to obtain the same result using Excel. Adding that the flexibility of the code can accept more changes depending on the use that you want to give.

Let's explore examples:

    1) Volume: due to the speed and the type of file, if the election would have more voters, it was not an issue. Python can support more volume without problems.
    2) Different data: The counties and candidates can vary to use the same code from other states.
    3) New variable: If new variables were added to categorize the votes, adding a new cycle would be the solution to refactor the script and print the information.

_Appendix: To revew the code, please refer to [PyPoll_Challenge.py]()_

### Resoruces
- Data Source: [election_results.csv](https://github.com/JackieCortes/ElectionAnalysis_Challenge/tree/main/ResourcesPP)
- Software: Python 3.8.8, Visual Studio Code:1.58.0

