# 🎵 Spotify Wrapped Trend Analysis

> A collaborative data science project exploring the audio characteristics associated with mainstream music popularity using Spotify Wrapped, Billboard Hot 100, and TikTok datasets.

---

## Overview

Every year, Spotify releases **Spotify Wrapped**, showcasing users' most-streamed songs regardless of when they were originally released. This project investigates whether a song's **danceability**, **energy**, and **valence** are consistent indicators of popularity and whether these characteristics can help explain why older songs experience a resurgence ("comebacks") alongside newly released tracks.

Using exploratory data analysis and non-parametric statistical testing, we compared songs from the **2025 Spotify Wrapped Top Songs**, **Billboard Hot 100**, and **TikTok Trending Songs** datasets to better understand the characteristics shared by popular music.

---

## Research Question

**Do songs featured in the 2025 Spotify Wrapped Top Songs list share statistically significant similarities in danceability, energy, and valence across different release years, and do these characteristics help explain long-term popularity and musical comebacks?**

Additionally, we investigated whether Billboard chart performance and TikTok virality act as confounding factors influencing Spotify Wrapped popularity.

---

## Why This Matters

Streaming platforms have transformed how music becomes popular. While new releases dominate charts, older songs frequently return to mainstream attention through social media trends, viral content, and cultural events.

Understanding whether popular songs share common audio characteristics may help explain how songs achieve long-term popularity and re-emerge years after their release.

---

## Datasets

| Dataset | Purpose |
|---------|----------|
| Spotify Wrapped Top Songs (2025) | Primary analysis |
| Billboard Hot 100 | Compare charting songs |
| TikTok Trending Songs (2020–2022) | Evaluate social media influence |

---

## Methodology

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Pairwise Comparisons
- Mann–Whitney U Tests
- Kruskal–Wallis Tests
- Cohort Analysis by Release Era

---

## Results

### Billboard vs Spotify Wrapped

- No statistically significant differences in danceability, energy, or valence.
- Billboard songs exhibited nearly identical audio characteristics.
- Suggests Billboard chart performance may be an important confounding factor.

### TikTok vs Spotify Wrapped

- Danceability significantly differed *(p = 0.047)*.
- Valence significantly differed *(p < 0.001)*.
- Energy showed no statistically significant difference.

### Release Year Analysis

Songs released before 2022, during 2022–2023, and in 2024 showed no statistically significant differences in danceability, energy, or valence.

These findings suggest that songs sharing similar audio characteristics remain competitive regardless of release year, supporting the possibility of musical comebacks.

---

## Key Visualizations

- Correlation Heatmaps
- Pairwise Feature Analysis
- Statistical Comparison Tables

---

## Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook
- Git

---

## Team

Collaborative project completed for:

**COGS 108 — Data Science in Practice**

University of California, San Diego

Spring 2026
