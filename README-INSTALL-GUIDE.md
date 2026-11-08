# Noor Tasbih — How to Daily-Drive on Your Android Phone

Because the browser sandbox cannot compile raw binary `.apk` files directly, this package gives you **3 fast ways** to install and daily-drive Noor Tasbih on your Android phone today:

## Way 1: Instant Full-Screen Phone Install (Takes 15 Seconds — No APK Needed)
1. Copy `Noor-Tasbih-Standalone.html` to your Android phone (or click **📲 Download Standalone Phone App** inside the app's **2. Daily Logs** tab).
2. Open the file in **Google Chrome** on your Android phone.
3. Tap the **three-dot menu (`⋮`)** in the top-right corner of Chrome and select **Add to Home screen**.
4. Tap **Add**. An icon named **Noor Tasbih** will appear on your home screen, launching full-screen and saving your daily logs permanently on your phone!

## Way 2: Convert `Noor-Tasbih-Standalone.html` into an `.apk` in 30 Seconds
* **On Windows / Desktop:** Open [Website 2 APK Builder](https://websitetoapk.com/), select **Local HTML Website**, choose this folder (`index.html`), set the title to **Noor Tasbih**, and click **Build Android APK**.
* **In the Cloud (Zero Install via GitHub):** Upload the contents of this `.zip` to a free GitHub repository. The included `.github/workflows/build-apk.yml` workflow will automatically compile `app-debug.apk` in ~90 seconds under the **Actions** tab!

## Way 3: Build the Native Android Studio Project (Included in `app/`)
This zip includes a complete native Android WebView wrapper (`MainActivity.java`) that also intercepts **Volume Up (`+1`)** and **Volume Down (`Side Button`)** even when a DIY Bluetooth ring acts as a media remote:
1. Open this folder in [Android Studio](https://developer.android.com/studio).
2. Click **Build → Build Bundle(s) / APK(s) → Build APK(s)**.
