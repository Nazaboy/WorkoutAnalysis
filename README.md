# Data Analysis and Visualization of Workout Trends

This project provides an in-depth analysis of global workout trends, keyword popularity, and geographical interest in various workout types. Using data visualization techniques, it uncovers insights into workout preferences over time and across regions.

## Project Structure

- **Data Loading and Cleaning**: Imports datasets, inspects structure, checks for missing values, and ensures data integrity.
- **Exploratory Data Analysis (EDA)**: Visualizes distributions, trends, and correlations in workout popularity.
- **Trend Analysis**: Examines global workout trends and geographical variations, with a focus on keyword interest (home workout, gym workout, and home gym).
- **Conclusion and Key Insights**: Summarizes findings on workout trends and highlights future optimization ideas.

## Features

1. **Data Preprocessing**:
   - Loads datasets and inspects structure.
   - Cleans data by handling missing values and removing duplicates.
   - Converts date columns to datetime format for time series analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Visualizes data distributions for workout trends globally and by keyword.
   - Shows workout interest over time and explores correlations between workout types.

3. **Trend Analysis**:
   - Identifies peak interest times and examines workout trends before, during, and after COVID-19.
   - Analyzes geographical interest in workouts, highlighting regions with high engagement.

## Dataset Requirements

- `workout.csv`: Contains monthly global workout popularity data.
- `three_keywords.csv`: Tracks monthly global interest in specific keywords.
- `workout_geo.csv`: Shows workout interest across different countries.
- `three_keywords_geo.csv`: Details country-level interest in specific workout keywords.

## Requirements

Ensure you have the following libraries installed:

```bash
pip install pandas matplotlib seaborn
