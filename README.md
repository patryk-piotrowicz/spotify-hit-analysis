# Project Title: Spotify Hit Song Analysis

A data analysis project exploring the characteristics associated with successful songs on streaming platforms. Using a Spotify dataset, this analysis investigates how musical features and audience engagement metrics relate to streaming performance.

---

## Table of Contents

- [Overview](#overview)  
- [Dataset](#dataset)  
- [Technologies Used](#technologies-used)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Analysis & Visualizations](#analysis--visualizations)  
- [Conclusion](#conclusion)  
- [Credits](#credits)  
- [License](#license)  

---

## Overview

### Motivation
Understanding what makes a song successful on streaming platforms is valuable for record labels, artists, and marketing teams.

### Objective
This project explores the question:

**What characteristics are associated with songs that achieve high streaming performance?**

The analysis investigates relationships between audio features such as danceability, energy, and instrumentalness, as well as audience engagement metrics like likes and views.

### Learning Outcomes

Through this project I learned:

- How to perform exploratory data analysis using Python
- How to analyze relationships between variables using correlation analysis
- How to create data visualizations to communicate insights
- How to structure a complete data analysis project

---

## Dataset

Dataset source:

https://www.gigasheet.com/sample-data/spotify-dataset

Dataset details:

- ~20,000 songs
- Audio features and engagement metrics
- Includes streaming counts and listener interaction

Key variables analyzed:

- Streams
- Views
- Likes
- Comments
- Danceability
- Energy
- Loudness
- Acousticness
- Instrumentalness
- Tempo
- Valence

Cleaning steps included:

- Checking for missing values
- Inspecting dataset structure
- Verifying data types
- Reviewing summary statistics

---

<h2>Technologies Used</h2>

<ul>
  <li><strong>Languages & Libraries:</strong> Python, Pandas, NumPy, Matplotlib, Seaborn</li>
  <li><strong>Tools:</strong> Jupyter Notebook, Git, GitHub</li>
</ul>

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white">
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge">
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge">
</p>

---

## Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/spotify-hit-analysis.git

cd spotify-hit-analysis

pip install -r requirements.txt

jupyter notebook


```

## Usage

Instructions for using the project:

1. Open the main notebook (`spotify_hit_analysis-2.ipynb`)  
2. Run each cell sequentially to reproduce the analysis  

The notebook contains all data exploration, visualizations, and insights.

---

## Analysis & Visualizations

Key findings from the analysis include:
- Streaming success is highly concentrated among a small number of songs.
- Engagement metrics such as likes, views, and comments strongly correlate with streaming performance.
- Hit songs tend to have lower instrumentalness, suggesting that vocal-driven songs dominate popular streaming content.
- Slight differences in danceability and loudness were observed between hit and non-hit songs.
- Several visualizations were created to explore these patterns, including:
- Stream distribution histograms
- Boxplots comparing hit vs non-hit songs
- Scatter plots showing the relationship between likes and streams
- Correlation analysis

---

## Conclusion

This project demonstrates how exploratory data analysis can reveal patterns in streaming music performance.

While some musical attributes show small differences between hit and non-hit songs, audience engagement metrics appear to play a much larger role in streaming success.

Future work could incorporate additional variables such as artist popularity, playlist placement, and marketing activity. 

---

## Credits

Dataset Source:
https://www.gigasheet.com/sample-data/spotify-dataset

---

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/)

---

<p align="center"><strong>Thanks for visiting! 🚀</strong></p>
