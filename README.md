# How the 3-Point Line Transformed the NBA

## Overview
This project analyzes the profound impact of the three-point shot on the NBA since its introduction in the 1979-80 season. Using historical data, the analysis examines how the three-point line has evolved from a novelty to a fundamental element of modern basketball strategy.

## Key Areas of Analysis
- **Evolution of Gameplay**: Changes in points per game and pace over time
- **Shifts in Offensive Strategies**: Transformation of scoring composition and shot distribution
- **Efficiency and Trade-Offs**: Relationships between pace, shooting percentages, and scoring efficiency
- **Broader Impact**: Influence of the 3-point line on other aspects of the game, including personal fouls and free throws

## Data Source
Historical NBA statistics from [Basketball-Reference.com](https://www.basketball-reference.com/leagues/NBA_stats_per_game.html), focusing on league-wide averages for regular seasons and playoffs.

## Key Findings
- The three-point shot has dramatically increased in usage, particularly since the 2010s
- Modern NBA teams now attempt more three-pointers than free throws for the first time in league history
- The game has become simultaneously faster (higher pace) and more efficient
- A negative correlation exists between three-point attempts and personal fouls, suggesting a shift toward less physical play
- Rule changes (particularly the shortened three-point line from 1994-97) had immediate but temporary impacts on shooting patterns

## Visualizations
The notebook contains nine key visualizations that illustrate:
1. Points per game and pace trends over NBA history
2. Correlation between pace and scoring
3. Composition of scoring (2PT vs 3PT vs FT)
4. Proportion of three-point attempts in total field goal attempts
5. Evolution of shot selection between two and three-point attempts
6. Shooting efficiency and pace relationships
7. Correlation between pace and field goal percentage
8. Relationships between free throws, three-point attempts, and personal fouls
9. Correlation between personal fouls and three-point attempts

## Tools & Technologies
- **Data Collection**: BeautifulSoup, Requests
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib

## Setup & Usage
1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Open the Jupyter notebook: `jupyter notebook DataPy_Project_NBA.ipynb`

## License
[MIT License](LICENSE)

## Acknowledgements
- Basketball-Reference.com for providing comprehensive historical NBA statistics
