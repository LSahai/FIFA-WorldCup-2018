# Predicting FIFA world cup 2018 winner

### Abstract
The most awaited tournament in football is the world cup that is conducted
once every 4 years. 32 football playing nations will participate in the 2018 tournament held in
Russia and one will emerge as the winner eventually.

### Objective:  
Analyze the dataset, understand the teams, players, rankings . Build a model predicting FIFA 2018 results.
1) Predict 4 Semi Finalists
2) Predict 2Finalists
3) Predict winner of 2018
4) Predict the World Cup Winner

### Approach Followed - Datapreprocessing, Exploratory Data Analysis, Data Modeling Techniques
### Modeling Techniques-Logistic Regression, Random Forest
### Result Analysis-Logistic Regression accuracy of 41.23%
###                 Random Forest accuracy of 64.79%	

### Dataset
1) World Cup 2018 Matches-This dataset consists match fixtures of all teams along with information on previous titles, previous finalists, semi finalists and their rankings.
2) Results-This dataset consists results of all football matches played between various countries from 1930 onwards
3) FIFA Rankings-Data contains rankings of teams from 1993 onwards
4) Elo Ratings-This data contains Elo ratings of football teams based on the Elo rating system, developed by Dr. Arpad Elo. This rating has been chosen as it works well for a Zero Sum game such as football

### Tools &Techniques-
We have used R programming for doing our analysis. We have performed data cleaning, Exploratory data analysis and applied data mining models to predict the winner of World Cup 2018. We have used two models for prediction analysis, Random forest and Logistic Regression. Models was applied on all the group matches to obtain winner of each group. 44 out of the 48 group matches were predicted correctly giving an accuracy of 61.97% for random forest model compared to logistic model which gave an accuracy of 41.23%. So we made the conclusion using the random forest model since it gave the highest accuracy.

### Results:
1) We predicted the group matches results, and were able to get an accuracy of 92%.
2) Further we predicted the semifinalists for the World cup match and in our model it came up: Portugal, Brazil, Spain and England.
3) World Cup winner: Brazil
4) Runner Up: Spain

### Conclusion:
In this project, we concluded that Random Forest is better approach than the Logistic Regression.
The reason is Random Forest is producing accuracy of 64.79% which is much higher than the Logistic Regression which is producing accuracy of only 41.23%. 
We predicted that Brazil is the winner of FIFA world cup 2018 through Random Forest whereas Uruguay is the winner through Logistic Regression.
We have achieved our business objective that is FIFA world cup winner prediction, which is accurate as per the past records available. But, in real France has won the FIFA world cup 2018. 


