# Data-Analysis-of-Yandex_music
Yandex Music User Activity Analysis
This repository contains the analysis of user activity on the Yandex Music streaming platform. The project examines user behavior across two major cities, Moscow and Saint-Petersburg, and provides insights into genre preferences, temporal listening patterns, and overall engagement levels. The analysis leverages a dataset of over 65,000 records, exploring trends in music streaming behavior to identify actionable insights.

Dataset Description
The dataset consists of the following columns:

userID: Unique identifier for each user.
Track: Name of the track being played (contains some missing values).
artist: Name of the artist (contains some missing values).
genre: Genre of the track (contains some missing values).
City: City of the user, either "Moscow" or "Saint-Petersburg."
time: Timestamp indicating when the track was played.
Day: Day of the week corresponding to the timestamp.
Key Analysis Objectives
Understand User Engagement: Identify the most active users and compare activity levels between Moscow and Saint-Petersburg.
Analyze Genre Preferences: Explore the most popular genres in each city and identify unique listening patterns.
Study Temporal Trends: Examine listening activity by time of day and day of the week to identify peak hours and trends.
Generate Data Visualizations: Create insightful visualizations, including bar charts, pie charts, and heatmaps, to communicate findings effectively.
Key Findings
User Activity: Moscow users demonstrate higher engagement levels, with the top user playing 70 tracks compared to 50 tracks in Saint-Petersburg.
Genre Preferences: Rock and pop dominate in both cities, but Saint-Petersburg shows a greater affinity for folk and electronic genres, while Moscow exhibits strong interest in dance music.
Time-Based Patterns: Morning (8:00–9:00) and evening (20:00–21:00) are the most active hours. Activity peaks on Fridays, likely reflecting pre-weekend listening habits.
Visualizations
This repository includes:

Pie Charts: Displaying the most popular genres and songs in both cities.
Bar Charts: Highlighting the most active users.
Heatmaps: Showing the relationship between activity, time of day, and genres.
Technologies Used
Python: For data analysis and preprocessing.
Pandas: For data manipulation and cleaning.
Matplotlib & Seaborn: For static visualizations.
Plotly: For interactive charts and dashboards.
