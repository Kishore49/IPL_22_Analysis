# IPL_22_Analysis

This project analyzes the data from the Indian Premier League (IPL) 2022 season. The dataset includes match details such as teams, venues, scores, winners, and notable player performances.


## Libraries Used

- Pandas: For data manipulation and analysis.
- Plotly: For creating interactive visualizations.
- Dash: For building web applications.

## Getting Started

To run the analysis, make sure you have the required libraries installed. You can install them using:


pip install pandas plotly dash


## Dataset

The dataset `ipl_2022.csv` contains the following columns:

- `match_id`: Match ID
- `date`: Date of the match
- `venue`: Venue of the match
- `team1`: First team
- `team2`: Second team
- `stage`: Stage of the match (e.g., Group, Semi-Final, Final)
- `toss_winner`: Team that won the toss
- `toss_decision`: Toss decision (Field or Bat)
- `first_ings_score`: First innings score
- `first_ings_wkts`: Wickets lost in the first innings
- `second_ings_score`: Second innings score
- `second_ings_wkts`: Wickets lost in the second innings
- `match_winner`: Winner of the match
- `won_by`: Method of victory (Wickets or Runs)
- `margin`: Margin of victory
- `player_of_the_match`: Player of the match
- `top_scorer`: Top scorer in the match
- `highscore`: Highest score in the match
- `best_bowling`: Best bowling performance
- `best_bowling_figure`: Best bowling figures

## Analysis

1. **Number of Matches Won by Each Team**: A bar chart showing the number of matches won by each team.

2. **Matches Won by Defending and Chasing**: A pie chart showing the number of matches won by defending and chasing teams.

3. **Top Scorers in IPL 2022**: A bar chart showing the top scorers in the IPL 2022 season.

4. **Most Player of the Match Awards**: A bar chart showing the players with the most Player of the Match awards.

5. **Best Bowlers in IPL 2022**: A bar chart showing the best bowling performances in the IPL 2022 season.

6. **Matches Played and Wickets Taken by Team in Each Venue**: A stacked bar chart showing the matches played and wickets taken by each team in each venue.

## How to Use

1. **Import the CSV file**: Use the `pd.read_csv()` function to import the dataset.

2. **Read and Explore the Data**: Use `data.head()` to view the first few rows of the dataset and explore the columns.

3. **Run the Analysis**: Run the provided code snippets to generate the visualizations.

4. **Interact with the Dash App**: Use the Dash app to interactively explore matches played at different stadiums.


## Contributing

Feel free to contribute to this project by adding new features, fixing bugs, or improving the analysis code.
Just fork the repository, make your changes, and submit a pull request.
