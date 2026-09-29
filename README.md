# Rectify
Rectify — a modern social media platform with AI, profiles, content discovery, and community features.
## License

Copyright © 2026 Angshuman Pal. All rights reserved.

This project is not open source. Unauthorized copying, modification,
distribution, or commercial use is not permitted without permission.
App by Angshuman Pal 
Idea by Rajat Mandal
Script by Angshuman Pal 

Rectify

Rectify is a modern social media application built with Android and Jetpack Compose.

Features

- Google authentication with Firebase
- User profiles
- Profile photo, name, and email
- Create and share content
- Picture and video posts
- Stories and status
- Top Posts system
- Discover content
- Content search
- Comments and engagement
- Rectify AI
- Social Trends
- Social Information
- Advice content
- Firebase-powered backend
- Notification support

Technology

- Kotlin
- Jetpack Compose
- Android
- Firebase Authentication
- Firebase Firestore
- Firebase Storage
- Firebase Cloud Messaging
- Coil

App Structure

Rectify is designed with separate screens and backend functionality for authentication, profiles, content, discovery, search, AI, and account features.

Top Posts

Rectify's Home section uses a "topScore" system to rank posts based on engagement.

The score can use:

Likes × 3
Comments × 5
Shares × 7
Views × 1

Posts with higher scores appear higher in Top Posts.

Privacy and Security

Sensitive credentials and API keys should never be stored directly inside the Android application.

Firebase Authentication, Firestore Security Rules, and Storage Security Rules should be configured before production release.

Do not commit:

- API keys
- passwords
- private signing keys
- "local.properties"
- keystore files
- other private credentials

Development

This project is developed in Android Studio using Kotlin and Jetpack Compose.

Clone the repository, open it in Android Studio, allow Gradle to synchronize, and build the application.

Status

Rectify is under active development.

License

License information will be added separately.
