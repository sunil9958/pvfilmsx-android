# PvFilmsX Android App

This is a lightweight Android WebView wrapper for the existing PvFilmsX website.

- App name: PvFilmsX
- Website: https://pvfilmsx-app.vercel.app/
- Package ID: xyz.pvfilmsx.app
- Video playback: handled by the website/WebView
- Direct downloads: handed to Android Download Manager
- Telegram/external links: opened by Android

## Build APK on GitHub (phone-friendly)

1. Upload the contents of this folder to a new GitHub repository, or add them to a new repository.
2. Open the repository's **Actions** tab.
3. Select **Build PvFilmsX APK** and tap **Run workflow** (or wait for the push build).
4. Open the completed workflow run.
5. Under **Artifacts**, download `PvFilmsX-debug-apk`.
6. Extract the ZIP and install `app-debug.apk` on Android. Allow installation from that browser/file manager if Android asks.

This produces a debug APK for testing, not a Play Store release-signed APK.

## Notes

The app loads the live website, so catalog and site changes appear without rebuilding the APK. Test streaming and downloads on the installed APK before sharing it. A signed release build and a custom launcher icon can be added later.
