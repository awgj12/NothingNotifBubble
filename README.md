# Notification Bubbles (Android starter)

A small Android app prototype for Nothing Phone 3a. It displays a temporary floating bubble showing **only the app name** when a notification arrives. Tap it to open that app; long-press or wait 5 seconds to dismiss.

## Permissions the user must enable
1. Notification access.
2. Display over other apps.

The listener receives notification metadata locally. This starter does not save notification content or send data anywhere.

## Get an APK from GitHub (no Android Studio needed)
1. Create a repository named `notification-bubbles` on GitHub.
2. Upload the project files and folders from this starter. Include the `.github/workflows/build-apk.yml` workflow. Don't upload `.gradle/`, `build/`, or local secrets.
3. Commit the upload. GitHub Actions automatically starts a build.
4. Open your repo's **Actions** tab and select the latest **Build Notification Bubbles APK** run.
5. Scroll to **Artifacts** and download `NotificationBubbles-debug-apk`.
6. Extract the downloaded artifact ZIP; it contains `app-debug.apk`. Transfer that APK to your phone and install it.

The workflow can also be started manually from **Actions → Build Notification Bubbles APK → Run workflow**.

## Build locally (optional)
Open this folder in Android Studio, sync Gradle, then Build → Build APK(s).

## Prototype notes
- UI is a basic Compose setup screen.
- Overlay is a basic TextView bubble and not yet draggable or configurable.
- This is a starter project. GitHub Actions compiles a debug APK, not a signed Play Store release.
