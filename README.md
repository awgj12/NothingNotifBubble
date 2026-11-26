# Notification Bubbles (Android starter)

A small Android app prototype for Nothing Phone 3a. It displays a temporary floating bubble showing **only the app name** when a notification arrives. Tap it to open that app; long-press or wait 5 seconds to dismiss.


## Permissions the user must enable
1. Notification access (Android settings page opened from the app).
2. Display over other apps (Android settings page opened from the app).

The listener receives notification metadata locally. This starter does not save notification content or send data anywhere.


## Build
- Open this folder in Android Studio.
- Let Gradle sync.
- Build > Build Bundle(s) / APK(s) > Build APK(s).
- Test on your phone and enable the two permissions above.


## GitHub upload
Create a new repository named `notification-bubbles`, then upload the project files/folders. Do not upload `.gradle/`, `build/`, or local secrets.\n

## Prototype notes
- UI is a basic Compose setup screen.
- Overlay is a basic TextView bubble and not yet draggable or configurable.
- This is a starter project; Android Studio may prompt to update Gradle/SDK depending on your install.
