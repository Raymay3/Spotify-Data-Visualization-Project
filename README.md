# Spotify Data Visualization Dashboard (2026)

## Project Overview

This project explores the relationship between Spotify track popularity and several audio features using interactive data visualizations. The goal is to investigate whether characteristics such as **energy**, **danceability**, **valence**, and **tempo** are associated with higher or lower song popularity.

The project was developed as part of **SIADS 521: Visual Exploration of Data** at the University of Michigan School of Information.

---

## Repository Contents

| File                                                      | Description                                                                                 |
| --------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| Spotify Analysis & Dashboard.ipynb                        | Main project notebook containing all visualizations and dashboard code                      |
| Spotify dataset.csv                                       | Dataset used for analysis                                                                   |
| README.md                                                 | Project documentation, screenshots, and project overview                                    |
| Dashboard - Energy.png                                    | Dashboard screenshot showing the Energy analysis view                                       |
| Dashboard - Danceability.png                              | Dashboard screenshot showing the Danceability analysis view                                 |
| Dashboard - Valence.png                                   | Dashboard screenshot showing the Valence analysis view                                      |
| Dashboard - Tempo.png                                     | Dashboard screenshot showing the Tempo analysis view                                        |
| Interactive Scatter Plot - Energy vs Popularity.png       | Interactive scatter plot demonstrating the relationship between Energy and popularity       |
| Interactive Scatter Plot - Danceability vs Popularity.png | Interactive scatter plot demonstrating the relationship between Danceability and popularity |
| Interactive Scatter Plot - Valence vs Popularity.png      | Interactive scatter plot demonstrating the relationship between Valence and popularity      |
| Interactive Scatter Plot - Tempo vs Popularity.png        | Interactive scatter plot demonstrating the relationship between Tempo and popularity        |
| Scatter Plot - Energy vs Popularity.png                   | Static scatter plot visualization                                                           |
| Histogram - Distribution of Popularity.png                | Histogram showing the distribution of popularity scores                                     |
| Bar Chart - Average Popularity by Genre.png               | Bar chart comparing average popularity across genres                                        |
| Violin Plot - Popularity Distribution by Genre.png        | Violin plot showing popularity distributions across genres                                  |

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

![Scatter Plot - Energy vs Popularity](Images/Scatter%20Plot%20-%20Energy%20vs%20Popularity.png)

---

## Interactive Scatter Plot

To improve exploration of the data, an interactive scatter plot was created using Plotly. A dropdown menu allows users to switch between Energy, Danceability, Valence, and Tempo while maintaining popularity on the y-axis.

This interactive feature allows users to compare multiple audio characteristics without creating separate visualizations for each feature.

### Energy

![Interactive Energy](Images/Interactive%20Scatter%20Plot%20-%20Energy%20vs%20Popularity.png)

### Danceability

![Interactive Danceability](Images/Interactive%20Scatter%20Plot%20-%20Danceability%20vs%20Popularity.png)

### Valence

![Interactive Valence](Images/Interactive%20Scatter%20Plot%20-%20Valence%20vs%20Popularity.png)

### Tempo

![Interactive Tempo](Images/Interactive%20Scatter%20Plot%20-%20Tempo%20vs%20Popularity.png)

---

### 2. Histogram

Displays the distribution of the selected audio feature.

**Purpose:**

* Understand how songs are distributed across feature values
* Identify skewness and concentration of observations

![Histogram](Images/Histogram%20-%20Distribution%20of%20Popularity.png)

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

![Bar Chart](Images/Bar%20Chart%20-%20Average%20Popularity%20by%20Genre.png)

---

### 4. Violin Plot

Displays the distribution of popularity within each feature level.

**Purpose:**

* Examine variability in popularity
* Compare distributions across groups
* Visualize density and spread simultaneously

![Violin Plot](Images/Violin%20Plot%20-%20Popularity%20Distribution%20by%20Genre.png)

---

## Interactive Dashboard & Findings

**Note:** GitHub does not reliably render all Jupyter Notebook outputs, particularly Plotly visualizations and other interactive content. For this reason, a runnable Google Colab version, a video demonstration, and dashboard screenshots have been provided below.

The dashboard allows users to explore the relationship between Spotify popularity and four audio features:

* Energy
* Danceability
* Valence
* Tempo

Using the dropdown menu, users can switch between features and instantly update:

* Scatter plots
* Histograms
* Bar charts
* Violin plots
* Correlation values
* Feature-level descriptions

This interactivity makes it possible to compare multiple audio characteristics without navigating between separate visualizations.

### Key Findings

**Energy**
* Showed the strongest relationship among the selected features.
* Exhibited a modest negative correlation with popularity.

**Danceability**
* Showed almost no linear relationship with popularity.
* More danceable songs were not necessarily more popular.

**Valence**
* Displayed a weak negative relationship with popularity.
* Happier songs were not automatically associated with higher popularity.

**Tempo**
* Demonstrated only a very weak relationship with popularity.
* Song speed alone was not a strong predictor of success.

Overall, the analysis suggests that popularity is influenced by many factors beyond the audio features examined in this project.

### Dashboard Screenshots

The screenshots below show the dashboard after selecting each audio feature from the dropdown menu.

#### Dashboard - Energy

![Dashboard - Energy](Images/Dashboard%20-%20Energy.png)

#### Dashboard - Danceability

![Dashboard - Danceability](Images/Dashboard%20-%20Danceability.png)

#### Dashboard - Valence

![Dashboard - Valence](Images/Dashboard%20-%20Valence.png)

#### Dashboard - Tempo

![Dashboard - Tempo](Images/Dashboard%20-%20Tempo.png)

---

# Interactive Dashboard Access

## Live Dashboard (Runnable)

The full interactive dashboard can be viewed and executed in Google Colab using the link below:

https://colab.research.google.com/drive/1nk3GRhEQnwcUmiEMhArVQ5Q-g7AtoNAy?usp=sharing

The Colab notebook contains the complete dashboard with dropdown functionality that allows users to switch between Energy, Danceability, Valence, and Tempo. All visualizations update dynamically based on the selected feature.

---

## Video Demonstration

A short video walkthrough demonstrating the dashboard's functionality is available below:

https://drive.google.com/file/d/1BMhEyZ0V1sPhR3Cbn1aJqV9SmLdlIkeh/view?usp=sharing

The video demonstrates:
- Dashboard navigation
- Dropdown menu functionality
- Dynamic chart updates
- Interpretation of the visualizations

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

March 2026
