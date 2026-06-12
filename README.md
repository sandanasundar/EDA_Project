# Netflix Titles Exploratory Data Analysis (EDA)

## Overview

This project focuses on performing Exploratory Data Analysis (EDA) on Netflix Movies and TV Shows datasets to uncover patterns, trends, and relationships within the data.

The analysis includes data cleaning, statistical summaries, visualizations, genre analysis, rating analysis, runtime analysis, and correlation analysis to derive meaningful insights from the dataset.

## Dataset Used

* **raw_titles.csv** – Contains information about movies and TV shows.
* **raw_credits.csv** – Contains cast and crew details associated with the titles.

## Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab / Jupyter Notebook

## Tasks Performed

### Data Exploration

* Loaded and inspected datasets
* Examined dataset structure and data types
* Generated statistical summaries

### Data Cleaning

* Checked for missing values
* Removed duplicate records
* Handled null values where necessary

### Data Visualization

* Content type distribution analysis
* Genre distribution analysis
* Release year trend analysis
* IMDb rating distribution
* Runtime analysis using boxplots
* Correlation heatmap
* Popularity vs rating analysis

### Cast Analysis

* Identified most frequently appearing actors
* Explored contributor patterns across titles

### Correlation Analysis

* Examined relationships between:

  * IMDb Score
  * IMDb Votes
  * Runtime
  * Release Year

## Key Findings

* Movies account for the majority of content in the dataset.
* Drama and Comedy are the most common genres.
* Content production increased significantly after 2010.
* Most titles received IMDb ratings between 6 and 8.
* Titles with higher IMDb votes generally tend to have better ratings.
* A small number of actors appear frequently across multiple productions.
* Audience engagement shows a positive relationship with content ratings.


## Conclusion

This project successfully applied Exploratory Data Analysis techniques to understand content trends, audience preferences, and relationships between key variables. The insights obtained can support data-driven decision-making and provide a better understanding of content characteristics within the entertainment industry.
