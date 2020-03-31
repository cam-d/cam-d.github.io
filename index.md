## Projects

---

### Kaggle ML March Madness 2020 <br>
Sadly the tournament didn't happned this year, so I'll have to wait until next year to officially compete on Kaggle.  On the training data provided by [Kaggle](https://www.kaggle.com/c/google-cloud-ncaa-march-madness-2020-division-1-mens-tournament/data), by including external data and summary season stats I was able to achieve log-loss in the .3-.5 range for each of the 2014-2019 seasons, and better accuracy than just always picking the higher ranked team.  Some of the work that went into the project is below.
<br>
* [NCAA Tourney Dashboard (Tableau Public)](https://public.tableau.com/profile/cameron.de.la.pena#!/vizhome/NCAABasketball_15841125763020/Dashboard1)
<br>
* Used BeautifulSoup to get stats from TeamRankings.com and KenPom.com -[Get External NCAA Basketball Stats](https://github.com/cam-d/Work_Examples/blob/master/teamRankings.ipynb)
<br>
* Python Code - [NCAA Notebook](https://github.com/cam-d/Work_Examples/blob/master/NCAA_Bball.ipynb)
  *	Reformat data to list lower TeamID first, same format needed for Kaggle submission.
  *	Aggregate regular season stats to use as features.
  *	Add regular season, KenPom and TeamRanking stats to TourneyResults data to create data set for training and testing.
  *	Create features that compare each stat for team_x and team_y (difference and ratio).
  *	Define function for training and testing.  For example, train on the 2007-2014 tournaments, test on 2015 tournament.

---

### Fairfax County Property Values
<br>
Looking through [data.gov](https://catalog.data.gov/dataset/tax-administrations-real-estate-assessed-values-1c608), I saw quite a bit of data provided by Fairfax County tax administration office.  The data consisted of assessed values for the land and buildings for each parcel, including residential and commercial, so I filtered just for those residential parcels with only 1 building on it to try to get an equivalent to single-family homes.  I was originally looking for home prices similar to what might be on RedFin or Zillow, but since they had made so much data available it seemed a shame not to use it.  <br>
* [Median Assessed Property Values viz (Tableau Public)](https://public.tableau.com/profile/cameron.de.la.pena#!/vizhome/FfxHouses/Dashboard1)
* Exploratory analysis using Streamlit and plotly.  [Streamlit gif](https://github.com/cam-d/Work_Examples/blob/master/StreamLit.gif)
* The data is available via API.
  * Calling data.gov API [Python](https://github.com/cam-d/Work_Examples/blob/master/Data.gov%20API)
* [R Script](https://github.com/cam-d/Work_Examples/blob/master/FFx%20Houses.pdf) to access data using the API, aggregate, cleanse, visualize, and ultimmately explore the relationship between house size and number of bedrooms and bathrooms with their sale price and appraised value for each city.  
---

<!--### Category Name 2-->

<!-- - [Project 1 Title](http://example.com/)-->



---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
