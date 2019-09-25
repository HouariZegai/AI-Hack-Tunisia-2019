# AI Hack Tunisia #5 - Predictive analytics challenge #2
This challenge was designed specifically for the AI Tunisia Hack 2019, which takes place from 20 to 22 September. Welcome to the AI Tunisia Hack participants!

## Challange link
http://zindi.africa/competitions/ai-tunisia-hack-5-predictive-analytics-challenge-2

## Challange info
Flight delays not only irritate air passengers and disrupt their schedules but also cause :
* a decrease in efficiency
* an increase in capital costs, reallocation of flight crews and aircraft
* an additional crew expenses

As a result, on an aggregate basis, an airline's record of flight delays may have a negative impact on passenger demand.

This competition aims to predict the estimated duration of flight delays per flight

This solution proposes to build a flight delay predictive model using Machine Learning techniques. The accurate prediction of flight delays will help all players in the air travel ecosystem to set up effective action plans to reduce the impact of the delays and avoid loss of time, capital and resources.

## Data [[here](datasets)]
You will find below the explanation of the different abbreviations:

DATOP Date opération

FLTID N° Vol

DEPSTN Esacle Départ

ARRSTN Escale arrivée

STD Scheduled Time departure

STA Scheduled Time arrival

STATUS Etat du vol

ETD Expected Time depature

ETA Expected Time arrival

ATD Actual Time of Departure

ATA Actual Time of arrival

DELAY1 Code retard 1

DUR1 durée retard 1

DELAY2 Code retard 2

DUR2 durée retard 2

DELAY3 Code retard 3

DUR3 durée retard 3

DELAY4 Code retard 41

DUR4 durée retard 4

AC Aircraft Code

## Rules
As this is a learning challenge, aside from the rules in the Zindi Terms of Use, no other particular rules apply.

We do, however, encourage all participants to share their code with Zindi, as well as on GitHub as a public good to the sector.

Note that there is Public and Private Leaderboards. The Public Leaderboard excludes approximately 80% of the test dataset. While the competition is open, the Public Leaderboard will rank the submitted solutions by the accuracy score they achieve. Upon close of the competition, the Private Leaderboard, which covers 100% of the test dataset, will be made public and will constitute the final ranking for the competition.

There is no maximum submission limit.

We reserve the right to modify these rules at any time as necessary.

## Evaluation
The metric used for this challenge is Root Mean Square Error.

Then the submission file should be as follows:

| id        |  target |
|-----------:|:---------|
| test_id_0 |  2470 |
| test_id_1 |  30 |

This means that the flight happening at date (mapping to test_id_1) for the flight number (mapping to test_id_1) will be late with 30 minutes.

## Timeline
Competition closes on 21 September 2019

Final submissions must be received by 07:00 GMT.

We reserve the right to update the contest timeline if necessary.
