# Election Analysis

## Overview of Election Audit

The purpose of this analysis is to determine who won the fictitious election that pertains to the data that has been provided and to illustrate some basic statistics based on the results.

## Election-Audit Results
- How many votes were cast in this congressional election?

The total number of votes that were cast is 368,711.

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
 
Counties in the precinct include Jefferson (38,855), Denver (306,055), and Arapahoe (24,801). Jefferson accounted for 10.5%, Denver for 82.8%. and Arapahoe for 6.7%.
    
- Which county had the largest number of votes?

The county with the largest turnout was Denver with 306,055 votes (82.8% of the total).
    
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

The candidates who participated in the election were Charles Casper Stockham, who received 85,213 votes (23% of the total), Diana DeGette, who received 272,892 votes (73.8% of the total), and Raymon Anthony Doane, who received 11,606 votes (3.1% of the total).
    
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

The winner of the election was Diana DeGette, with 272,892 votes (73.8% of the total).
    
## Election-Audit Summary
This script can be used to accurately calculate the votes for each candidate and county, total votes, percentage of total votes for each candidate and county, and determine the winner of the election and county with the largest turnout. It takes a .csv file (with the candidate names, county names, and ballot IDs) as input, calculates the votes and percentages, formats and stores the results in a text file. The election commission could utilize this script in any election in order to significantly increase the rate at which votes are tabulated. Any number of candidates and counties can be analyzed without any further modifications.

Additionaly, a few modifications could be made in order to make this script more efficient and versatile. For one, assuming that ballot IDs are included in the .csv provided as input (which is the case for this particular dataset), a simple "if-else" statement could be added to confirm that each individual vote is unique and not duplicated. Secondly, with a few extra imported Python modules and HTML tags added to the code using print(), you could output the data to an HTML file instead of a text file and upload it as a page on a website in order to display the results on the web.
