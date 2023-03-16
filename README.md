# FIFA-2021-Data-Cleaning


## Introduction

Being a newbie in the data space and hearing some amazing people talk about how data cleaning takes a lot of time to clean on and how challenging it could be.
The #datacleaningchallenge which was organized recently on the twitter space was about the messy and dirty FiFa 2021 csv data. This challenge was to encourage and gave everyone the opportunity to work on a data cleaning project with any prefered tools of their choice and also learn new skills and different ways while on the job.

![](use.png)

## Problems and things to look out for
1. Incorrect data type
2. Errors in spelling and values
3. Wrong calculations accross rows and columns
4. Irrelevant data
5. Null entries and outliers

## About the data
The FIFA21 csv data is a dirty and messy data which was gotten from the public kaggle website that has 18979 rows and 77 columns and the colunm names include the following: ID, Name, LongName, photoUrl, playerUrl, Nationality, Positions, Age, OVA, POT, Team & Contract, Height, Weight, foot, BOV, BP, Growth, Joined, Loan Date End, Value, Wage, Release Clause, Attacking, Crossing, Finishing, Heading Accuracy, Short Passing, Volleys, Skill, Dribbling, Curve, FK Accuracy, Long Passing, Ball Control, Movement, Acceleration, Sprint Speed, Agility, Reactions, Balance, Power, Shot Power, Jumping, Stamina, Strength, Long Shots, Mentality, Aggression, Interceptions, Positioning, Vision, Penalties, Composure, Defending, Marking, Standing Tackle, Sliding Tackle, Goalkeeping, GKDiving, GK Handling, GK Kicking, W/F, SM, GK Positioning, GK Reflexes, Total Stats, Base Stats, A/W, D/W, IR, PAC, SHO, PAS, DRI, DEF, PHY, Hits. 

## Data Transformation
I will be using the Microsoft Power BI tool. In order not to get confused, disconnected from the data cleaning process, i decided  to take the columns step by step and also document the process

## Special Character
Using the power query editor and changing it to UTF-8 encoding, the application helped to remove majority of the strings and special characters from the data



