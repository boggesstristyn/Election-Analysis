# Election-Analysis

## Project Overview
For this project, we were given data from a local congressional election and, using Python, were asked to generate a vote count report to:
  1. Calculate the total number of votes casted
  2. Calculate the voter turnout for each county
  3. Calculate the percentage of votes from each county based on the total votes cast
  4. Determine which county had the highest turnout
  5. Get a complete list of candidates who received votes
  6. Calculate the total numbers of votes each candidate received
  7. Calculate the percentage of votes each candidate won
  8. Determine the winner of the election based on popular vote
  9. Calculate the voter turnout for each county
  10. Calculate the percentage of votes from each county based on the total votes cast
  11. Determine which county had the highest turnout
  12. Print the information to a text file

## Election-Audit Results
The analysis of the election showed that there were 369,711 total votes cast in the election.
### Per County Analysis
  - The county results were:
    - Arapahoe County received 24,801 votes, 6.7% of the total votes.
    - Jefferson County received 38,855 votes, 10.5% of the total votes.
    - Denver County received 306,055 votes, 82.8% of the total votes.
  - Denver County had the largest number of votes, with 306,055 votes.

The bit of code used to analyze results based on county:

![county_analysis_code](https://user-images.githubusercontent.com/103851131/168406818-71d49a06-4c5a-47ed-b439-e8c61253daa1.png)

### Candidate Analysis
  - The candidates results were:
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
    - Charles Casper Stockham received 23.0% of the votes and 85,213 votes.
    - Diana DeGette received 73.8% of the vote and 272,892 votes.
- The winner of the election was Diane DeGette, with 272,892 votes, 73.8% of the total vote count.

The bit of code used to analyze results based on candidate:

![candidate_analysis_code](https://user-images.githubusercontent.com/103851131/168406819-820a8b2c-d3ce-4183-8445-70650252bb8c.png)

We printed the results to a text file:

![printed_results](https://user-images.githubusercontent.com/103851131/168407089-07e66509-7275-4cf8-92f3-5a36f22b5377.png)

## Election-Audit Summary
The script we wrote for this election audit could easily be modified to satisfy future analyses of the same, less, or greater size. A possible modification could be to change the parameters for counties to states, in order to scale up results. Another could be for a smaller election, such as a PTA election for choosing different board of directors.
