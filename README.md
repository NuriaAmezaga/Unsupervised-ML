# Music Playlist Creation Using K-Means Clustering and Advanced Techniques

## Introduction

This project demonstrates how to create music playlists using K-Means clustering and other advanced techniques such as deep learning and collaborative filtering. By leveraging Spotify's audio features and user interaction data, we can generate sophisticated and personalized music playlists.

## Features

- **Data Collection and Preprocessing**: Gather and normalize audio features from Spotify's API.
- **K-Means Clustering**: Apply the K-Means algorithm to group songs into clusters based on their audio features.
- **Elbow Method for Optimal k**: Determine the optimal number of clusters using the Elbow Method.
- **Cluster Interpretation**: Evaluate and interpret the characteristics of each cluster.
- **Playlist Creation**: Generate playlists based on the clustered groups of songs.
- **Advanced Techniques**: Explore deep learning (autoencoders and neural networks) and collaborative filtering for improved clustering and personalization.
- **Reclustering**: Differentiate playlists further by reclustering within each initial cluster for more refined groupings.

## Audio Features

### Jazz vs. Party Music

- **Jazz**:
  - Tempo: Moderate to slow
  - Energy: Moderate to low
  - Danceability: Low to moderate
  - Acousticness: High
  - Instrumentalness: High
  - Liveness: Moderate to high
  - Valence: Variable

- **Party Music**:
  - Tempo: Fast
  - Energy: High
  - Danceability: High
  - Acousticness: Low
  - Instrumentalness: Low to moderate
  - Liveness: Low to moderate
  - Valence: High
  - 
![image](https://github.com/NuriaAmezaga/Unsupervised-ML/assets/168557674/20f23d63-d36f-45a5-b613-e47e0fc612d3)

## Clustering with K-Means

### Determining the Optimal Number of Clusters

Use the Elbow Method to plot the inertia score against the number of clusters (k) to find the optimal number of clusters for your data.

![image](https://github.com/NuriaAmezaga/Unsupervised-ML/assets/168557674/f7e378da-6233-4eb5-a255-a44cc6129376)


### Applying K-Means and Creating Playlists

After determining the optimal k, apply K-Means to the normalized audio features and create playlists based on the clustered groups of songs.

## Advanced Techniques

### Deep Learning

Autoencoders or neural networks can learn complex representations of music features, leading to more sophisticated clustering. This approach captures intricate patterns and relationships in the data.

### Collaborative Filtering

Uses user behavior data to find similarities between songs based on user preferences rather than audio features alone. This method creates highly personalized recommendations.

## Reclustering

After the initial clustering, reclustering within each cluster can further differentiate the playlists, creating more refined and specific groupings of songs.

## Visualizing Clusters

A heatmap can be used to explain how the clusters are similar or different from each other:

- "A heatmap in a playlist illustrates the similarities and differences between the clusters."
- "Cluster 2 is remarkably different from Cluster 7."

## Conclusion and Recommendations

By leveraging K-Means clustering and advanced techniques, we can create effective and personalized music playlists. For best results:

1. **Utilize Advanced Clustering Techniques**: Explore deep learning methods like autoencoders and neural networks to capture complex patterns in music features.
2. **Implement Collaborative Filtering**: Use collaborative filtering for personalized recommendations based on user behavior data.
3. **Combine Both Methods**: Develop a hybrid system that combines deep learning and collaborative filtering for optimal playlist creation.
4. **Reclustering**: Differentiate playlists further by reclustering within each initial cluster.
5. **Include Additional Dimensions**: Incorporate other dimensions such as the year of release to create more nuanced clusters.
6. **Continuous Evaluation**: Regularly evaluate and refine the models to ensure the quality and relevance of the playlists.


