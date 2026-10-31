# Video Downloader (Android APK)

The whole app runs on the phone: Flask + yt-dlp (via Chaquopy) behind a WebView.

## Build the APK without installing anything
1. Create an empty GitHub repo and push this folder to `main`:
   git init && git add . && git commit -m init
   git branch -M main
   git remote add origin https://github.com/YOUR-NAME/videodl.git
   git push -u origin main
2. GitHub > Actions > "Build APK" (runs on push, or press Run workflow).
3. Open the finished run > Artifacts > VideoDownloader-apk > unzip > app-debug.apk
4. Copy to the phone, tap it, allow "install unknown apps".

## Or with Android Studio
File > Open this folder, let it sync, Build > Build APK(s).

Requires Android 10+ (arm64 or x86_64).
