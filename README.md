# -Product-Development-Leveraging-Unsupervised-Machine-Learning

# Summary 
This project utilised unsupervised machine learning, in particular K-means clustering, to develop playlist prototypes  from a dataset of 5000 songs for the (mock) company Moosic. The K-means model clustered the songs into “mood” playlists based on 13 quantitative music dimensions i.e. danceability, energy, speechiness etc.
Two prototypes and strategic recommendations were presented to the mock CEO. 

[Please see final presentation.](https://github.com/sngomane/-Product-Development-Leveraging-Unsupervised-Machine-Learning/blob/main/Product%20Develeopment%20leveraging%20Unsupervised%20Machine%20Learning%20.pptx.pdf)

## Languages and Libraries Used 
Python:
* Scikit-learn
* Pandas
*  Seaborn
*  M atplotlib
*   Plotly
See Please see python notebook with code and analysis 
## Arriving at a Prototype and Strategic recommendation 
Data exploration
K-means clustering by cleaning data, scaling it and deciding number of clusters 
Evaluating whether applying Principal Component Analysis(PCA)  refines the K-means model
Presenting, in assigned groups, two Prototypes based on revised group analysis and subsequent product development recommendations. 
## Key Learnings and  Challenges Overcome
How to arrive at the optimal number of playlists from 5000 songs. 
The number of clusters are  central to a K-means model and significantly impact the accuracy and applicability of the model’s results. Applying Technical Analysis such as the Elbow Method and Silhouette score was a useful starting point but not sufficient when taking into account the business case.  Therefore, additional business analysis, customer empathy and common sense were imperative to arrive at the sweet spot for the number of playlists. 
How to evaluate the success of the K-means model for generating playlists.
 The K-means model did generate distinct playlists and the model could be further refined by applying PCA analysis. However, some of the playlists contained a broad range of genres and it is debatable whether they could be categorised into one playlist. As such, an encompassing framework which considered the following success criteria: 1. Interpretability, 2. Business Relevance & 3. Discovery of new patterns  and manually listening to some of the playlists helped arrive at a final recommendation. As a result, K-means clustering was a good starting point to generate playlists but  human intervention and quality control was still required to ensure optimal playlists. 

## Additional Background information
Moosic is a small  start-up that creates playlists which users can listen to via their preferred Music App (be it Spotify, Apple Music, Youtube Music…) after subscribing to Moosic’s website. They love the fact that their playlists have a personal touch, and that each playlist encapsulates a certain “mood” or “style”.
To optimise their playlist generation they are considering utilising basic clustering algorithms such as K-Means to generate playlists. For their prototype development they have collected a dataset of 5000 songs from a Spotify API including a list of audio features (tempo, energy, danceability, etc.) to test whether this process moving forward would support their business case. From this dataset they would like to generate a range of 20-100 playlists. The main questions for their prototype testing are: 
Are songs clustered in relevant and recognisable playlists?
Is K-Means a good method to create playlists?  Is this algorithm sufficient moving forward, or other methods need to be explored to arrive at the final playlists ?



