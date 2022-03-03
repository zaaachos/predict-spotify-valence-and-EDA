# predict-spotify-valence-and-EDA

## Description
### Spotify uses a metric called valence to measure the happiness of a track. The metric itself, however, was not developed by Spotify. It was originally developed by Echo Nest, a company that was bought by Spotify in 2014. We don't know exactly how valence is calculated. Some details are given by a blog post, which you can find here:

https://web.archive.org/web/20170422195736/http://blog.echonest.com/post/66097438564/plotting-musics-emotional-valence-1950-2013

In this occasion,our aim is to untangle the mystery behind valence and propose how this is derived. We will use statistical measures to find the most significant track features.
In the end, we will use 5 models to predict valence of the tracks
* XGBoost
* SGDRegression
* RandomForest Regression
* MLP (with dropout 0.1)
* CNNs (with dropout 0.1)


## Environment
* Conda

## Dependencies
* Python
* Tensorflow (Keras)
* NumPy
* Matplotlib
* sklearn
* spotipy
* xgboost

## License
[MIT](https://github.com/zaaachos/predict-spotify-valence-and-EDA/blob/main/LICENSE)
