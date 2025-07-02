# 🎵 Spotify Music Data Analysis

This project explores Spotify music data across **tracks** and **artists** to uncover insights into popularity trends, genre evolution, audio feature correlations, and anomalies using Python and data visualization techniques.

---

## 📌 Project Overview

This analysis answers key questions like:
- Who are the most followed and most popular artists?
- How do **explicit tracks** compare with **clean tracks** in energy and popularity?
- How have audio features like **danceability** and **energy** changed over time?
- What is the relationship between **popularity** and Spotify's audio features?
- Are there outliers or standout tracks/artists based on popularity or energy?

---

## 🧪 Exploratory Data Analysis

### ✅ Data Cleaning & Preparation
- Handled missing and invalid values (`release_date`, `name`, etc.)
- Extracted release year and normalized date formats
- Converted list-like string fields (e.g., `artists`, `genres`) using `eval`
- Added new columns like `explicit_label`, `main_artist`, and `popularity_level`

### 📈 Analyses Performed
1. **Artist Popularity Trends**
   - Top 10 most followed vs. most popular artists
   - Correlation between followers and popularity

2. **Track Insights**
   - Comparison of **explicit vs. clean tracks** in terms of popularity and energy
   - Boxplots and distribution analysis

3. **Genre & Era Evolution**
   - Trends in **energy** and **danceability** over time (since 1920s)
   - Correlation of audio features across decades

4. **Audio Feature Correlation**
   - Pairwise correlation between **popularity**, **energy**, **acousticness**, **loudness**, etc.

5. **Outlier Detection**
   - Identified outliers using statistical methods and visualized them using boxplots
   - Highlighted extreme popularity tracks and energy spikes

---

## 📊 Visualizations

- `matplotlib` & `seaborn` plots for:
  - Distribution of popularity
  - Boxplots for outlier detection
  - Barplots for top artists
  - Line plots for time-based trends
  - Heatmaps for audio feature correlation

---

## 📦 Tech Stack

- **Language**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn, scipy
- **Tools**: Jupyter Notebook, Google Colab, Kaggle

---

## 📁 Dataset Source

- Spotify Artist and Track Dataset from **Kaggle**
  > Contains: `artists.csv`, `tracks.csv` with audio features and metadata

---

## 📌 Summary

This project provided valuable insights into how music features correlate with popularity, how music evolved across eras, and how genres and artist trends differ. It involved **cleaning, visualizing, analyzing, and deriving meaning** from a rich music dataset using end-to-end data analytics skills.

---

## 🚀 Future Work

- Build a recommendation system using audio features
- Apply clustering on tracks by mood

---
