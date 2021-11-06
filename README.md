# Election-Analysis

## Challenge Objective:
This challenge had me organize thousands of rows of data from an election taking place across the counties of Jefferson, Denver and Arapahoe. The module showed me how to retrieve data on the votes for the candidates, but the challenge itself required I use similar functions in python to retrieve the same data for each county. Overall, the finished product can be summed up here:

![Election Product](https://user-images.githubusercontent.com/89936913/140592926-46e6b9ed-64a0-49b8-974c-7f7c970e4a40.png)

Denver county contains the largest share of voters at 306,055 (83%) and the winner (by a landslide) was Diana DeGette with 272,892 votes (74%). 

## Overview of Election Audit

The purpose of this election analysis audit is well defined. (3 pt)
For this challenge, I found the voter turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout. I utilized "for loops" and conditional statements with membership and logical operators to find these results. The findings were printed to a text file, which is included in this report (election_reslts.txt). 

## Election Audit Results

There is a bulleted list where each election outcome is addressed. (7 pt)

My evaluation of the election's results occurred in a few steps:
- establishing a list and dictionary to track the winning candidate and largest county
- extracting the candidate and county name from each row
- adding unique candidate and county names to their respective lists
- adding votes to the respective candidate's or county's name

As mentioned before, Diana DeGette won the election with 272,892 votes, or 74% of the total count. The code to retrieve these outcomes began with formulating a list and dictionary for the winning candidate's vote count and percentage:

Here is the code that established a list and dictionary to track the winning candidate:
<img width="426" alt="Screen Shot 2021-11-05 at 10 28 35 PM" src="https://user-images.githubusercontent.com/89936913/140594895-8e593483-7822-4e38-9dac-2ecc292bc2e8.png">

And here is the code that established the same items for the largest county:
<img width="410" alt="Screen Shot 2021-11-05 at 11 42 39 PM" src="https://user-images.githubusercontent.com/89936913/140596821-114c826c-a305-4fb9-867f-427de4ea1a68.png">

Next, I used this code to extract the candidate and county names from each line:
<img width="353" alt="extraction" src="https://user-images.githubusercontent.com/89936913/140596999-58d61173-db01-4d29-abc1-d363ab594ec4.png">

Here is the code I used to add unique and additional names to the final deliverable: 

<img width="470" alt="Screen Shot 2021-11-05 at 11 51 08 PM" src="https://user-images.githubusercontent.com/89936913/140597109-65b3fbd8-64d8-4e22-a0f8-23203dc7b545.png">

## Further & Future Use
Overall takeaways from this election: 
- 396,711 votes were cast in this congressional election
- Jefferson County held 38,855 (10.5%) of the votes; Denver County held 306,055 (82.8%) of the votes; and Arapahoe County held 24,801 (6.7%) of the votes
- **Denver county had the largest percentage of votes**
- Charles Stockham held 85,213 (23%) of the votes; Diana DeGette held 272,892 (73.8%) of votes; Raymon Doane held 11,606 (3.1%) of the votes
- Diana DeGette held the largest percentage of votes with 73.8% of the total votes at 272,89

This script can be used in the future for any election to deliver the same types of results as long as votes, voter's county names and the candidate options are included in the data. The script may even be modified to entertain differing variables, such as: 
1. Electoral votes: depending on the election (those involving an electoral college), winning a majority of votes may not be enough. Instead, tracking what percentage of an electoral college each candidate has won could be a viable route to determining election status. This would involve the total votes for each county being put through a multiplier that would convert the value to reflect the total electoral votes granted from that populace. 
2. Another way to track voters' preference would be to tally the votes that were **Not** for a specific candidate, or discern the least popular candidate from each county. In this case, the candidate with the fewest votes NOT for them would be most favorable. 

