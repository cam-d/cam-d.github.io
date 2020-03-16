## Projects

---

### Kaggle ML March Madness 2020 <br>
Sadly the tournament isn't happening, so I'll guess I'll have to wait until next year to see how I did.
<br> <br>
I used the data provided by [Kaggle](https://www.kaggle.com/c/google-cloud-ncaa-march-madness-2020-division-1-mens-tournament/data) to make this summary dashboard for past years tournaments.
<br>
[NCAA Tourney Dashboard (Tableau Public)](https://public.tableau.com/profile/cameron.de.la.pena#!/vizhome/NCAABasketball_15841125763020/Dashboard1)
<br>
<img src="images/ncaa_viz.PNG?raw=true"/>
<br>
<br>
Used BeautifulSoup to get stats from TeamRankings.com and KenPom.com.  Added these to to the season games data provided by Kaggle. 
<br>
[Get External NCAA Basketball Stats](https://github.com/cam-d/cam-d.github.io/blob/master/teamRankings.ipynb)
<br><br>
Python Notebook for reformating and combining stats from Kaggle and external sources, then predicting for 2015-2019 seasons. <br>
[NCAA Notebook](https://github.com/cam-d/cam-d.github.io/blob/master/NCAA_Bball_copy.ipynb)
<br>
1.	Reformat data to list lower TeamID first, same format needed for Kaggle submission.
2.	Aggregating regular season stats to use as features.
3.	Add regular season, KenPom and TeamRanking stats to TourneyResults data to create data set for training and testing.
4.	Create features that compare each stat for team_x and team_y (difference and ratio).
5.	Define function for training and testing.  For example, train on the 2007-2014 tournaments, test on 2015 tournament.
6.	Predict game results using Logistic Regession and Neural Networks (MLP).

---

### Fairfax Country Property Values
<br>
Looking through data.gov, I saw quite a bit of data provided by Fairfax County tax administration office.  I was originally looking for home prices similar to what might be on RedFin or Zillow, but since they had made so much data available it seemed a shame not to use it.  <br>
[Median Assessed Property Values viz (Tableau Public)](https://public.tableau.com/profile/cameron.de.la.pena#!/vizhome/FfxHouses/Dashboard1)

---

<!--### Category Name 2-->

<!-- - [Project 1 Title](http://example.com/)-->



---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
