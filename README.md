# sainath Android Launcher APK Project

This Android Studio (Kotlin + Jetpack Compose) project was exported with your exact custom theme colors, icon pack style (tactile-color), icon shape (circle), bento tile layout, and pinned Android dock apps.

## Build Your Installable APK

### Option 1: Android Studio (Recommended)
1. Unzip this folder and open **monoblock-android-launcher** in **Android Studio**.
2. Wait for Gradle Sync to finish automatically.
3. From the top menu click **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
4. Copy `app/build/outputs/apk/debug/app-debug.apk` to your Android phone and install it.
5. Open Android **Settings → Apps → Default apps → Home app** and select **sainath Launcher**.

### Option 2: Command Line
```bash
./gradlew assembleDebug
adb install app/build/outputs/apk/debug/app-debug.apk
```
