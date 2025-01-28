# NBA Player Performance Analysis

This repository contains a detailed analysis of NBA player performance based on historical game data. The analysis includes scraping data from Basketball-Reference, cleaning and merging the datasets, performing statistical visualizations, and exploring the relationship between player stats and team performance.

## Project Structure

- **`Code/`**: Contains Python scripts for data scraping, cleaning, and analysis.  
  - `NBA_Player_Performance_Analysis_Code.py`: Main Python script for data scraping, analysis, and visualization.
  
- **`Data/`**: Contains the NBA player statistics datasets for training and testing.

- **`README.md`**: Project description and usage instructions.

## Technologies Used
- Python
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Statsmodels
  - BeautifulSoup
  - Requests

## Description

This project aims to analyze NBA player performance using historical data. The analysis involves:
1. **Web Scraping**: Collecting game statistics from Basketball-Reference.
2. **Data Cleaning**: Preprocessing and merging data for analysis.
3. **Exploratory Data Analysis (EDA)**: Visualizing various statistical trends.
4. **Linear Regression Analysis**: Exploring relationships between player statistics and team performance (e.g., win percentage).

### Data Sources:
1. [Basketball-Reference](https://www.basketball-reference.com/) for scraping game stats.
2. Excel files for player statistics (e.g., `Team_Player_Stats_Train_2022_23.xlsx`, `Team_Player_Stats_Test_2023_24.xlsx`).

## Installation

To run this project locally, you'll need Python installed. You can install the required packages using pip:

```bash
pip install pandas numpy requests beautifulsoup4 seaborn matplotlib statsmodels openpyxl
```

## Usage

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/NBA_Player_Performance_Analysis.git
   ```

2. **Run the script**:
   Navigate to the `Code/` directory and run the script `NBA_Player_Performance_Analysis_Code.py`:
   ```bash
   python NBA_Player_Performance_Analysis_Code.py
   ```

3. **Data**: Ensure the dataset files (`Team_Player_Stats_Train_2022_23.xlsx` and `Team_Player_Stats_Test_2023_24.xlsx`) are located in the `Data/` folder for the script to access them.


This will scrape data, clean it, and generate visualizations including histograms, pair plots, scatter plots, and linear regression analysis.

## Expected Outputs:
- Distribution plots for player stats (e.g., Age, Height, Weight).
- Correlation matrix heatmap showing relationships between player statistics and win percentage.
- Scatter plots with linear regression lines to visualize the impact of player stats on team success.


## Known Issues / Future Work
- The web scraping process might break if the website structure changes.
- Plan to extend the analysis to include more detailed player performance metrics, such as advanced statistics (PER, True Shooting %).
