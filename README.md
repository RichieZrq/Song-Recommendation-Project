# Spotify-Song-Recommendation-Project

The group_3_final_project.ipynb notebook contains all code necessary to reproduce results reported in our project report. No additional datasets have to be downloaded, as we used the kagglehub package to load all datasets in the project.

The notebook contains all parts of our development journey in chronological order:

1. EDA and Data Preprocessing (running the code in this section sets up the dataset for clustering and modeling steps)

    a. EDA and Preproccesing for Classic Hits Dataset

    b. EDA and Preprocessing for Spotify Playlists Dataset

    c. EDA and Preprocessing for Larger Spotify Tracks Dataset:

2. Clustering (running the code in this section would replicate clustering results presented in our report)

    a. K-Prototypes Clustering

    b. DBSCAN Clustering

3. KNN Recommender Implementation (running the code in this section sets up the our KNN recommender system that we use in the next part to recommend songs and playlists)

4. Integrating Spotify Playlists with the KNN Recommender (running the code in this section replicates results for song and playlist recommendations)

5. Model Evaluation (running the code cells in this section sets up our evaluation metric and replicates evaluation results from our report)

6. Implementing Presentation Feedbacks by Building a new model (running the code in this section sets up our weighted matrix factorization recommender model)

