# Spotify Data Visualization Dashboard (2025)

## Project Overview

This project explores the relationship between Spotify track popularity and several audio features using interactive data visualizations. The goal is to investigate whether characteristics such as **energy**, **danceability**, **valence**, and **tempo** are associated with higher or lower song popularity.

The project was developed as part of **SIADS 521: Visual Exploration of Data** at the University of Michigan School of Information.

---

## Research Question

**How do audio features influence Spotify track popularity?**

Specifically, this dashboard examines:

* Energy vs. Popularity
* Danceability vs. Popularity
* Valence vs. Popularity
* Tempo vs. Popularity

By allowing users to dynamically switch between features, the dashboard provides multiple perspectives on the relationship between audio characteristics and popularity scores.

---

## Dataset

The dataset contains Spotify track information, including:

* Track name
* Artist
* Popularity score
* Danceability
* Energy
* Valence
* Tempo
* Genre

For clarity and visualization purposes, the analysis focuses on the top 10 most common genres in the dataset.

---

## Visualization Techniques

The dashboard combines four visualization types:

### 1. Scatter Plot

Displays the relationship between a selected audio feature and popularity.

**Purpose:**

* Identify trends and correlations
* Detect clusters and outliers
* Compare feature values against popularity

---

### 2. Histogram

Displays the distribution of the selected audio feature.

**Purpose:**

* Understand how songs are distributed across feature values
* Identify skewness and concentration of observations

---

### 3. Bar Chart

Displays average popularity across feature levels:

* Very Low
* Low
* Medium
* High
* Very High

**Purpose:**

* Compare average popularity among groups
* Highlight whether higher or lower feature values tend to be associated with popularity

---

### 4. Violin Plot

Displays the distribution of popularity within each feature level.

**Purpose:**

* Examine variability in popularity
* Compare distributions across groups
* Visualize density and spread simultaneously

---

## Interactive Features

The dashboard includes a dropdown menu that allows users to switch between:

* Energy
* Danceability
* Valence
* Tempo

When a feature is selected:

* All four visualizations update automatically
* Titles update dynamically
* Correlation values update dynamically
* Feature level descriptions update dynamically

This allows users to explore multiple audio characteristics without leaving the dashboard.

---

## Key Findings

### Energy

Energy exhibited the strongest relationship among the selected features, showing a modest negative correlation with popularity.

### Danceability

Danceability showed almost no linear relationship with popularity, suggesting that highly danceable songs are not necessarily more popular.

### Valence

Valence demonstrated a weak negative relationship with popularity, indicating that happier songs are not automatically associated with higher popularity scores.

### Tempo

Tempo showed only a very weak relationship with popularity, suggesting that song speed alone is not a strong predictor of success.

Overall, the analysis suggests that popularity is influenced by many factors beyond the audio features examined here.

---

## Repository Contents

* `Spotify Analysis & Dashboard.ipynb` — Main project notebook
* `Spotify dataset.csv` — Dataset used for analysis
* Dashboard screenshots
* Video demonstration

---

## Dashboard Screenshots

GitHub does not reliably render complex Plotly dashboards with dropdown interactivity. To ensure the dashboard can be viewed directly within the repository, screenshots of each dashboard state have been included.

### Energy Dashboard

![Dashboard - Energy](Dashboard_-_Energy.png)

### Danceability Dashboard

(Add image here)

### Valence Dashboard

(Add image here)

### Tempo Dashboard

(Add image here)

---

## Video Demonstration

A short video walkthrough of the dashboard is available here:

[https://drive.google.com/file/d/1BMhEyZ0V1sPhR3Cbn1aJqV9SmLdlIkeh/view?usp=sharing]

---

## Technologies Used

* Python
* Pandas
* Plotly
* Jupyter Notebook
* VS Code

---

## Author

**Gabriella Gass**

Master of Applied Data Science (MADS)
University of Michigan School of Information

2025
