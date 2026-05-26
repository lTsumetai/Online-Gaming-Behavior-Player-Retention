# Case Study of online gaming behaviour dataset 

## Repository Outline
1. README.md - General project overview and documentation
2. Player Retention.ipynb - Notebook containing data analysis and visualizations using Python
3. online_gaming_behavior_dataset.csv - Dataset used for analysis

## Problem Background
Using  SMART framework, main goal is to achive stable player count and improving player experience, within the next season 6 months prior so the player base would be much healthier. stable player counts can be studied by how,when, and what players play. 

## Project Output
Exploratory Data Analysis (EDA) with Summary Of Analysis:

| # | Question | Variables |
|---|---|---|
| 1 | Does playtime differ by engagement? | PlayTimeHours | 
| 2 | What do players play? | GameGenre, EngagementLevel |
| 3 | When/how often do players play? | SessionsPerWeek, AvgSessionDuration |
| 4 | Does progression drive engagement? | PlayerLevel, AchievementsUnlocked | 

The Main Problem Statement on SMART framework


## Data
- Source: Kaggle — Online Gaming Behavior Dataset
- Rows: 40,034
- Columns: 13
- Missing values: None
- Duplicates: None
- Key columns: PlayerID, Age, Gender, Location, GameGenre, GameDifficulty, SessionsPerWeek, AvgSessionDurationMinutes, PlayTimeHours, InGamePurchases, EngagementLevel

## Method
This project uses statistical analysis and EDA methods:

| # | Method | Why this method |
|---|---|---|
| 1 | Two-Sample T-Test | Comparing means of a numeric variable between 2 groups |
| 2 |  Chi-Square Test | Both variables are categorical (labels, not numbers) |
| 3 |  Measures of Dispersion | Understand spread/consistency of behavior, not just the average |
| 4 | Spearman Correlation | One variable is ordinal; checking if two variables move together |


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