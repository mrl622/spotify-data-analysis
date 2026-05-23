# 🎵 Spotify Data Analysis Project

> Analyzed 114,000+ Spotify tracks to uncover genre trends, audio feature patterns, and popularity insights using Python, SQL, and Power BI.

---

## 📌 Project Overview

This end-to-end data analyst project explores the Spotify Tracks Dataset from Kaggle.
The goal was to clean, analyze, and visualize music data to find meaningful patterns
in how genres, audio features, and explicit content relate to track popularity.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas) | Data cleaning & manipulation |
| Matplotlib & Seaborn | Exploratory Data Analysis (EDA) |
| SQL (pandasql) | Data querying & aggregation |
| Power BI | Interactive dashboard & insights |

---

## 📂 Project Structure

```
spotify-data-analysis/
│
├── dataset.csv                 ← Raw Spotify dataset (114K tracks)
├── spotify_eda.ipynb           ← Python EDA notebook
├── Spotify_Analysis.pbix       ← Power BI dashboard file
├── dashboard.png               ← Dashboard screenshot
├── insights.png                ← Insights page screenshot
└── README.md                   ← Project documentation
```

---

## 📊 Dataset

- **Source:** Kaggle — Spotify Tracks Dataset
- **Size:** 114,000+ tracks
- **Features:** track_name, artists, popularity, danceability, energy,
  valence, tempo, loudness, acousticness, instrumentalness, track_genre

---

## 🔍 Steps Performed

### 1. Data Cleaning (Python)
- Removed 3 null rows
- Dropped duplicate tracks
- Converted duration from ms to minutes

### 2. Exploratory Data Analysis (Python)
- Descriptive statistics for all audio features
- Top 10 genres by average popularity
- Correlation heatmap of audio features
- Popularity distribution histogram

### 3. SQL Analysis (pandasql)
- Top 10 most popular tracks
- Average audio features by genre
- Explicit vs non-explicit comparison
- High energy + high popularity filter

### 4. Power BI Dashboard
- KPI Cards: Avg Valence, Danceability, Liveness, Energy
- Area chart: Popularity by Danceability
- Donut chart: Energy distribution
- Bar chart: Avg Popularity by Genre
- Slicers: Genre & Artist filters
- Insights page: 7 key findings

---

## 💡 Key Insights

1. 🎵 Pop-film & K-Pop are the most popular genres (avg popularity > 55/100)
2. 🎵 Genres like black-metal & grunge score below 30 in avg popularity
3. ⚡ High energy tracks (>0.8) tend to have higher danceability scores
4. 💃 Average danceability across all genres is 0.57
5. 🎸 Acoustic songs have LOW energy (avg 0.30) but high valence (positivity)
6. 🔞 Explicit tracks have higher avg popularity than non-explicit tracks
7. ✅ 80%+ of tracks in the dataset are non-explicit (family friendly)

---

## 📈 Dashboard Preview

![Dashboard](dashboard.png)
![Insights](insights.png)

---

## 🚀 How to Run

1. Clone this repository
2. Open `spotify_eda.ipynb` in Jupyter Notebook
3. Run all cells in order
4. Open `Spotify_Analysis.pbix` in Power BI Desktop

---

## 👤 Author

Dhamodharan
- LinkedIn: linkedin.com/in/dhamodharam06
- GitHub: github.com/mrl622
