## Introduction
The fold “data” contains two files “nba.csv” and “wnba.csv” which are the data from the article The Greatest Unexpected NBA Performances published in February 2023, covering the most unexpected performance data for every player from 1985 to 2022. The source of these data is basketball-reference.com.

Russell Samora is the creator of this dataset and a journalist-engineer at The Pudding. He is good at making stories with data and code, and he has produced 59 stories to date. If you are interested in the stories he created, you can click the link for details:https://pudding.cool/author/russell-samora/
Get in touch: russell@pudding.cool

## Metadata
Below you'll find a table with a list of the variables in this dataset and a brief description of what they are.
| Header       | Description                              | Data Type |
| ------------ | ---------------------------------------- | --------- |
| `bbrID` | basketball-reference player id | text |
| `Date` | date of game | text |
| `Tm` | player's team during game | text |
| `Opp` | opponent team during game | text |
| `TRB` | total rebounds | number |
| `AST` | assists | number |
| `STL` | steals | number |
| `BLK` | blocks | number |
| `PTS` | points | number |
| `GmSc` | Gamescore | number |
| `Season` | season | text |
| `Playoffs` | was playoffs | boolean |
| `Year` | year | number |
| `GameIndex` | game number in career | number |
| `GmScMovingZ` | z-score of game from moving average | number |
| `GmScMovingZTop2Delta` | difference between top 2 games' z-scores | number |
| `Date2` | date of second game | text |
| `GmSc2` | Gamescore of second game | number |
| `GmScMovingZ2` | z-score of second game from moving average  | number |
