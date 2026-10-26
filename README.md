# FL Tournament Manager – Android project

This is a ready-to-build Android app (a full-screen WebView that runs the FL Tournament Manager
web app from inside the APK, fully offline).

## Get the APK (no Android Studio needed)

1. Create a free account at github.com and make a **new private repository**.
2. Upload everything in this folder to it (drag and drop the files in the browser, keep the
   `.github` folder).
3. Open the **Actions** tab → **Build APK** → wait about 3–5 minutes for the green tick
   (or press **Run workflow**).
4. Open the finished run, download **FL-Tournament-Manager-apk** (a zip), unzip it and copy
   `app-debug.apk` to your phone.
5. Tap the file on the phone and allow "Install unknown apps" when asked.

## Or build it yourself

Install Android Studio, choose **Open** on this folder, wait for Gradle sync, then
**Build → Build APK(s)**. Command line: `gradle assembleDebug` (JDK 17 + Android SDK 34).

## Changing the app

The whole app lives in `app/src/main/assets/www/index.html`. Edit it and rebuild.
