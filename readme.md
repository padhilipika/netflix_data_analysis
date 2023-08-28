# Netflix Catalog Analysis Project

## Summary

Welcome to the **Netflix Catalog Analysis Project**! This repository contains the code and resources for analyzing the Netflix catalog of movies and TV shows. Our goal is to group these shows into relevant clusters, contributing to an enhanced user experience and reduced subscriber churn for Netflix, the world's largest online streaming service provider.

As of 2022-Q2, Netflix boasts over 220 million subscribers globally. This project aims to leverage a dataset sourced from the third-party search engine Flixable, which includes movies and TV shows up to 2019, consisting of approximately 7787 records with 11 attributes.

## Objectives

- Analyze the Netflix catalog to discover insights and trends within the streaming entertainment industry.
- Enhance user experience by categorizing shows into meaningful clusters.
- Utilize clustering algorithms to group shows based on attributes like cast, country, genre, director, rating, and description.
- Implement a content-based recommender system using cosine similarity on the generated clusters.

## Project Steps

1. **Data Preprocessing and Exploratory Data Analysis (EDA)**:
   - Address missing values in the dataset.
   - Conduct exploratory analysis to understand the dataset's characteristics.

2. **Attribute Selection and Vectorization**:
   - Utilize attributes like cast, country, genre, director, rating, and description for clustering.
   - Tokenize, preprocess, and vectorize these attribute values using TFIDF vectorizer.

3. **Dimensionality Reduction**:
   - Address dimensionality using Principal Component Analysis (PCA).

4. **Cluster Construction**:
   - Employ K-Means Clustering and Agglomerative Hierarchical clustering algorithms.
   - Determine optimal cluster count using methods like the elbow method, silhouette score, dendrogram, etc.

5. **Content-Based Recommender System**:
   - Generate a similarity matrix using cosine similarity on attribute vectors.
   - Develop a content-based recommender system to suggest ten shows based on the user's watched show type.

## Getting Started

1. Clone this repository:
   ```bash
   git@github.com:padhilipika/netflix_data_analysis.git
   cd netflix_data_analysis
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the analysis scripts and notebooks provided in the repository.

## Contributors


## Acknowledgments

We would like to express our gratitude to Flixable for providing the dataset used in this project, as well as the open-source community for their invaluable tools and resources.

## Contact

For questions, suggestions, or contributions, please feel free to contact us at [lipikapadhi1995@gmail.com](mailto:lipikapadhi1995@gmail.com).

---

*Note: This project is for educational and non-commercial purposes.*