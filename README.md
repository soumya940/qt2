# QT - Quotient Tracker (Android, offline)

1. Create a new GitHub repository and upload everything from this folder (keep the `.github` folder).
2. Open the **Actions** tab, choose **Build QT Android APK**, press **Run workflow** (it also runs on every push).
3. When it turns green, open the run and download the **QT-debug-apk** artifact. Unzip it and install `app-debug.apk` on your phone (allow "install unknown apps").

The app works fully offline. Your data is stored inside the app on the phone (WebView localStorage) and stays when you close or update the app. Use Settings > Export JSON to keep a backup.

To change the app: edit `www/index.html`, or replace the pictures in `assets/`, and push again.
