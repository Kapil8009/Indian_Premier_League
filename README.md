# Indian_Premier_League
# IPL Matches Analysis

This project focuses on analyzing IPL (Indian Premier League) cricket matches data. The dataset contains detailed information about matches played across multiple seasons, including team performances, player statistics, and match outcomes. The analysis aims to uncover insights and trends in the IPL matches.

## Dataset

The dataset contains the following columns:
- `id`: Unique identifier for each match.
- `season`: The season in which the match was played.
- `city`: The city where the match was held.
- `date`: The date of the match.
- `match_type`: Type of the match (e.g., League, Qualifier, Final).
- `player_of_match`: The player awarded as the best performer of the match.
- `venue`: The stadium where the match was played.
- `team1` and `team2`: The two teams that played the match.
- `toss_winner`: The team that won the toss.
- `toss_decision`: The decision made by the toss winner (bat/field).
- `winner`: The team that won the match.
- `result`: The result type (e.g., runs, wickets).
- `result_margin`: The margin by which the match was won.
- `target_runs` and `target_overs`: The target score and overs for the chasing team.
- `super_over`: Indicates if a super over was played.
- `umpire1` and `umpire2`: The umpires officiating the match.

## Key Features of the Analysis

1. **Data Cleaning**:
    - Handled missing values using forward fill and mode imputation techniques.
    - Dropped unnecessary columns like `method`.

2. **Exploratory Data Analysis (EDA)**:
    - Analyzed the distribution of matches won by each team.
    - Visualized the top players based on the number of `player_of_match` awards.
    - Examined the impact of toss decisions on match outcomes.
    - Identified matches with the highest winning margins.

3. **Visualizations**:
    - Bar plots, pie charts, and histograms were used to represent data trends.
    - Count plots to show the frequency of match results.
    - Stacked bar charts to compare toss decisions and match outcomes.

4. **Insights**:
    - Percentage of matches won by toss winners.
    - Top 5 teams based on the number of matches played.
    - Distribution of wins by runs and wickets.

## Tools and Libraries Used

- **Python**: The primary programming language for analysis.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib** and **Seaborn**: For data visualization.
- **NumPy**: For numerical computations.

## How to Use

1. Clone the repository and ensure the dataset is available in the `Data` folder.
2. Open the Jupyter Notebook and execute the cells sequentially.
3. Explore the visualizations and insights generated from the analysis.

## Conclusion

This project provides a comprehensive analysis of IPL matches, helping cricket enthusiasts and analysts understand team performances, player contributions, and match dynamics. The visualizations and insights can be used to make data-driven decisions and predictions for future IPL seasons.
