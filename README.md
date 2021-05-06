<center><h1>NBA game prediction</h1></center>
<center>practice project</center>

---
This project is a part of my portfolio and its aim is to simply showcase some of my skills in acquiring and analysing data. <br>
It is not suitable as a model for gambling purposes and it should/can not be used as such.
<br>
<br>

### The project

<br>
Being a basketball fan/player with a growing interest in Data Science and ML I thought it would be a fun little project to scrape basketball stats and use them with classification models to predict outcomes.

<br>
<br>
The project is based on the assumption that this year's NBA finals will be between the Los Angeles Lakers and the Brooklyn Nets, so esssentially the models are used to predict a potential matchup in the finals between these two teams.
<br>
<br>
I have scraped stats of games between the two teams going back 30 years from [basketball-reference.com](https://www.basketball-reference.com) and then fed these stats into a number of classification models in scikit-learn to predict wins/losses.

<br>
<br>

#### Some notes:
* the teams have had only 60+ games in the last 30 years, which is obviously not a lot for a serious analysis
* the stats used are post game stats so the word 'prediction' is somewhat misleading in this case, apologies for that

<br>
I have plans for an updated version of this project in which I will aim to use basic box score stats (rather than advanced game stats) and also create more features to account for a number of things like minutes played by best scorers and best defenders on the team, overall league ratings of the teams at the time etc...

---
<br>
The data is available as a csv file from the repo.
