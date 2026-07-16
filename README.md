# Spotify Wrapped Trend Analysis

## Overview
A collaborative data science project analyzing the musical features that predict 
a song's appearance on the 2025 Spotify Wrapped Top Songs list. We investigated 
whether danceability, energy, and valence, and confounding platforms like TikTok 
and Billboard Hot 100, could explain what makes a song go (or stay) popular.

## Research Question
Can audio features like danceability, energy, and valence predict which songs make 
Spotify Wrapped, and can they identify songs likely to make a "comeback"?

## Datasets
- 2025 Spotify Wrapped Top Songs
- TikTok Viral Trends (2020–2022)
- Billboard Hot 100 (2002–2023)

## Key Findings
- **Danceability** (0.60–0.85) was the strongest predictor of Spotify Wrapped 
  placement — top 5 songs scored even more narrowly between 0.65–0.85
- Audio features showed **no significant difference across release decades**, 
  meaning a 2015 song sounds just as Wrapped-worthy as a 2024 release
- **TikTok** was confirmed as a confounding variable for danceability and valence, 
  but not energy
- **Billboard Hot 100** shared nearly identical average scores across all three 
  variables, confirming why charting songs tend to sound similar
- Energy was surprisingly the most **consistent** variable across all datasets, 
  contradicting our original hypothesis that valence would be most stable

## Tools & Methods
- Python, pandas, numpy, matplotlib, seaborn
- Mann-Whitney U Test for statistical validation
- Cohort analysis by release date (pre-2022, 2022–2023, 2024+)

## Team
Collaborative project — UC San Diego COGS 108, Spring 2026
