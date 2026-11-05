<img src="https://github.com/canistag/chiclets/blob/main/canistag nhl.png" align="left" width="100" height="100" style="margin-right: 15px;">

<br>

# Chiclets
<br> An ongoing hockey database project that uses Jupyter Notebook to create a similarity engine between inactive and active #1 draft picks in the NHL.

# Question
Can we use Python to predict the careers of #1 draft picks in the NHL? Can we find players with similar records?

# Findings

| | Average Career Stats of Retired #1s | Average Career Stats of Active #1s |
| ---- | --- | --- |
| Average Games Played |  863.81 | 701.16 |
Average Goals Scored | 254.11 | 241.26 |
Average Assists |  398.59 | 367.21 |
Average Points | 652.7 | 608.47 |
Average Penalty Minutes | 760.41 | 344.74 |
Average Plus Minus | 7.08 | 34.37 |
Average Point Shares | 70.94 | 82.3 |

For the screenshot below, I used StandardScaler, NearestNeighbors, and some aggregation in order to predict Jack Hughes' lifetime points and similar retired players. 
<img width="1098" height="582" alt="image" src="https://github.com/user-attachments/assets/ec1119e0-e38e-46c5-bb29-89b6b31669a9" />



# Data
Credit for the database goes to Matt OP at https://www.kaggle.com/code/mattop/nhl-draft-player-analysis-1963-2022. I did make changes to Juraj Slafkovsky's entry to match the stats as of 10-15-2026.

# Future Ideas
- Stats by season (Is there a difference between rookie/veteran season stats? When do they start to taper off?)
- Introduce newer draft picks (Gavin McKenna, Macklin Celebrini, etc.)
- Visualizations
