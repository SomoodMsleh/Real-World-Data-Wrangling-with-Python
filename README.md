# Real-World Data Wrangling with Python

## Project Overview
This project is part of the Udacity Data Analyst Nanodegree. The goal was to collect, assess, clean, and analyze real-world data using Python. The dataset used is from The Movie Database (TMDb), focusing on movie-related attributes such as budget, revenue, cast, crew, and genres.

## Datasets
The project utilizes the following datasets:
- **tmdb_5000_movies.csv** – Contains information about movies, including budget, revenue, runtime, genres, and release dates.
- **tmdb_5000_credits.csv** – Contains data on cast and crew members for each movie.
Dataset link form kaggle [TMDB 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?resource=download&select=tmdb_5000_movies.csv)

## Data Wrangling Process
The project follows the three-step data wrangling process:

1. **Gathering Data**
   - Loaded the TMDb datasets using Pandas.
   
2. **Assessing Data**
   - Identified data quality and tidiness issues, including missing values, incorrect data types, and structural inconsistencies.
   
3. **Cleaning Data**
   - Handled missing values by imputation or removal.
   - Converted data types for better analysis (e.g., converting `release_date` to datetime).
   - Extracted relevant data from JSON-like columns (genres, cast, and crew).
   - Merged datasets for a more comprehensive analysis.

## Key Findings
Using the cleaned dataset, the project explored:
- Trends in movie production and revenue over time.
- The impact of budget on revenue.
- The most frequently occurring actors and directors.

## Tools Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, JSON,os,requests)
- **Jupyter Notebook** for interactive analysis
- **Git & GitHub** for version control

## Installation & Usage
To run this project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/SomoodMsleh/Real-World-Data-Wrangling-with-Python.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Real-World-Data-Wrangling-with-Python
   ```
3. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Reflection
Given more time, further improvements could include:
- Handling more nuanced data quality issues (e.g., adjusting for inflation in revenue and budget comparisons).
- Expanding analysis to include more advanced statistical methods.
- Incorporating external datasets for richer insights.

## License
This project is for educational purposes under the Udacity Data Analyst Nanodegree.

---
For more details, check the full project notebook in this repository.

