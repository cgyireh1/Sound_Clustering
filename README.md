# Sound_Clustering
This assignment aims to apply clustering techniques to an unlabeled sound dataset, analyze the necessity of dimensionality reduction, and compare different clustering methods. It explores the effectiveness of K-Means and DBSCAN clustering, with PCA and t-SNE applied for dimensionality reduction.

### Dataset

- Format: Audio files (.wav)

- Feature Extraction: Mel Spectrogram computed using Librosa

### Feature Extraction

Used librosa and Mel Spectrogram  for the feature extraction.


### Dimensionality Reduction Techniques

- PCA (Principal Component Analysis)

- t-SNE (t-Distributed Stochastic Neighbor Embedding


## Clustering Methods

- K-Means Clustering

Determined optimal k using the Elbow Method.

Applied K-Means with k=3.

- DBSCAN (Density-Based Spatial Clustering of Applications with Noise)

Applied with eps=5 and min_samples=3.


## Results

K-Means performed better than DBSCAN, achieving a Silhouette Score of 0.1741 and a Davies-Bouldin Index of 1.7984.

DBSCAN failed to form meaningful clusters

