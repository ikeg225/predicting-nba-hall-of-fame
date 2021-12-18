# Predicting NBA Hall Of Famers

## Data Collection and Cleaning

All data was collected off the website https://www.basketball-reference.com/ using Urlib/Regex and cleaned using Pandas/NumPy. Every season of each 4,978 players that have any NBA or ABA stats were scraped. For each of the seasons the Per Game regular season/playoffs and Advanced regular season/playoffs were used. 

Features include:
- Player Name
- Season
- Age
- Team
- League
- All Star Team
- Championship
- \*Position 
- \*Games
- \*Games Started
- \*Minutes Per Game
- \*Field Goals Per Game
- \*Field Goal Attempts Per Game
- \*Field Goal Percentage
- \*3-Points Per Game
- \*3-Point Attempts Per Game
- \*3-Point Percentage
- \*2-Points Per Game
- \*2-Point Attempts Per Game
- \*2-Point Percentage
- \*Effective Field Goal Percentage: This statistic adjusts for the fact that a 3-point field goal is worth one more point than a 2-point field goal.
- \*Free Throws Per Game
- \*Free Throw Attempts Per Game
- \*Free Throw Percentage
- \*Offensive Rebounds Per Game
- \*Defensive Rebounds Per Game
- \*Total Rebounds Per Game
- \*Assists Per Game
- \*Steals Per Game
- \*Blocks Per Game
- \*Turnovers Per Game
- \*Personal Fouls Per Game
- \*Points Per Game
- \*Minutes Played
- \*Player Efficiency Rating: A measure of per-minute production standardized such that the league average is 15.
- \*True Shooting Percentage: A measure of shooting efficiency that takes into account 2-point field goals, 3-point field goals, and free throws.
- \*3-Point Attempt Rate: Percentage of FG Attempts from 3-Point Range.
- \*Free Throw Attempt Rate: Number of FT Attempts Per FG Attempt.
- \*Offensive Rebound Percentage: An estimate of the percentage of available offensive rebounds a player grabbed while they were on the floor.
- \*Defensive Rebound Percentage: An estimate of the percentage of available defensive rebounds a player grabbed while they were on the floor.
- \*Total Rebound Percentage: An estimate of the percentage of available rebounds a player grabbed while they were on the floor.
- \*Assist Percentage: An estimate of the percentage of teammate field goals a player assisted while they were on the floor.
- \*Steal Percentage: An estimate of the percentage of opponent possessions that end with a steal by the player while they were on the floor.
- \*Block Percentage: An estimate of the percentage of opponent two-point field goal attempts blocked by the player while they were on the floor.
- \*Turnover Percentage: An estimate of turnovers committed per 100 plays.
- \*Usage Percentage: An estimate of the percentage of team plays used by a player while they were on the floor.
- \*Offensive Win Shares: An estimate of the number of wins contributed by a player due to offense.
- \*Defensive Win Shares: An estimate of the number of wins contributed by a player due to defense.
- \*Win Shares: An estimate of the number of wins contributed by a player.
- \*Win Shares Per 48 Minutes: An estimate of the number of wins contributed by a player per 48 minutes (league average is approximately .100)
- \*Offensive Box Plus/Minus: A box score estimate of the offensive points per 100 possessions a player contributed above a league-average player, translated to an average team.
- \*Defensive Box Plus/Minus: A box score estimate of the defensive points per 100 possessions a player contributed above a league-average player, translated to an average team.
- \*Box Plus/Minus: A box score estimate of the points per 100 possessions a player contributed above a league-average player, translated to an average team.
- \*Value over Replacement Player: A box score estimate of the points per 100 TEAM possessions that a player contributed above a replacement-level (-2.0) player, translated to an average team and prorated to an 82-game season. Multiply by 2.70 to convert to wins over replacement.

The * indicates the feature also has a separate playoffs column 