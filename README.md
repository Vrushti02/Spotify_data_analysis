
# Spotify Data Analysis

This Jupyter Notebook (Spotify_analysis.ipynb) contains an analysis of Spotify's track data and genre information. The primary objective of this analysis is to explore and gain insights into the characteristics of Spotify tracks, their popularity, and the distribution of songs across different genres. We also aim to understand the correlation between various audio features of the tracks and how they relate to popularity.

## Data Sources

1. **tracks.csv**: This dataset contains information about individual tracks, including audio features such as loudness, energy, acousticness, and popularity.

2. **SpotifyFeatures.csv**: This dataset provides additional information, including genre data, for Spotify tracks.

## Analysis Steps

1. **Data Preprocessing**: We start by loading the required datasets and performing some initial data exploration to check for missing values and basic statistics of the tracks.

2. **Top 10 Most Popular Tracks**: We identify and display the top 10 tracks based on their popularity score.

3. **Correlation Analysis**: We analyze the correlation between different audio features of the tracks using a heatmap, providing insights into the relationships between these features.

4. **Loudness vs. Energy Correlation**: We visualize the correlation between loudness and energy using a regression plot to understand how these features are related.

5. **Popularity vs. Acousticness Correlation**: A regression plot is used to explore the correlation between popularity and acousticness of tracks.

6. **Songs Distribution Over the Years**: We plot a histogram to observe the number of songs released each year and understand the distribution.

7. **Duration of Songs Over the Years**: We visualize the average duration of songs over the years using a line plot to see if there are any trends.

8. **Genres Analysis**: We load and analyze the SpotifyFeatures dataset to gain insights into different genres and their durations and popularity.

## Visualization and Interpretation

Throughout the analysis, we utilize various visualizations, including bar plots, line plots, histograms, and regression plots. Each visualization is accompanied by a brief interpretation of the insights gained from the analysis.

## Requirements

To run this notebook, you need the following Python libraries:
- numpy
- pandas
- matplotlib
- seaborn

The data files 'tracks.csv' and 'SpotifyFeatures.csv' should be present in the same directory as this notebook for successful execution.
