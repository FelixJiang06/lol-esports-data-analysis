# League of Legends Esports Data Analysis



### Overview

This project explores professional League of Legends match data from the 2025 competitive season using Python. It focuses on player performance, champion selection patterns, and differences in match duration between teams through exploratory data analysis, data visualization, and linear regression.



### Analysis

- **Player Performance Analysis:** Calculated Damage Conversion Rate (DCR) for T1 players and compared average DCR across different positions.
- **Champion Selection Analysis:** Analyzed Faker's champion usage frequency and visualized his most frequently played champions using a bar chart.
- **Linear Regression:** Built a linear regression model using T1 match data to examine the relationship between kills, deaths, assists, and earned gold per minute. Applied the model to Weibo Gaming (WBG) data and compared predicted values with actual results.
- **Team Comparison:** Created a boxplot to compare the distribution of match durations for T1 and WBG.



### Technologies

- Python
- pandas
- matplotlib
- scikit-learn
- Jupyter Notebook



### Dataset

The project uses match-level data from the 2025 League of Legends competitive season. Please refer to the original dataset source and its usage terms before redistributing the data.

Original dataset homepage: https://oracleselixir.com/tools/downloads

### How to Run

1. Install Python and Jupyter Notebook.
2. Install the required Python packages.
3. Place the dataset in the project directory and ensure its filename and format match the data-loading code in `lol-esports-data-analysis.ipynb`.
4. Open `lol-esports-data-analysis.ipynb` in Jupyter Notebook and run the cells in order.

Install the main dependencies with:

```bash
pip install pandas matplotlib scikit-learn jupyter
```



### Key Takeaways

This project demonstrates how data analysis and statistical modeling can be used to investigate player performance, champion selection, and team-level match patterns in professional e-sports.