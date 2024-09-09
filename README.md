# Data-Analysis-with-SpotifyAPI

### Overview
This project investigates the factors contributing to the popularity of a song and how these factors vary across genres and different time periods. In addition to the analysis, a simple music recommendation system is implemented using the Spotify API. Key insights from this analysis show interesting trends in music over the years, such as the increasing danceability of songs and the decreasing duration in response to social media platforms like TikTok, Instagram Reels, and YouTube Shorts.

### Key Insights
- **Genre Similarities**: Some genres, such as Love and R&B, exhibit similar audio patterns, likely due to their emotional and expressive nature.
- **Song Evolution**: Since the mid-2010s, songs have become shorter and more danceable, driven by the new format of social media content (Musically/TikTok).
- **Audio Features**: Audio features do not significantly affect a song's popularity score.
- **Clustering**: KMeans clustering revealed some severe outliers, possibly due to the limited dataset, but overall, a trend of songs sounding more similar to each other was observed.

### Suggestions for Further Analysis
- **Extended Analysis**: Expanding the dataset to include more tracks would allow further exploration of the 'TikTokification' trend, as well as a comparison of pre-2000s music.
- **Seasonal Preferences**: Further analysis could investigate whether certain genres are more popular during different times of the year.
- **Social Media Impact**: A potential future analysis could involve correlating social media mentions of artists with their popularity on Spotify.
- **Improved Recommendation System**: The current recommendation system could benefit from a larger dataset and more complex algorithms.

### Spotify API Usage
- **/categories**: Used to collect genre information.
- **/search**: To search for tracks.
- **/audio_features**: To retrieve audio feature data for each track.

### Requirements
To run the notebooks and collect the data, you’ll need the following:
- Python 3.x
- Jupyter Notebook
- Spotify API credentials (you can create an account and obtain these [here](https://developer.spotify.com/))

### Future Work
- Expanding the recommendation system with more advanced methods and a larger dataset.
- Investigating whether certain audio features correlate with seasonal or regional popularity.

### How to Use
1. Clone this repository:
   ```
   git clone https://github.com/AnthonyLovesCoffee/Data-Analysis-with-SpotifyAPI.git
   ```
2. Add your Spotify API credentials to the notebook or environment.
3. Run the notebooks to collect data and perform the analysis.
