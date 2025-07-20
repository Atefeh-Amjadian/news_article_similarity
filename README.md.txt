# News Article Similarity Analysis

This project clusters news articles based on their semantic similarity using NLP techniques. It was completed as a learning exercise to demonstrate skills in text processing, embedding, clustering, and visualization.

## Overview
- **Dataset**: Public news articles dataset from [mage-ai](https://raw.githubusercontent.com/mage-ai/datasets/refs/heads/master/news_articles.csv).
- **Techniques**: GloVe embeddings, PCA, K-Means clustering, Word Clouds.
- **Goal**: Group similar articles and visualize key themes.

## Visualizations
### PCA Scatter Plot
![PCA Plot](plots/pca_scatter.png)

### Clustered Scatter Plot
![Clustered Plot](plots/clustered_scatter.png)

### Word Clouds
![Cluster 0](plots/wordcloud_cluster_0.png)
![Cluster 1](plots/wordcloud_cluster_1.png)
![Cluster 2](plots/wordcloud_cluster_2.png)
![Cluster 3](plots/wordcloud_cluster_3.png)

## Installation
```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn wordcloud