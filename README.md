# cinePulse - Movie & TV Tracker

A high-fidelity Android application built with Jetpack Compose, Retrofit, and Firebase.

## 🚀 Features
- **Neon Branding**: Custom-designed high-fidelity logo (Film Reel & Heartbeat Pulse) and UI theme.
- **Watchlist**: Track your favorite movies and TV shows offline-first.
- **Comments & Reviews**: Leave personal thoughts and ratings on media items, persisted in a local Room database.
- **Settings Menu**: Comprehensive preferences including:
    - Dark Theme Toggle
    - TMDB Region Preference (US, UK, ZA, etc.)
    - Manual Database Synchronization tools
- **Secure Authentication**: Full Firebase integration for registration, login, and password resets.
- **Trending & Search**: Real-time integration with the TMDB REST API.

## 🛠️ Technical Stack & Architecture
- **Architecture**: Clean MVVM (Model-View-ViewModel) with Repository pattern.
- **UI Toolkit**: 100% Jetpack Compose for a modern, reactive interface.
- **Persistence**: 
    - **Local**: Room Database for offline-first capabilities.
    - **Cloud**: Firebase Firestore for user-data synchronization.
- **Networking**: Retrofit & OkHttp with Kotlinx Serialization.
- **Image Loading**: Coil for high-performance backdrop and poster rendering.
- **Concurrency**: Kotlin Coroutines & Flow for asynchronous state management.
- **Testing**: Robust unit testing suite using `kotlinx-coroutines-test`.

## 📹 Video Presentation
[Click here to watch the presentation](INSERT_YOUR_VIDEO_LINK_HERE)

---
*Created as part of the App Prototype Development Assessment.*
