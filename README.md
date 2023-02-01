# NFL Concussion Analysis


Each year a number of players in the NFL experience head injuries or concussions. 
As fans of football, it is important to consider the risks players are putting themselves in to play the game. 
This is especially important to consider since mild traumatic brain injuries or concussions can cause damage to the brain. 
This in turn can impact sleep, thinking, actions, learning, and feelings.To better understand the data Project Team 02, 
looked at the number of head injuries, including concussions that occurred in the NFL in seasons 2012-2014. 

Project Team 02 decided to attempt to answer the following questions in order 
to better understand the impact head injuries have on the players and on the game itself:

Do Head Injuries or concussions cause players to miss more games?
How long were players out? 
How did the injury affect the player’s playtime? 
What position gets the most concussions on both offense and defense?
Do offensive or defensive players miss more games from injuries?
Do offensive or defensive players have more injuries?
How did the team fare (win or lose?) when they had a player with a head injury?
What team is most prone to concussions?
What team inflicted the most concussions? 





# Visuals


![3D_graph](https://user-images.githubusercontent.com/86619869/215665889-3d9677a3-90a1-4b48-a2b5-30e3ca5fa79e.png)


![Injuries_per_team_2012-2014](https://user-images.githubusercontent.com/86619869/215666652-5c1a105d-19f0-46ea-a346-68585d194496.png)

![Number_of_Games_Missed](https://user-images.githubusercontent.com/86619869/215666755-c42db8b6-6feb-4888-9eaf-7a03ef591e6e.png)

![Total_injuries_on_2012-2014](https://user-images.githubusercontent.com/86619869/215666799-d7ea12f7-467a-4bcf-9e6d-f50f0f61c37b.png)

![Percentage_of_injuries_between_offense_defense_2012-2014](https://user-images.githubusercontent.com/86619869/215666839-7d37b6cd-4265-4c7b-b47f-42fb46432ba2.png)

![Injuries_per_year](https://user-images.githubusercontent.com/86619869/215666888-f7a52cc6-cd9a-4777-a7aa-fba1b732be79.png)

![Number_of_Wins_Loses_of_Teams_with_an_Injured_Player_2012-2014](https://user-images.githubusercontent.com/117786548/215682349-487dd7b4-0b4c-4e6d-97ea-97773573a1a9.png)

![win_count_Teams_with_an_Injury](https://user-images.githubusercontent.com/117786548/215684637-70ca5561-ab5b-44df-bd75-fc779a2acbaa.png)

![Number_of_Wins_Loss_of_Teams_Inflicting_an_injury_to_the_other_team_2012-2014](https://user-images.githubusercontent.com/117786548/215682596-15614ba5-69a7-4c10-b647-2fe102255193.png)

![Teams_Win_Lose_Rate_with_Inflicting_Injury](https://user-images.githubusercontent.com/117786548/215685404-0968abfd-8abe-4aff-8d81-4961685b13a9.png)

![Number_of_Downs_Before_and_After_Injury](https://user-images.githubusercontent.com/117327499/215873695-e35e973a-373a-468c-835c-591b0a29992b.png)

![Team_Map](https://user-images.githubusercontent.com/117327499/215969263-5a10b33e-9409-4031-8768-9ece7b0151e5.png)


#Statistical Analysis:
Do Head Injuries or concussions cause players to miss more games?
•	Ho: If head injuries impact a player’s ability to participate as much as concussions, then there will not be a difference in mean number of games missed
•	Ha: If head injuries do not impact a player’s ability to participate as much as concussions, then there will be a difference in mean number of games missed
•	Independent t-test
•	pvalue=0.35 
•	Not Statistically Significant

Injuries impact play time?
•	Ho: If head injuries do not impact a player’s ability to participate, then there will not be a difference in mean number of downs played after injury compared to downs played before injury.
•	Ha: If head injuries do impact a player’s ability to participate, then there will be a difference in mean number of downs played after injury compared to downs played before injury.
•	Independent t-test
•	pvalue=0.012
•	Statistically Significant

Do offensive or defensive players miss more games from injuries?
•	Ho: If being an offensive or defensive player is not related to the number of games missed after injury, then there will not be a difference in mean number of games missed.
•	Ha: If being an offensive or defensive player is related to the number of games missed after injury, then there will be a difference in the mean number of games missed.
•	Independent t-test
•	pvalue=0.078
•	Not statistically significant

Do offensive or defensive players have more injuries?
•	Ho: If offensive and defensive players are as susceptible to injury, then there will not be a difference in mean number injuries received over the three seasons of play between offense and defense.
•	Ha If offensive and defensive players are not as susceptible to injury, then there will be a difference in mean number injuries received over the three seasons of play between offense and defense.
•	Independent t-test
•	pvalue=0.74
•Not statistically significant

# Additional Questions Answered
How long were players out? 
 Most players that were involved in a head injury were back by the next game.

What position gets the most concussions on both offense and defense?
Offense: Wide Receiver
Defense: Cornerback 

How did the team fare (win or lose?) when they had a player with a head injury?
Injured Teams fare worse, with a 45.5% win rate during games with an injury.
Injury Inflicting Teams fare better, with a 54.5% win rate during games where they inflicted an injury on the opposing team.

What team is most prone to concussions?
Jacksonville Jaguars with 21 injuries

What team inflicted the most concussions? 
Cleveland Bears with 19 inflicted injuries

# Further Research
Increases size of the dataset
The original dataset is small
Very limited readily available datasets were public 
Determine the number of players with multiple head injuries 


# Authors and acknowledgment
Kelsey Brantner
•	Ran statistical analysis, (4 independent t-tests) on data set using both my code and code Joel created for the analysis
•	Helped write introduction and statistical analysis
•	Created the code for the following graphs and images:
o	Number_of_Downs_Before_and_After_Injury
o	Number_of_Games_Missed
o	Team_Map


Daniel Carrasco
* Created code that grouped and graphed teams head injuries to wins/loses
* Breakdown of teams with the most head injuries
* Breakdown of teams that inflicts the most head injuries
* Compared how head injuries affected teams wins/loss
* Compared how inflicting head injuries affected teams wins/loss
* Percentage of wins/loss in pie chart for both injured and inflicting injuries


Joel Pangilinan
* Helped clean the dataframe
* Created the code that produced the following graphs
* 3D rendering of injuries per NFL team and per year
* Number of injuries per year
* Breakdown of injuries by positions
* Percentage of injuries on offensive teams compared to defensive teams
* Injury trend

# References:
Dataset:
https://data.world/alice-c/nfl

Location Data:
https://www.geoapify.com/

News articles:
https://www.pbs.org/wgbh/frontline/investigation/the-nfls-concussion-crisis/

NFL protocol on concussions:
https://www.nfl.com/playerhealthandsafety/resources/fact-sheets/nfl-head-neck-and-spine-committee-s-concussion-diagnosis-and-management-protocol

CDC:
https://www.cdc.gov/traumaticbraininjury/concussion/index.html 




# Project status
Completed
