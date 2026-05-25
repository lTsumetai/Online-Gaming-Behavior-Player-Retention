# Case Study of online gaming behaviour dataset 

## Repository Outline
1. README.md - General project overview and documentation
2. P0M1_Fauzi_maulana.ipynb - Notebook containing data analysis and visualizations using Python
3. online_gaming_behavior_dataset.csv - Dataset used for analysis

## Problem Background
main goal is to achive stable player count and improving player experience, within the next season 6 months prior so the player base would be much healthier. stable player counts can be studied by how,when, and what players play. 

## Project Output
Exploratory Data Analysis (EDA) with 5 visualizations:

- Bar chart: Average sessions per week by engagement level


## Data
- Source: Kaggle — Online Gaming Behavior Dataset
- Rows: 40,034
- Columns: 13
- Missing values: None
- Duplicates: None
- Key columns: PlayerID, Age, Gender, Location, GameGenre, GameDifficulty, SessionsPerWeek, AvgSessionDurationMinutes, PlayTimeHours, InGamePurchases, EngagementLevel

## Method
This project uses statistical analysis and EDA methods:

- Two-Sample T-Test — to test whether playtime differs significantly between Low and High engagement players
- Central Tendency (mean, median, mode) — to understand typical session frequency across the playerbase


## Stacks
Language: Python 3
Libraries:

- pandas — data manipulation and aggregation
- matplotlib — data visualization
- scipy — statistical testing (T-test)
- numpy — numerical operations


Tools: Jupyter Notebook

## Reference
- Dataset — [Kaggle Online Gaming Behavior](https://www.kaggle.com/datasets/rabieelkharoua/predict-online-gaming-behavior-dataset)