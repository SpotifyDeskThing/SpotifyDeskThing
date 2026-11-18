# Spotify Remote

[![Latest Release](https://img.shields.io/github/v/release/TONY-STANK/SpotifyDeskThing?label=latest)](https://github.com/TONY-STANK/SpotifyDeskThing/releases/latest)

A small native Android remote for Spotify playback on the same phone. The app reads Spotify's Android media session for the current track and sends standard Android playback controls. It does not ask for Spotify account credentials.

## Download

Grab the latest APK from the [Releases page](https://github.com/TONY-STANK/SpotifyDeskThing/releases/latest) and install it on any Android 8.0+ device.

1. Tap the **app-release.apk** link on the Releases page to download.
2. Open the downloaded file on your phone. Android will ask for permission to install apps from this source — allow it.
3. The app will install and appear as **Spotify Remote** in your app drawer.

## Run on your Motorola

1. Install Android Studio and open this project folder. Let Gradle sync and install Android SDK 35 if prompted.
2. Connect your phone with USB debugging enabled, then run the `app` configuration from Android Studio.
3. Open Spotify on the phone and sign in. In Spotify Remote, tap the settings icon and enable notification access for Spotify Remote.
4. Return to the app and tap **OPEN SPOTIFY TO CHOOSE MUSIC**. Start a song or playlist in Spotify, then return to Spotify Remote.

Notification access is required by Android to read active media sessions. The app uses that access only to display Spotify playback and control it; track selection happens in the Spotify app itself.

## Controls

- Tap the left button once to restart the current track. Tap it twice quickly to go to the previous track.
- Drag the bar between the left and right buttons to change the phone's media volume.
- Drag the timeline below the track information to seek.
- Use the center button to play or pause and the right button to skip forward.
- Open Spotify to select a different track or playlist; the remote updates when playback changes.