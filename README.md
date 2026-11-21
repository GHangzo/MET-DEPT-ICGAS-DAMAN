# Tatrakshak Mausam Vibhag – Daman Manpower Manager

Starter Android app project (Kotlin + Jetpack Compose) intended to be customized for office manpower administration.

## Features in the starter
- Dashboard and manpower status counts
- Personnel register
- Attendance status records
- Search and local phone storage

## Build an APK using GitHub.com (no local Android Studio required for the build)
1. Sign in to GitHub and create a **new repository** (for example, `ManpowerManager`).
2. Upload the contents of this folder to the repository's root (not the folder itself nested inside another folder). Commit to `main`.
3. Open the repository's **Actions** tab. The workflow `Build Android APK` should start automatically after the push. You can also select it and click **Run workflow**.
4. Wait for the workflow to finish successfully.
5. Open the completed workflow run, scroll to **Artifacts**, and download `manpower-manager-debug-apk`.
6. Extract the downloaded artifact and install the APK on your Android phone. You may need to allow installation from your browser or file manager.

## Build locally
Open the project folder in Android Studio, sync Gradle, and use **Build > Build APK(s)**. Requires JDK 17 and Android SDK.

## Important
This is a prototype and stores data locally on the device. It is not a secure or shared personnel database. Do not enter sensitive personal information until secure authentication, encryption, backup, and access controls have been added. GitHub Actions produces a debug APK, not a signed production release.
