# NFL Receivers Analysis with K-means Clustering

## Project Overview

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

The analysis resulted in distinct clusters of NFL receivers, each with unique performance profiles. These clusters can be used for further insights, such as identifying top performers, consistent players, and those with specific strengths.

## How to Run the Project

### Prerequisites

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib (for visualizations, if any)
- Jupyter Notebook (optional, for interactive analysis)

### Instructions

1. **Clone the Repository**

   ```sh
   git clone https://github.com/yourusername/nfl-receivers-clustering.git
   cd nfl-receivers-clustering
   ```

2. **Install the Required Packages**

   ```sh
   pip install pandas numpy scikit-learn matplotlib
   ```

3. **Run the Analysis**

   Open the Jupyter Notebook `nfl_receivers_analysis.ipynb` and run all cells to perform the clustering analysis. Alternatively, you can run the Python script `nfl_receivers_analysis.py`:

   ```sh
   python nfl_receivers_analysis.py
   ```

## Repository Structure

- `data/`: Contains the dataset used for the analysis.
- `nfl_receivers_analysis.ipynb`: Jupyter Notebook with the complete analysis.
- `nfl_receivers_analysis.py`: Python script for the analysis.
- `README.md`: Project documentation.

## Conclusion

This project demonstrates the application of K-means clustering to analyze NFL receivers based on key performance metrics. The resulting clusters provide valuable insights into the performance and characteristics of different receivers.

## Contact

For any questions or suggestions, please reach out to [yourname@domain.com](mailto:yourname@domain.com).

---

This README provides a comprehensive overview of your project, including the methodology, results, and instructions for running the analysis. Adjust the content as necessary to fit your specific project details and dataset.
