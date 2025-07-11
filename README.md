# IPL data analysis
Historical Data Analysis Of The Indian Premier League

# This repository contains a Jupyter Notebook (ipl.ipynb) dedicated to analyzing Indian Premier League (IPL) match data. The project aims to provide insights into various aspects of IPL matches through data manipulation, exploration, and visualization using Python's pandas, matplotlib, and seaborn libraries within a Google Colab environment.

## 📁 About the Dataset (`matches.csv`)

The core of this analysis is the `matches.csv` dataset, which contains comprehensive information about individual IPL matches. Each row in the dataset represents a unique match and includes the following key columns:

- **id**: Unique identifier for each match  
- **season**: The IPL season (e.g., '2008', '2009')  
- **city**: The city where the match was played  
- **date**: The date the match took place  
- **match_type**: The type of match (e.g., 'League', 'Eliminator')  
- **player_of_match**: The player who was awarded "Player of the Match"  
- **venue**: The stadium where the match was held  
- **team1**: Name of the first team participating in the match  
- **team2**: Name of the second team participating in the match  
- **toss_winner**: The team that won the toss  
- **toss_decision**: The decision made by the toss-winning team ('bat' or 'field')  
- **winner**: The team that won the match  
- **result**: The outcome of the match (e.g., 'runs', 'wickets', 'No Result')  
- **result_margin**: The margin of victory (e.g., number of runs or wickets)  
- **target_runs**: The target runs set in the second innings  
- **target_overs**: The target overs for the second innings  
- **super_over**: Indicates if the match went to a Super Over ('Yes' / 'No')  
- **method**: The method used to determine the result (e.g., 'D/L' for Duckworth–Lewis method)  
- **umpire1**: Name of the first umpire  
- **umpire2**: Name of the second umpire  

This dataset provides a rich foundation for exploring various aspects of IPL match dynamics, team strategies, and individual performances.
