# Project Overview
This project presents an Exploratory Data Analysis (EDA) of the Netflix Titles Overview dataset. The analysis focuses on understanding Netflix’s content growth over time by examining release years, content duration, and type (Movies and TV Shows).

The project was completed as part of an academic data analytics assignment and uses Python for data preprocessing, visualization, and clustering analysis.

# Dataset Description
- Dataset name: netflix_titles.csv
- Source: Kaggle
- Size: ~3.4 MB
- Rows: 8,807
- Columns: 12

# Key Attributes:
- `title`
- `type` (Movie / TV Show)
- `release_year`
- `duration`
- `country`
- `rating`
- `listed_in`
- `description`
- `date_added`
<br>Some columns such as director, cast, and country contain missing values, which were handled during the data wrangling process.

# Tools and Technologies
- Programming Language: Python
- Libraries Used:
- pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
- Environment: Jupyter Notebook

# Data Wrangling

The following preprocessing steps were applied:
- Removal of duplicate records
- Handling missing values in key columns
- Cleaning the duration column by extracting numeric values
- Converting duration into a consistent numerical format
- Dropping rows with missing release_year or duration
- Standardizing numerical features before clustering

# Exploratory Data Analysis

EDA techniques used in this project include:
- Descriptive statistics for numerical features
- Histograms to analyze release year distribution
- Count plots to compare Movies and TV Shows
- Heatmaps to identify missing values
- Scatter plots to examine relationships between release year and duration
<br>These steps helped identify content trends and Netflix’s growth pattern over time.

# Data Mining and Clustering
K-means clustering was applied using:
- Features: release_year and duration
- Number of clusters: 4
- Standardization: StandardScaler
## Cluster Interpretation:
- Cluster 0: Recent movies (2015–2021) with short to medium duration
- Cluster 1: Short-duration TV content from recent years (2015–2021)
- Cluster 2: Medium to long-duration content from 1995–2015
- Cluster 3: Older movies released before 1995
This clustering helps visualize how Netflix content varies across time and duration.

# Project Objective
The main objective of this project is to analyze **Netflix’s content growth over time** and understand how release year and duration influence content distribution using exploratory data analysis and clustering techniques.

# Disclaimer
This project was completed for educational purposes only. The dataset is publicly available on Kaggle, and all analysis is based on that data.
