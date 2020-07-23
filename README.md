# ODI-Cricket-Match-Prediction

<h2>Overview</h2>
<p>
With the advent of statistical modeling in sports, predicting the outcome of a game has been established as a fundamental problem. Cricket is one of the most popular team games in the world. Moreover cricket betting is a multi-billion dollar market. Therefore, there is a strong incentive for models that can predict the outcomes of games and beat the odds provided by bookers. The aim of this study is to investigate to what degree it is possible to predict the outcome of cricket matches.
</p>
<p>
Cricket matches are quite unpredictable. Considering only ODI matches, we will try to predict who is going to be the winner of the match, before the match begins. 
Suppose we know that there is going to be an ODI match between Team A and Team B in near future. Before the match begins, our ML model should predict which team will win the match.
</p>

<h2>Data Collection</h2>
Ball by ball records of every international ODI match is available on the web, in computer readable format. The data has been gathered from <a href="https://cricsheet.org/"><u>Cricsheet</u></a>.Entire dataset has been built from scratch and every feature has been normalised before feeding into the model. 
<br>
<h2>The Main Approach</h2>
<ul>
  <li>I experimented with various classification models like Naive Bayes, Logistic Regression, Random Forest, SVC etc.</li>  
  <li>I have updated the team features for every match by using the last 5 matches played by the individual teams.</li>
  <li>Surprisingly it has been observed that, in none of the research papers or blogs, RNNs has been used for the prediction although we know that they are supposed to perform well on any sequential data very well, like LSTM  and GRU has been previously used for stock market prediction. 
</li>
  <li>However when we tried to exploit the LSTM network it was actually a colossal failure. Due to lack of expertise we may have gone wrong with the fundamental idea, but we definitely plan on working on it at a later point of time.
</li>
</u>
