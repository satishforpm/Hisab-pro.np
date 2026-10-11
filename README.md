# HisabPro – Android project

1. Install Android Studio (latest). File → Open → this `HisabPro` folder. Let Gradle sync (it downloads the wrapper/SDK).
2. Run on a phone/emulator (Run ▶). Test everything offline (airplane mode).
3. Release: Build → Generate Signed App Bundle (.aab). Create and BACK UP your upload keystore. Upload the .aab in Google Play Console.
4. Package id is `com.satishdev.hisabpro` (change in app/build.gradle.kts before first upload if you want another; it can never change later).
5. Take real screenshots from the running app (emulator toolbar camera icon) for the Play listing. `play_store_icon_512.png` is the 512x512 store icon.
6. Host `privacy.html` at a public URL and enter it in Play Console.

The calculators live in `app/src/main/assets/index.html` (HTML/JS, runs fully offline inside a WebView). The app declares no INTERNET permission.
