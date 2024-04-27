# Spotify Recommendation Bot
## Overview
Music &amp; Artist recommendation engine using Spotipy

## Technologies Used
### Environment
* [Jupyter Notebook](https://jupyter.org/)
* [Anaconda](https://www.anaconda.com/download/)
* [Python](https://www.python.org/) (3.11)
### Libraries
* [NumPy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)
* [SciKit-Learn](https://scikit-learn.org/stable/index.html)
* [Spotipy](https://pypi.org/project/spotipy/)
* [Dotenv](https://pypi.org/project/python-dotenv/)

## Installing and Executing the Program
To run the application, perform the following tasks.
* Install Anaconda or Python
* Install Jupyter Notebook
* Clone this repository
* Install the required python libraries (using ```pip install``` or ```conda install```)
* OPTIONAL: Run all the cells in [data_preprocessing.ipynb](data_preprocessing.ipynb) to generate the properly transformed CSV files (they have already been provided)
* Create a Spotify App on the [Spotify API Dashboard](https://developer.spotify.com/dashboard)
* Create a .env file and enter in the following information:
```
CLIENT_ID=your-client-id
CLIENT_SECRET=your-client-secret
REDIRECT_URI=http://localhost:3000
```
NOTE: These values (Client ID and Client Secret) are gotten from the app you created on the Spotify API (click on your app and go to settings)
* Find your Spotify username on your [profile](https://www.spotify.com/us/account/profile/) page
* Run all the cells in [spotify_recommendation_system.ipynb](spotify_recommendation_system.ipynb)
