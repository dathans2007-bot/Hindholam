# Offline Beats 🎧

A home-screen-installable music player for audio files you choose from your phone. It has a library, playlists, next/previous, seeking, shuffle, repeat, playback speed, liked songs, and media controls where supported.

## Put it online with GitHub Pages

1. On GitHub, create a new **public repository** named `offline-beats`.
2. Unzip this ZIP on your phone or computer.
3. Upload **all the files inside** this folder to the repository's root. Upload `index.html`, `app.js`, `styles.css`, `manifest.webmanifest`, `sw.js`, `icon.svg`, and `README.md` directly, not the enclosing folder.
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Choose branch **main** and folder **/(root)**, then tap **Save**.
7. Wait a minute, then open the Pages URL GitHub gives you. It will look like `https://YOUR-USERNAME.github.io/offline-beats/`.
8. In Android Chrome, open that URL, tap **⋮ → Add to Home screen** (or **Install app** if shown), then confirm.

## Use it

- Tap **Add downloaded songs** and select audio files in Android's file picker. You can select multiple files at once.
- Tap a song to play it, use **▶|** to skip, **|◀** to go back, and drag the timeline to fast-forward/rewind.
- Create playlists in **Playlists**, then use the song's **⋯** menu to add songs to playlists or manage Liked Songs.
- Tap **1×** to change playback speed. Shuffle and repeat are beside the playback controls.

## Important limitations

- This is a web app, not a native Android APK. It can be installed on the home screen through Chrome after publishing it over HTTPS.
- Browsers do not let a website silently scan all downloaded music. You must choose files using the file picker.
- Songs and playlists are saved in the browser's local storage (IndexedDB), so they should remain after closing/reopening the app in the same browser. Clearing Chrome site data, uninstalling/clearing the app's storage, or switching browsers can remove them. The app does not upload your music anywhere. Choose files once to import them into the app.
- Keep the app open while listening. Background playback and lock-screen controls depend on Android/browser support.
- GitHub Pages is free for public repositories. Do not put private or copyrighted music files in this repository; only upload the app's source files.
