# NFL Receivers Analysis with custom K-means Clustering

## Project Overview

In this project, a custom K-means clustering algorithm was implemented from scratch to analyze the performance of NFL receivers. The custom implementation allows for flexibility in parameter tuning and optimization tailored to the specific dataset and requirements of the analysis.

This project involves performing a K-means clustering analysis on NFL receivers using five key features:
- **Games Played**
- **Receptions**
- **Receiving Yards**
- **Yards Per Reception**
- **Receiving TDs**

The goal is to identify clusters of receivers with similar performance metrics, which can provide insights into player performance and groupings based on their statistical profiles.

## Dataset

The dataset used for this analysis contains the following columns:
- **Name**: The name of the NFL receiver.
- **Games Played**: The number of games played by the receiver.
- **Receptions**: The number of receptions made by the receiver.
- **Receiving Yards**: The total number of receiving yards.
- **Yards Per Reception**: The average yards gained per reception.
- **Receiving TDs**: The total number of receiving touchdowns.

## Features

The features selected for clustering are:
- **Games Played**
- **Receptions**
- **Receiving Yards**
- **Yards Per Reception**
- **Receiving TDs**

## Clustering Methodology

### Data Preprocessing

1. **Data Cleaning**: Handling missing or invalid data, such as replacing '--' with `NaN` and removing commas from numerical fields.
2. **Normalization**: Normalizing the data to ensure that each feature contributes equally to the distance calculations during clustering.

### K-means Clustering

1. **Choosing the Number of Clusters**: Using methods like the Elbow Method and Silhouette Score to determine the optimal number of clusters.
2. **Model Training**: Applying the K-means algorithm to cluster the receivers based on the selected features.
3. **Cluster Analysis**: Analyzing the resulting clusters to interpret the characteristics and performance of receivers in each group.

## Results
![](https://github.com/Praneshv25/K-Means-Custering/blob/main/Screenshot%202024-05-30%20at%203.04.28%E2%80%AFPM.png)
The analysis resulted in distinct clusters of NFL receivers, each with unique performance profiles. These clusters can be used for further insights, such as identifying top performers, consistent players, and those with specific strengths.

## Conclusion

This project demonstrates the application of K-means clustering to analyze NFL receivers based on key performance metrics. The resulting clusters provide valuable insights into the performance and characteristics of different receivers.
