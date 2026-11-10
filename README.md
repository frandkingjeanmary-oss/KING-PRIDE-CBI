# KING PRIDE CBI Android project

This repository builds a debug APK with GitHub Actions.

## Build
1. Upload all files and folders in this project to a GitHub repository.
2. Make sure the default branch is `main`.
3. Open the repository's **Actions** tab.
4. Select **Build KING PRIDE APK** and press **Run workflow** (or wait for the first push build).
5. When the run finishes, open it and download the `KING-PRIDE-CBI-APK` artifact.
6. Extract the downloaded ZIP to get `app-debug.apk`.

Note: The supplied HTML refers to `king_pride_logo.png`. That image was not included with the uploaded HTML, so the app will hide the logo until you add that image at `www/king_pride_logo.png`.
The app validates number format only; it cannot verify whether a WhatsApp number is blocked or banned.
