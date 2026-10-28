# Loop music player

Loop is a phone-first installable web app for playing audio files already on your device. It supports a local music library, playlists, shuffle, repeat playlist, repeat song, seeking, volume, and Android media controls.

## Use it on Android

The app needs to be served from an HTTPS website to install as a PWA. Put the files in this folder on any HTTPS static host, open its URL in Chrome on Android, then use **⋮ → Install app** or **Add to Home screen**. Select **Add music** in Loop and choose audio files from the phone.

The library is stored in the browser's local IndexedDB on that phone. Clearing browser site data removes the imported library. These files do not include a commercial music catalog; use audio you own or are allowed to play.

## Files

- `index.html`: app interface and playback logic
- `manifest.webmanifest`: Android install metadata
- `sw.js`: app shell caching for offline launch
