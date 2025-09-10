Problem
  - What are the factors that affect how popular a song is on Spotify?

Data Source
  - Dataset: [Spotify Top 200 Charts (2020-2021])(https://www.kaggle.com/datasets/sashankpillai/spotify-top-200-charts-20202021) from Kaggle

Methods
  - Multi-linear regression model
  - collinearity analysis
  - Residual plots

Measures
  - Dependent Variable: Popularity
  - Independent Variables:
    - Danceability
    - Energy
    - Loudness
    - Speechiness
    - Acousticness
    - Liveness
    - Tempo
    - Duration
    - Valence
  - Additional Analysis:
    - P-values of independent variables
    - Multicolinearity / correlation
   
Conclusions
  - Energy had the greatest impact on a song's popularity.
  - However, with an R^2 value of 0.0145, none of the examined variables are strong predictors of popularity on Spotify.

Key Insight
  - While audio features like energy show some relationship to popularity, Spotify song popularity cannot be strongly predicted by these variables alone. Other external factors (e.g., marketing, artist reputation, playlist placements) may play a much larger role.
