# RBC-Module-3-Election-Analysis

## Overview of Project
Tom is a member of the Colorado Board of elections employee who has tasked us with using a Python Script to help him Audit the Congressional Colorado Precicnt Elections.

[Link to PyPoll_Challenge.py](PyPoll_Challenge.py)

### Purpose
The purpose of this project was to provide Tom with a thorough analysis on the Election Audit results using the Python Language by the following:
- Importing [election_results.csv](https://github.com/Dryspell/RBCModule3-Challenge/blob/main/Resources/election_results.csv).
- Counting the total number of votes cast.
- Creating lists of the candidates and counties.
- Tallying the votes for each candidate in each county using dictionaries.
- Calculating the percentages of the votes in each county and finding the lagest turnout county.
- Calculating the winner of the elections.
- Exporting the results to [election_analysis.txt](https://github.com/mubeenkh4u/RBC-Module-3-Election-Analysis/blob/main/analysis/election_analysis.txt)

### Election-Audit Results
The results of the election audit were as follows:
1. The total number of votes cast in the election were `369,711`.
2. The votes from each county were as follows:
    - `Jefferson: 10.5% (38,855)`
    - `Denver: 82.8% (306,055)`
    - `Arapahoe: 6.7% (24,801)`
3. Denver County had the largest turnout with `306,055` Voters!
4. The votes (percentage) received in total by each candidate were as follows:
    - `Charles Casper Stockham: 23.0% (85,213)`
    - `Diana DeGette: 73.8% (272,892)`
    - `Raymon Anthony Doane: 3.1% (11,606)`
5. The winner of the election was Diana DeGette with a `Winning Vote Count of 272,892` and `Winning Percentage of 73.8%`

Here are screenshots of the results printed out in the terminal and the output from the text file.
<table align="center">
  <tr>
    <th>Terminal Output</th>
    <th>Output to the Text File</th>
  </tr>
  <tr>
    <td><img src="https://github.com/mubeenkh4u/RBC-Module-3-Election-Analysis/blob/main/Images/Terminal_Output.png"></td>
    <td><img src="https://github.com/mubeenkh4u/RBC-Module-3-Election-Analysis/blob/main/Images/Text_File_Output.png"></td>
  </tr>
</table>

### Election-Audit Summary
Overall the election audit script "PyPoll" that we have created is powerful enough in itself. Though we could modify it for future elections in the following ways:
- We could add a user input for the purpose of inputting the files into the script.
<img src="https://github.com/mubeenkh4u/RBC-Module-3-Election-Analysis/blob/main/Images/User_Input.png">
- We can further modify the script to work for different types of election.	This would be utilizing the listing of each individuals vote for the type of election and then tallying it for each individual for that particular election type.
<table align="center">
  <tr>
    <th>Terminal Output</th>
    <th>Output to the Text File</th>
  </tr>
  <tr>
    <td><img src="https://github.com/mubeenkh4u/RBC-Module-3-Election-Analysis/blob/main/Images/Change_Candidate_Input.png"></td>
    <td><img src="https://github.com/mubeenkh4u/RBC-Module-3-Election-Analysis/blob/main/Images/Change_County_Input.png"></td>
  </tr>
</table>
