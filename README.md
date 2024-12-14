# CS 441 Final Project Data
## Jamie Rollison, Cole Zimmerman

Sources:
- https://www.kaggle.com/datasets/tobennao/rym-top-5000
- https://www.kaggle.com/datasets/nadintamer/top-spotify-tracks-of-2018
- https://www.kaggle.com/datasets/iamsumat/spotify-top-2000s-mega-dataset
- https://www.kaggle.com/datasets/tomigelo/spotify-audio-features

We used the spotify API to get the songs in each album, then attempted to find their audio features. However,
as of November 2024, Spotify has removed the ability to get audio features for each song via their API, so we instead
attempted to look them up in existing Kaggle databases. We were able to find 2000+ songs. Source code for collecting the data
is in `scraper.ipynb`, and our final dataset is in `rym-songs.csv`.