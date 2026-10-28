<img src="https://github.com/canistag/chiclets/blob/main/canistag nhl.png" align="left" width="100" height="100" style="margin-right: 15px;">

<br>

# Chiclets
<br> An ongoing hockey database project that uses Jupyter Notebook to predict career stats of #1 draft picks and matches them to similar inactive players.

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
<img width="945" height="587" alt="image" src="https://github.com/user-attachments/assets/102cd3db-03cc-4e0e-a5cc-7a2342c1ffeb" />


# Data
Credit for the database goes to Matt OP at https://www.kaggle.com/code/mattop/nhl-draft-player-analysis-1963-2022. I did make changes to Juraj Slafkovsky's entry to match the stats as of 10-15-2026.

# Future Ideas
- Stats by season (Is there a difference between rookie/veteran season stats? When do they start to taper off?)
- Introduce newer draft picks (Gavin McKenna, Macklin Celebrini, etc.)
- Visualizations
