🎵 Spotify Data Analysis Project
Analyzed 114,000+ Spotify tracks to uncover genre trends, audio feature patterns, and popularity insights using Python, SQL, and Power BI.
📌 Project Overview
This end-to-end data analyst project explores the Spotify Tracks Dataset from Kaggle.
The goal was to clean, analyze, and visualize music data to find meaningful patterns
in how genres, audio features, and explicit content relate to track popularity.
🛠️ Tools & Technologies
Tool
Purpose
Python (Pandas)
Data cleaning & manipulation
Matplotlib & Seaborn
Exploratory Data Analysis (EDA)
SQL (pandasql)
Data querying & aggregation
Power BI
Interactive dashboard & insights
📂 Project Structure
Code
📊 Dataset
Source: Kaggle — Spotify Tracks Dataset
Size: 114,000+ tracks
Features: track_name, artists, popularity, danceability, energy,
valence, tempo, loudness, acousticness, instrumentalness, track_genre
🔍 Steps Performed
1. Data Cleaning (Python)
Removed 3 null rows
Dropped duplicate tracks
Converted duration from ms to minutes
2. Exploratory Data Analysis (Python)
Descriptive statistics for all audio features
Top 10 genres by average popularity
Correlation heatmap of audio features
Popularity distribution histogram
3. SQL Analysis (pandasql)
Top 10 most popular tracks
Average audio features by genre
Explicit vs non-explicit comparison
High energy + high popularity filter
4. Power BI Dashboard
KPI Cards: Avg Valence, Danceability, Liveness, Energy
Area chart: Popularity by Danceability
Donut chart: Energy distribution
Bar chart: Avg Popularity by Genre
Slicers: Genre & Artist filters
Insights page: 7 key findings
💡 Key Insights
🎵 Pop-film & K-Pop are the most popular genres (avg popularity > 55/100)
🎵 Genres like black-metal & grunge score below 30 in avg popularity
⚡ High energy tracks (>0.8) tend to have higher danceability scores
💃 Average danceability across all genres is 0.57
🎸 Acoustic songs have LOW energy (avg 0.30) but high valence (positivity)
🔞 Explicit tracks have higher avg popularity than non-explicit tracks
✅ 80%+ of tracks in the dataset are non-explicit (family friendly)
