OBSIDIAN PAY — ANDROID STUDIO PROJECT

This is the Android WebView wrapper source project. It is ready to open in Android Studio and build into an APK.

BUILD APK
1. Install Android Studio (current stable) and Android SDK Platform 35 + Build Tools.
2. Open this folder (the folder containing settings.gradle) in Android Studio.
3. Allow Gradle sync/downloads.
4. Choose Build > Build Bundle(s) / APK(s) > Build APK(s).
5. Android Studio will show the APK location (usually app/build/outputs/apk/debug/app-debug.apk).

The current build environment did not include Android SDK, Gradle, or network access, so an APK binary could not be compiled here.

SECURITY / BANK DATA
This app bundles the existing Obsidian Pay HTML. Its Nepal Bank tracker remains manual/CSV-import based. No Nepal Bank API integration exists, and no live balance is fetched. Do not add bank passwords, PINs, OTPs, JWTs or API secrets to this project.
