# DailyFlow Android APK (build from your phone)

This project wraps the DailyFlow routine tracker in a simple Android WebView app. The HTML is bundled inside the app; no website hosting or network permission is needed. Browser local storage is used to keep routine data on the device.

## Build the APK using GitHub on your phone
1. Download this ZIP and extract it on your phone (Files app can usually extract ZIPs).
2. In your mobile browser, sign in to GitHub and create a new repository named `dailyflow-android`. Choose **Public** or **Private**; either works.
3. Upload the *contents* of this extracted folder to the repository's `main` branch. Make sure `.github/workflows/build-apk.yml` is included. If the GitHub mobile website does not show hidden `.github` folders, use GitHub's web editor or switch the browser to **Desktop site**.
4. Open the repository's **Actions** tab. Select **Build DailyFlow APK** and tap **Run workflow** (if it has not already run automatically).
5. Wait for the workflow to finish with a green check. Open that run and scroll to **Artifacts**. Download `DailyFlow-APK`.
6. Extract the downloaded artifact ZIP. Tap `app-debug.apk` to install it. If Android asks, allow your browser or Files app to **Install unknown apps** for this installation, then retry.

Keep the repository if you want to rebuild the APK later. The APK is unsigned for Play Store publishing, but is suitable for personal sideload installation. Anyone who can access a public repository can see its source; choose a private repository if preferred.
