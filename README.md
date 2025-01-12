# Spotipie
Spotipie is an intuitive Spotify assistant that utilizes emotion detection and hand gesture control. By analyzing facial expressions and recognizing hand gestures, it allows seamless music playback control, providing a personalized and interactive experience.

Installation
Clone the repository.
  git clone https://github.com/mohittalwar23/Spotipie
Install the Required packages.
  pip install -r requirements2.txt
Set up the Spotify API credentials:
You will need a Spotify premium account for this.
Create a Spotify Developer account at https://developer.spotify.com/ and create a new app.
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

References
Some instances in the first draft were referred from:

Spotify-RFID-Record-Player
In the second draft, an attempt was made to replicate emotion detection with CNN:

Emotion Detection with CNN
However, we switched to using MEDIAPIPE in the third draft.

The entire emotion detection part used in our code is referenced from:

Facial Emotion Recognition using Mediapipe
