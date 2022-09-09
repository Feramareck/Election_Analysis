# Election_Audit

## Project Overwiew  

Produce a Python code that serves as an electoral audit of tabulated results for a US Congressional precinct in Colorado. Our main task was to report the total number of votes cast, the total number of votes for each candidate and county, the percentage of votes for each candidate and county, the county with the highest turnout, and the winner of the election based on popular vote.  
After the votes are counted, it was necessary to generate a vote count report to certify this race to the US Congress.

## Resources  

 - Data Source: election_results.csv
 - Software: Python 3.9.1, VS code 1.71

 ## Election-Audit Results  
 
After manipulating the data from the .csv file in Python, we were presented with the following results:  

![election_analysis](https://user-images.githubusercontent.com/111664141/189436729-213dcc2c-dfaa-40a5-919d-47c90a943737.png)
  
From the image above we can see that the total number of votes received in this election was 369,711, with Denver being the county with the highest number of voters with 306,055 votes. Candidates Charles Casper Stockham, Diana DeGette and Raymon Anthony Doane had 23%, 73.8% and 3.1% respectively with Diana DeGette winning with a total of 272,892 votes.  
This data can also be verified in the generated file election_analysis.txt  


## Election-Audit Summary:  

The vote data were made available in an Excel file, which makes it very susceptible to problems during its manipulation and also very easy to make mistakes if the data is not handled correctly. Thus, this project was coded in Python because it is a language widely used in data analysis and because it is easy to reuse the code for a wider range of data.  

To reuse this code for use in other election audits we could make some changes to the code.  
One of the modifications would be to set the path/name of the .csv file containing the election data in a variable at the beginning of the code, not needing to change the line containing "file_to_load = os.path.join..."  
Another change would be to identify the columns. We could create an index that directly references the candidate or municipality along with the declaration of variables without the need to look for the referenced column in the middle of the code to change them.
