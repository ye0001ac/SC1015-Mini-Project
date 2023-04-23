# SC1015-Mini-Project
Dota 2 Player Data Analysis

Collaborators:
Joel Chan Jia Le
Yeo Isaac
Goh Jun Hui

Repo Contents:
Data Analysis.ipynb - main body of the mini-project, contains all of our analysis and results
Data Collection.ipynb - data parsing from OpenDota API
sample1.csv - Dota Player Data used in Data Analysis
sample2.csv - Dota Hero Data used in Data Analysis

Project Description:
In this project we want to learn to play as a better core player in DOTA. DOTA is a 5v5 Online Multiplayer Battle Arena where players battle it out to destroy each others ancients. Core players in DOTA farm creeps and get gold and exp to buy items and improve their heroes abilities. this results in them being stronger in fights and eventually win the game. With data that we acquired from Opendota, we plan to build a model that predicts the rank of core players, and in doing so, find out what metrics we need to improve on

Conclusions:
With the models we have created, our results largely tally with our initial predictions. Low rank players are behind in most metrics, as expected. Generally to improve as a core player, we should learn how to pick good fights better, how to farm more efficiently and also having better map awareness to avoid deaths while not sacrificing the objectives. Additionally, based on the few anomalous data points, the meta appears to favour more fast-paced heroes that are strong and fight early on rather than heroes that farm and drag to the late game. We should also look to drfat heroes that can fight together as a team instead of playing the game alone. Finally, we should avoid high-variance heroes and focus on those that can deliver consistently.
The most common metrics that differentiate high rank players and low rank players in both winning and losing games are gold per minute, last hits per minute, deaths per minute ans exp per minute. Players should focus on improving these metrics should they want to improve
