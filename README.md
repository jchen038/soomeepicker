# Sumikko Chooser - Android APK Project

This package contains the complete native Android WebView project for **Sumikko Chooser**, configured for offline storage (`domStorageEnabled`), status bar styling, and sound synthesis.

## Option 1: Build APK in 1 Click via GitHub Actions (No Android SDK Required)
1. Upload this folder to a GitHub repository.
2. Go to the **Actions** tab and run **Build Sumikko Chooser APK**.
3. Download `SumikkoChooser-debug-apk` from the workflow artifacts and sideload `app-debug.apk` onto your Android phone.

## Option 2: Build Locally in Android Studio / CLI
1. Open this folder in **Android Studio**.
2. Select **Build > Build Bundle(s) / APK(s) > Build APK(s)**, or run:
   ```bash
   gradle assembleDebug
   ```
3. Install the generated APK from `app/build/outputs/apk/debug/app-debug.apk`.
