# Project_2_SuperBowlPrediction
![images](https://user-images.githubusercontent.com/104388678/192389256-068e437e-7e6d-45c2-9dad-e50708e2fe8c.png) 

###  Technology Advancement 

We plan to develop new predicitve models for NFL Sports Team's win advantage. 

![image](https://user-images.githubusercontent.com/104388678/192389870-63ad38ed-45df-4367-9983-fda9954eb42b.png)

### Background

To begin, a background into the sport that we will be focusing our models on. The Super Bowl is the annual final playoff game of the National Football League to determine the league champion. It has served as the final game of every NFL season since 1966, replacing the NFL Championship Game. The technology we are primarily utlizing for this project is Machine learning (ML). This is a field of inquiry devoted to understanding and building methods that 'learn', that is, methods that leverage data to improve performance on some set of tasks.

### Project Objective 

Using NFL data from 2011-2021, we will predict teams that will most likely go to the SuperBowl and one team that will most likely win.  We will develop a deep look into concepts of prediction and neural networks to find the next winner of the Super Bowl everytime!


### Project Summary

Taking a "5-Prong" approach, we were able to narrow the landscape of 32 NFL teams down to 6 teams most likely to contend for the SuperBowl. We were able to do this 12 weeks ahead of the end of the regular season.  By using a NFL sports tracking API, our model could update the prediction weekly based on wins and losses as the season draws nearer to the close. We believe that with more time to create additional coding and a few more weeks into the season, we could have predicted the winner with ~80-90% accuracy. See presentation and below for the following approaches used.

* `Logistic Regression` algorithm yielded a 79% accuracy for predicting winning/losing teams
* `Clustering` algorithm using KMeans and elbow method predicted the 'Top 7' likely teams based on an aggregated ten years of 'Wins' and 'Net Pts'
* `Deep Learning` Neural Network algorithm yielded three different results.  The best model predicted with 87.5% accuracy winning/losing teams
* `Decision Tree` algorithm yielded two teams.
* `MS Excel` Pivot tables using the 80:20 rule outlined the 'Top 16' best performing teams most likely to win the nextSuperBowl. 

The winner of SuperBowl of LVII will be one of the following teams: `Green Bay Packers`, `Kansas City Chiefs`, `Tampa Bay Bucaneers`, `Dallas Cowboys`, `Philadelphia Eagles`, or the `Buffalo Bills`.

We also started the framework of a 'Bot' using AWS that interprets data retrieved from an API source and communicates scores and teams based on preferences and interactions from users. 


### References
https://www.nfl.com/stats/team-stats/

https://www.nfl.com/standings/

https://www.pro-football-reference.com/

https://en.wikipedia.org/wiki/Super_Bowl#cite_note-1

https://en.wikipedia.org/wiki/Machine_learning#cite_note-1

Mitchell, Tom (1997). Machine Learning. New York: McGraw Hill. ISBN 0-07-042807-7. OCLC 36417892.
