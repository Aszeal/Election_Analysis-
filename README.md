# Overview of Election Audit 
  I was tasked with helping two individuals named Seth and Tim submit an election audit to the Election Commission. Furthermore, the Election Commision asked
me to create a consistently accurate sript that produces the voter turnout for each county, percentage of votes from each county out of the total count, and each county with the highest turnout. I completed the task. Below I will explain the election audit results and a comprehensive summary. 

## Election Audit Results 
### Below, is the *Election Aduit Results* . I will referance the image.
1. How many votes were cast in this congressional election?
  - As seen below, the total votes amounted to ***369,711*** .
  
  
3. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  - ***Dever had the highest percentage of votes***. Following, we have Jefferson at ***10.5*** percent and then Arapahoe at ***6.7*** percent.
    - Jefferson: 10.5% (38,855)
    - Denver: 82.8% (306,055)
    - Arapahoe: 6.7% (24,801)

  - The county that had the largest amount of votes was Denver at an astounding ***306,055 votes***.
  
  
7. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
As seen in the image, below is the distribution of the votes and percentages allocated among the canidates.

    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)


9. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  The candidate that won was ***Diana DeGette***. Diana absolutely defeated her opponents by ***73.8 percent***. A smashing victory. 

   - Diana DeGette: 73.8% (272,892)




-----------------------------------------------------------------------------------------------------------------------------




![Election Analysis](https://github.com/Aszeal/Election_Analysis-/blob/main/Resources%20Election%20Analysis/Election%20Analysis%20text.png)

## Election Audit Summary
I would like to showcase tha my script can be much more benefical for any election process. ***My script is highly versitle and can be retro-fitted to meet the various needs of any election.*** 

 - For example,  we can modify the script to be used to track the ***"smallest county"*** votes by changing the script to look like the following:
    ```
    smallest_county = empty string   
    smallest_county_count = 0
    ```
    
    ```
            if votes > smallest_county_count:
            smallest_county_count = votes
            smallest_county = county_name
            
    smallest_county_summary =  (
        f"-------------------------\n"
        f"Smallest County Turnout: {Smallest_county}\n"
        f"-------------------------\n")
    print(Smallest_county_summary)

    ```
  - Another part of the script we can change, would be if we wanted to have the script say something else. Maybe we want the script to show ***"County With Greatest           Amount of Votes".***
       ```
    greatest_amount_county = empty string   
    greatest_amount_county_count = 0
    ```
    ```
            if votes > smallest_county_count:
            greatest_amount_county_count = votes
            greatest_amount_county = county_name
            
    greatest_amount_county_summary =  (
        f"-------------------------\n"
        f"County With Greatest Amount of Votes: {greatest_amount_county}\n"
        f"-------------------------\n")
    print(greatest_amount_county_summary)
    ```
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
In conclusion, I understand, and I have learned that the election process can be very complicated. I have showcased how my script can fit the needs of any eleciton proces. My script can do so much more. ***I can track and script to calculate by Districts. Or if elected officals would like to determine the income level of the voter I can script for that as well.*** My scripts takes the complexities of elections and makes aquiring the necessarry infromation to make informed decision quick and easy. I hope that my script can be of use in future election processes. 
