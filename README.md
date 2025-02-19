# NBA Data Analysis

## Overview
This project analyzes NBA player data from 2018-19 to the present (2024-2025) to uncover insights into player performance, game trends, and statistical correlations. The analysis includes data cleaning, statistical analysis, and interactive visualizations using Python.

## Dataset
- **Source**: `nba_play_data.xlsx`
- **Columns**: Various player statistics (excluding 'RANK' and 'EFF', which were removed in preprocessing).

## Key Analyses
1. **Data Cleaning & Preparation**
   - Loaded and cleaned NBA player statistics.
   - Removed unnecessary columns and handled missing values.

2. **Player Stats Correlation**
   - Analyzed correlations between different player statistics.
   - Used visualizations to identify significant relationships.

3. **Minutes Played Distribution**
   - Explored how playing time is distributed among players.
   - Created visual representations of playing time patterns.

4. **Trends Since 2018-2019**
   - Investigated how the game has evolved over recent seasons.
   - Examined shifts in key metrics like scoring, assists, and efficiency.

5. **Regular Season vs. Playoffs**
   - Compared player performance metrics in the regular season versus playoffs.
   - Identified significant differences in player contributions.

## Visualizations
This project includes several interactive **Plotly visualizations**, created using Graph Objects, to enhance the data analysis:
- **Custom Graphs**: Various interactive visualizations explored trends and correlations.
- **Performance Comparisons**: Graphs highlight differences in player statistics between the regular season and playoffs.
- **Time-Based Trends**: Charts display how metrics like scoring and efficiency have changed over recent seasons.

## Technologies Used
- **Pandas**: Data manipulation and analysis.
- **Plotly**: Interactive visualizations.
- **Jupyter Notebook**: Analysis and visualization.

## How to Use
1. Install required libraries:
   ```bash
   pip install pandas plotly openpyxl
   ```
2. Run the Jupyter Notebook to execute the analysis.

## Results
- The project provides insights into NBA player performance trends.
- Interactive visualizations allow for a deeper exploration of statistics.

## Future Work
- Expand the dataset to include more seasons.
- Implement machine learning models for player performance prediction.

## Author
Developed by Marcus Li


