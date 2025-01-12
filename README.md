# Spotipie

**Spotipie** is an intuitive Spotify assistant that combines emotion detection and hand gesture control. By analyzing facial expressions and recognizing hand gestures, Spotipie allows seamless music playback control, providing a personalized and interactive experience.

## Table of Contents
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Spotify API Setup](#spotify-api-setup)
- [References](#references)

## Installation

Follow these steps to get Spotipie up and running:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/mohittalwar23/Spotipie
Install the required packages:

Navigate to the repository folder and run:

bash
Copy code
pip install -r requirements2.txt
Set up the Spotify API credentials:

You will need a Spotify Premium account to access the API.
Create a Spotify Developer account at Spotify Developer Dashboard and create a new app.
Obtain the CLIENT_ID, CLIENT_SECRET, and set the redirect_uri to http://localhost:8080 in the SpotifyOAuth initialization.

Dependencies
Ensure you have the following dependencies installed:

cv2
csv
copy
itertools
numpy
mediapipe
model (custom module)
cvzone
time
spotipy
pyttsx3
threading

Spotify API Setup
To use the Spotify API, you'll need to configure your Spotify Developer credentials as described in the Spotify Developer Documentation. This involves creating an app in the Spotify Developer Dashboard, obtaining CLIENT_ID and CLIENT_SECRET, and configuring your redirect URI to match the one set in your project.

References
Some components and methods used in this project were inspired by the following resources:

Spotify-RFID-Record-Player
Emotion Detection with CNN
An earlier draft attempted to replicate emotion detection using Convolutional Neural Networks (CNN), but this approach was later replaced with Mediapipe.
Facial Emotion Recognition using Mediapipe
The emotion detection code used in Spotipie is based on the Facial Emotion Recognition using Mediapipe approach.
Feel free to explore these references for more details on the emotion detection process and its integration with Spotipie.
