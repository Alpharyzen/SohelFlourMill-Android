# Sohel FlourMill — Android App

WebView app with floating overlay bubble that loads:
https://alpharyzen.github.io/Sohel-FlourMill-/admin_v2.html

## Features
- Full website inside app (sound/media enabled)
- Floating bubble icon overlay (system-wide, draggable)
- Tap bubble → opens the app instantly

## Build steps
1. Install **Android Studio** (latest).
2. Open this folder as a project (`File → Open`).
3. Let Gradle sync (downloads Android SDK if needed).
4. Click **Run ▶** to install on your phone (USB debugging on),
   OR `Build → Build Bundle(s) / APK(s) → Build APK(s)` to get an APK file.
5. On first launch, allow **Display over other apps** permission.

## Notes
- App icon ke liye `app/src/main/res/mipmap-*/ic_launcher.png` mein apna logo daal do (Android Studio mein right-click `res` → New → Image Asset).
- URL change karna ho to `MainActivity.kt` mein `SITE_URL` edit karo.
