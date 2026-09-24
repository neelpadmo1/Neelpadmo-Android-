# Neelpadmo Android App

This project packages the current Neelpadmo website HTML inside an Android WebView.

## Build
1. Open this folder in Android Studio.
2. Let Gradle sync.
3. Select `app`.
4. Build > Build APK(s).
5. The debug APK will be under:
   `app/build/outputs/apk/debug/app-debug.apk`

## Important
- Internet permission is enabled because the website uses Supabase and external services.
- The website is bundled as `app/src/main/assets/neelpadmo.html`.
- WhatsApp/Facebook/other external URL schemes are handed to Android when possible.
- The Android back button navigates the WebView history before exiting.

Application ID: `com.neelpadmo.app`
Version: `1.0 (1)`
