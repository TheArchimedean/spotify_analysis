# spotify_analysis
Contains an analysis of my music tastes compared to that of 'general music' from a '1 Million Tracks' dataset, and will later contain a thorough analysis of that dataset.

The ommited files from this repository are `credentials.json` and `spotify_data.csv`.

- `spotify_data.csv` will be automatically downloaded when running the Jupyter notebook `Spotify 1 Million Track Analysis.ipynb`.
- `credentials.json` will need to be created by the user. They need a Spotify Client ID and secret, which can be obtained by creating an app in [Spotify for developers](https://developer.spotify.com/dashboard).
  - Inside the `.json` file should contain:
    `{"SPOTIFY_CLIENT_ID": "################################", "SPOTIFY_CLIENT_SECRET":"################################"}`
