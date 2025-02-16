Cricket T20 Data Analysis
This repository contains Python scripts and datasets used for analyzing T20 cricket batters and bowlers using ball-by-ball data extracted from cricsheet.org.
Project Overview:
This project aims to identify elite and underrated players using data-driven analysis. We have analysed T20 batters and bowlers based on key performance metrics.
Files Included:
1. Batter Analysis (t20_analysis.ipynb):
Objective: Identifying the best T20 batters based on Strike Rate (SR), Runs Per Innings (RPI), Balls Per Dismissal (BPD), and Balls Per Boundary (BPB).
Methodology:
Weighted averages were calculated to account for differences in sample size.
Players were ranked using percentile calculations.
Filters were applied to identify elite batters who meet multiple conditions (e.g., top 75th percentile for SR, RPI, etc.).
2. Bowler Analysis (t20_bowleranalysis.ipynb):
Objective: Evaluating T20 bowlers using metrics like Economy Rate (ECO), Average (AVG), Strike Rate (SR), Dot Ball Percentage, and Balls Per Boundary (BPB).
Methodology:
Weighted averages and percentiles were used to find elite bowlers.
Players with high dot ball percentages, low economy rates, and strong wicket-taking ability were prioritized.
The underrated bowler metric was introduced to find bowlers who perform well but don't get enough recognition.
How We Identified Elite Players:
Used Python to process ball-by-ball data and extract key statistics.
Percentile rankings helped in setting thresholds to filter out top-performing players.
Players meeting at least 3 out of 4 elite criteria were selected as elite performers.
Data Source:
The analysis is based on T20 match data collected from cricsheet.org.

Next Steps:
Expanding the dataset to include more tournaments.
Adding visualizations to better represent player performance.
Creating a prediction model for player performance trends.

Contributors:
Nakul Singh Lodhi
Feel free to contribute or suggest improvements!

