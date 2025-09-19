# Student Performance Clustering

A Data Science project that applies K-Means clustering to group students based on their performance in Math, Reading, and Writing.  
The project was developed as part of the Data Science coursework at Universiti Teknologi PETRONAS.

## Features
- Cleaned and prepared dataset of 1,000+ student records
- Applied **K-Means clustering** to identify performance groups
- Evaluated model quality using **Elbow Method** and **Silhouette Score** (0.54)
- Visualized results with PCA plots and cluster graphs
- Provided insights for identifying at-risk students and supporting academic improvement

## Tech Stack
- Language: **R**
- Libraries: `dplyr`, `ggplot2`, `factoextra`, `cluster`

## How It Works
1. Load and clean the student performance dataset
2. Run K-Means clustering for different values of *k*
3. Use the Elbow Method and Silhouette Score to find the optimal cluster count
4. Visualize clusters using PCA and scatter plots
5. Interpret results to recommend academic support strategies

## Example Results
- Optimal number of clusters: **3**
- Silhouette Score: **0.54**
- Cluster groups show clear separation of high, medium, and low performers

## How to Run
```R
# Install required packages
install.packages(c("dplyr", "ggplot2", "factoextra", "cluster"))

# Run the script
source("student_performance_clustering.R")
