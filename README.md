# Caribbean Tents & Pirate Ships — Android project

This is an offline Android WebView wrapper for the supplied HTML/Canvas game.

## Build an APK

1. Install Android Studio (current stable) and the Android SDK Platform 35.
2. Open this folder (`caribbean-pirate-android`) in Android Studio.
3. Allow Gradle sync to complete.
4. Choose **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
5. Android Studio will show the generated APK location (normally `app/build/outputs/apk/debug/app-debug.apk`).

The app does not request the INTERNET permission. The game is bundled in `app/src/main/assets/index.html` and runs offline.

## App details
- App name: Caribbean Pirate Ships
- Package: `com.example.caribbeantents`
- Minimum Android: 6.0 (API 23)
- Target/compile SDK: 35
- Orientation: portrait
