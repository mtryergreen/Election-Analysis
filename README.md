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

## Future & Further Use

There is a statement to the election commission that explores how this script can be used for any election, with two examples for modifying the script. (4 pt)
This script can be used in the future for any election to deliver the same types of results as long as votes, voter's county names and the candidate options are included in the data. The script may even be modified to entertain differing variables, such as: 
1. Electoral votes: depending on the election (those involving an electoral college), winning a majority of votes may not be enough. Instead, tracking what percentage of an electoral college each candidate has won could be a viable route to determining election status. This would involve the total votes for each county being put through a multiplier that would convert the value to reflect the total electoral votes granted from that populace. 
2. 

