# Movie Correlation Analysis

# Project Overview

This project explores the relationships (correlations) between various movie attributes such as budget, revenue, rating, and genre. The goal is to identify which factors contribute most to a movie’s success using Python data analysis techniques.

By leveraging pandas, seaborn, and matplotlib, we analyze trends and visualize insights from a dataset containing movie metadata.

# Dataset Description

The dataset (movies.csv) contains the following columns:

Title: Name of the movie

Year: Year of release

Genre: Movie genre (e.g., Action, Drama)

Budget: Production budget (in dollars)

Revenue: Box office earnings (in dollars)

Rating: IMDb rating

Votes: Number of user votes

Runtime: Duration of the movie (in minutes)

# Key Steps in Analysis

1️⃣ Data Cleaning & Preprocessing

Handled missing values: Missing budgets were filled using a median value based on year and genre.

Converted data types: Ensured numerical values were formatted correctly for analysis.

Checked for outliers: Identified extreme values in budget and revenue that could impact correlation results.

2️⃣ Exploratory Data Analysis (EDA)

Visualized distributions of key attributes like budget and revenue.

Generated correlation heatmaps to identify strong relationships between numerical features.

Boxplots & scatterplots were used to further analyze trends and patterns.

3️⃣ Correlation Analysis

Used Pearson correlation coefficient to measure relationships between movie attributes.

Key insights:

Higher budgets tend to result in higher revenue.

Higher IMDb ratings do not always correlate with revenue.

Genres play a significant role in financial success.

# Results & Findings

Movies with bigger budgets generally have higher revenues, but the correlation is not perfect due to marketing and audience reception factors.

IMDb ratings and revenue have a weak correlation, suggesting that well-rated movies don’t always earn more at the box office.

Certain genres (e.g., Action, Adventure) tend to have higher budgets and revenues compared to others (e.g., Drama, Horror).
