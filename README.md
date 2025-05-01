## Video Game Sales Analysis and Insights (EDA)

# Project Overview
Welcome to my Video Game Sales Analysis project! This project dives into exploratory data analysis (EDA) to uncover trends, patterns, and actionable insights from a dataset of 16,598 video games, covering sales, genres, platforms, publishers, and regional preferences. The goal is to answer key questions about game development strategies, such as what types of games to create, how regional preferences impact sales, and what drives global success. This repository contains the code, visualizations, and findings presented by me, Erfan Ebrahimi, and my collaborator, Sadegh Mosazade.
Motivation
As a data enthusiast and gaming lover, I wanted to explore how data can guide game development decisions. By analyzing sales trends and player behavior, this project aims to provide practical recommendations for developers and publishers to optimize game design, target specific markets, and time releases effectively.
Dataset
The dataset, sourced from vgsales.csv, includes:

16,598 games spanning multiple genres, platforms, and publishers.
Sales data across regions: North America (NA), Europe (EU), Japan (JP), and Other regions, plus global sales.
Key attributes: Game name, platform, release year, genre, publisher, and sales figures (in millions).

Key Questions
This project addresses three main questions:

What should we create? Identifying high-demand genres and platforms.
How do regional preferences influence sales? Understanding genre and platform preferences in NA, EU, and JP.
What strategies drive global success? Analyzing trends, market saturation, and release timing.

Methodology
Data Cleaning

Removed games with release years after 2015 to focus on relevant trends.
Handled missing values:
Dropped rows with missing Year values (271 instances).
Filled missing Publisher values with "Unknown Publisher" (56 instances).


Verified data integrity with statistical summaries and null checks.

Exploratory Data Analysis

Tools: Python, Pandas, Matplotlib, Seaborn.
Techniques:
Aggregated data by genre, platform, and region to analyze sales distributions.
Visualized trends using bar plots, pair plots, and time-series charts.
Identified top publishers (e.g., Nintendo) and platforms (e.g., PlayStation, Nintendo).
Examined regional sales: North America leads with 49.3% of global sales.
Analyzed genre preferences: Action and Sports dominate globally, while Role-Playing is strong in Japan.



Key Findings

Genre Popularity: Action (3,133 games), Sports (2,266), and Misc (1,692) are the most produced genres.
Regional Insights:
North America and Europe favor Sports and Action games.
Japan has a strong preference for Role-Playing games.


Platform Strategy: Nintendo and PlayStation platforms consistently drive high sales.
Market Trends: Sales peaked around 2006-2010, with saturation points indicating optimal release windows.
Publisher Impact: Established brands like Nintendo leverage strong franchises for significant market share.

Recommendations
Based on the analysis, I recommend the following for game developers:

Genre Focus: Prioritize Action, Sports, and Role-Playing genres for broad appeal, while exploring niche markets like Puzzle or Strategy.
Platform Strategy: Optimize games for leading platforms like Nintendo and PlayStation.
Regional Customization: Tailor game themes and mechanics to regional preferences (e.g., Role-Playing for Japan, Sports for NA/EU).
Release Timing: Target launch windows with lower market saturation to maximize visibility and sales.

Repository Structure

vgsales.csv: The raw dataset used for analysis.
project.ipynb: Jupyter Notebook containing the full EDA code, including data cleaning, visualizations, and analysis.
trivia_night.pdf: Presentation slides summarizing the project, key findings, and recommendations.
README.md: This file, providing an overview of the project.

How to Run

Prerequisites:
Python 3.x
Libraries: pandas, matplotlib, seaborn, numpy, scipy


Steps:
Clone this repository: git clone https://github.com/Sadegh-MousaZade/video-game-sales-analysis.git
Install dependencies: pip install -r requirements.txt
Open project.ipynb in Jupyter Notebook and run the cells to reproduce the analysis.


Dataset: Ensure vgsales.csv is in the same directory as the notebook.

Visualizations
The notebook includes visualizations such as:

Pair plots showing relationships between sales, genres, and regions.
Bar charts of top platforms and publishers by global sales.
Time-series plots of global sales trends over the years.
Regional sales distributions highlighting market dominance.

Check out the Doc.pdf for a visual summary of these insights!
Future Work

Predictive Modeling: Build machine learning models to forecast game sales based on genre, platform, and release year.
Deeper Regional Analysis: Explore cultural factors influencing genre preferences.
Extended Dataset: Incorporate newer data (post-2015) to analyze recent trends.

Contact
Feel free to reach out for questions or collaboration:

GitHub: Sadegh-MousaZade

If you find this project useful, please give it a ⭐ on GitHub!
