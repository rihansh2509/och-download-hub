# Offline Communicator - Download Hub

This repository hosts the downloadable APK for the Offline Communicator project, allowing for easy installation on Android devices.

## How to update the app:
1. Compile your Flutter app for release:
   `flutter build apk --split-per-abi`
2. Navigate to your build folder: 
   `build/app/outputs/flutter-apk/`
3. Copy the `app-arm64-v8a-release.apk` file.
4. Paste it into the `releases/` folder in this directory.
5. Rename it to `offline-communicator-v1.apk` (or update the link in `index.html` if you change the version number).
6. Commit and push your changes to GitHub!

## GitHub Pages Setup
1. Go to your repository settings on GitHub.
2. Select **Pages** from the left sidebar.
3. Set the source to **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder.
5. Click **Save**. Your site will be live in a few minutes!
