# Nepal Premier League (NPL) 2024 Analysis

This repository contains an exploratory data analysis of the inaugural Nepal Premier League (NPL) 2024. The NPL is a T20 cricket league in Nepal, and this project aims to provide insights into various aspects of the tournament using Python, data manipulation, and visualization libraries.

## Project Overview

- **Objective**: To analyze the inaugural NPL 2024 season, understand match outcomes, player performances, and overall trends.
- **Datasets**:
  - **NPL_matches.csv**: Contains high-level match details such as match ID, teams, winner, MVP, and total runs scored.
  - **NPL_final.csv**: Contains ball-by-ball data with detailed information for each delivery (innings, batter, bowler, over, runs scored, wicket type, shot direction, etc.).
- **Notebook**: The Jupyter Notebook (`NPL_Analysis.ipynb`) showcases the data cleaning, exploratory analysis, and visualization process.


## Data Description

### NPL_matches.csv
- **match_id**: Unique identifier for each match.
- **team1** & **team2**: The two teams playing the match.
- **winner**: The team that won the match.
- **mvp**: Player who received the Man of the Match award.
- **runs_scored**: Total runs scored in the match (both innings combined).
- Other match-related columns like date, venue, etc. (if available).

### NPL_final.csv
- **match_id**: Identifier to link with `NPL_matches.csv`.
- **innings**: The innings number (1 or 2).
- **over**: Over number (1 to 20).
- **ball**: Delivery count within an over (1 to 6).
- **batter** & **bowler**: The batter and bowler for each delivery.
- **runs**: Runs scored off the delivery.
- **wicket_type**: If a wicket fell on that delivery, the mode of dismissal.
- **shot_direction**: The direction of the shot played (if available).
- Other ball-by-ball details (e.g., extras, runs off the bat, etc.).

## Analysis & Visualizations

In the Jupyter Notebook, a variety of analyses and visualizations have been conducted, including but not limited to:

1. **Toss Decision**  
   - How often teams choose to bat or bowl first after winning the toss.

2. **Toss Impact**  
   - Influence of the toss on match outcomes (e.g., does winning the toss correlate with winning the match?).

3. **Chasing vs Defending**  
   - Comparing the success rate of teams batting first vs. batting second.

4. **Team Discipline (Extras Conceded)**  
   - Analyzing which teams gave away the most extras (wides, no-balls, byes, etc.).

5. **Top 5 Players with the Most Man of the Match Awards**  
   - Identifying standout performers who frequently won MVP honors.

6. **Runs Scored by a Batsman Against Each Team**  
   - Checking how certain batters perform against different bowling attacks.

7. **Batsmen with the Most Sixes**  
   - Highlighting the biggest hitters of the tournament.

8. **Comparing Batsmen with the Most Dot Balls and Their Strike Rates**  
   - Investigating if a high number of dot balls affects a batsman’s strike rate.

9. **Bowlers with the Most Dot Balls**  
   - Finding the most economical bowlers who consistently kept batsmen under pressure.

10. **Distribution of Shot Directions**  
    - Visualizing the shot directions to see batting tendencies.

11. **Phase-wise Bowling Performance**  
    - Examining how bowlers performed in different phases of an innings (e.g., Powerplay, Middle Overs, Death Overs).

12. **Match Progression**  
    - Tracking run progression throughout the innings (over-by-over analysis).

Each section in the notebook contains code cells with explanations, charts, and observations.
