# Netflix Movies — EDA Project

## About This Project
Exploratory Data Analysis on a Netflix-related movies dataset
of 9,800+ titles using Python. Goal was to understand content
trends, genre popularity, and voting patterns.

## Objective
To uncover patterns in movie popularity, genres, and release
trends to support data-driven content decisions.

## Tools Used
- Python
- Pandas — data cleaning and manipulation
- NumPy — numerical operations
- Matplotlib — visualizations
- Seaborn — statistical visualizations
- Jupyter Notebook

## Dataset
- Source — Kaggle (TMDB Netflix Movies Dataset)
- Rows — 9,827 titles
- Columns — Release_Date, Title, Popularity, Vote_Count,
  Vote_Average, Genre, Overview, Original_Language, Poster_Url

## Data Cleaning & Feature Engineering
- Converted Release_Date from string to datetime,
  extracted year
- Dropped unnecessary columns — Overview,
  Original_Language, Poster_Url
- Categorized Vote_Average into 4 groups using pd.cut()
  → not_popular, below_avg, average, popular
- Removed null values using dropna()
- Checked and confirmed 0 duplicate records

## Key Findings
-  Action and Drama are the most popular genres
-  Majority of titles fall in average or below_avg
  rating category
-  Popularity scores vary widely — few titles
  dominate with very high scores
-  Most content released between 2018 to 2022

## Project Structure
netflix analysis.ipynb — Complete EDA notebook with
cleaning, feature engineering and visualizations

## How To Run
1. Clone this repo
2. Install libraries
   pip install pandas numpy matplotlib seaborn
3. Open netflix analysis.ipynb in Jupyter Notebook
4. Run all cells

## Author
Mahek Jamadar
LinkedIn — www.linkedin.com/in/mahek-jamadar-
GitHub — github.com/Mahekjamadar20
4. Run all cells

## Author
Mahek Jamadar
LinkedIn — www.linkedin.com/in/mahek-jamadar-
GitHub — github.com/Mahekjamadar20
