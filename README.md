# Sonora for Android

Native Android companion for the Sonora self-hosted audiobook service.

## Stack

- Kotlin and Jetpack Compose
- Media3 / ExoPlayer for background playback
- Sonora's versioned REST API
- Room and WorkManager will be added for caching, downloads, and reliable progress sync

## Open in Android Studio

Open this repository as a Gradle project with JDK 17. The initial screen verifies the project builds; the next feature is server setup and sign-in.

The app is intentionally API-first: it does not hold Audiobookshelf administrator credentials.