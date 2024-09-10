
# Story App

This Story is an Android project built using Kotlin. It was created to fulfill the final coding project in "Belajar Pengembangan Aplikasi Android Intermediate".


## Features

- Modern User Interface: Uses Jetpack Compose to provide a modern and responsive look.
- Clean Architecture: Separates app concerns into domain, data, and presentation for improved maintainability and testability.
- MVVM: Uses the MVVM architectural pattern to separate View (Compose), ViewModel, and Model (data).
- News API: Fetches news data from News API to display the latest news from various categories and countries.
- Search Feature: Allows users to search for news by keyword.
- Save News: Adds a feature to save favorite news.


## Tech Stack

- Programming Language: Kotlin
- Architecture: MVVM
- Library:
      - Retrofit: For making HTTP requests to the News API
Tools: Android Studio


## Screenshots

<img src="https://github.com/user-attachments/assets/dbca8111-aedd-4a8c-864a-a3bd2098c263" width="200">
<img src="https://github.com/user-attachments/assets/2280bce2-884a-4aca-8df7-5c336231ad6c" width="200">
<img src="https://github.com/user-attachments/assets/4ec328dc-3319-4521-8771-21484842c9db" width="200">
<img src="https://github.com/user-attachments/assets/4b8c1bcd-a726-4b44-902e-21affb8ed95e" width="200">
<img src="https://github.com/user-attachments/assets/467c897b-4445-49ab-9798-4dd7ecf70af1" width="200">
<img src="https://github.com/user-attachments/assets/bd1324dc-d67e-40f3-a9da-1cb8eb6d5d14" width="200">

## Installation

1. Clone the repository

```bash
  git clone https://github.com/wildanfatah22/StoryApp.git
```
2. Open the project in Android Studio: Open the project you just cloned in Android Studio.
3. Sync Gradle: Wait for Android Studio to finish syncing Gradle.
4. Configure News API:
    - Create an account on the News API (https://newsapi.org/) and get an API key.
    - Replace the API key in the build.gradle file (app module) with your API key.
