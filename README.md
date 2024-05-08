# Spotify Song Success Predictor

## Project Description
This project aims to predict the success of Spotify songs based on various audio and metadata features. The model built in this project can be a useful tool for artists, record labels, and anyone interested in understanding what makes a song popular on Spotify.

## Dataset
The dataset used in this project consists of features for tracks fetched using Spotify's Web API. The tracks are labeled '1' or '0' ('Hit' or 'Flop') depending on some criteria. The dataset includes the following features:

- **Track**: The Name of the track.
- **Artist**: The Name of the Artist.
- **URI**: The resource identifier for the track.
- **Danceability**: Describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity.
- **Energy**: A perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy.
- **Key**: The estimated overall key of the track. Integers map to pitches using standard Pitch Class notation.
- **Loudness**: The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks.
- **Mode**: Mode indicates the modality (major or minor) of a track, the type of scale from which its melodic content is derived.
- **Speechiness**: Detects the presence of spoken words in a track.
- **Acousticness**: A confidence measure from 0.0 to 1.0 of whether the track is acoustic.
- **Instrumentalness**: Predicts whether a track contains no vocals.

## Files
- `spotify-cl.ipynb`: This Jupyter notebook contains the code for the project.
- `spotify-song-success-predicter.xpynb`: This Jupyter notebook contains the extended version of the project.
- `spotify_songs.csv.zip`: This zip file contains the dataset used in the project.

## Usage
To run the project, you need to have Jupyter notebook installed on your system. You can then clone the repository and run the Jupyter notebooks.

## Contributing
Contributions are welcome. Please feel free to fork the project and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
