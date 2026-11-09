# Woof

A list of dogs, each card showing a photo, name and age, that expands to reveal the dog's hobbies.

Built while following Google's [Android Basics with Compose](https://developer.android.com/courses/android-basics-compose/course) course (the "Woof" Material theming and animation codelabs).

## Features

- `LazyColumn` of dog cards with an expand/collapse icon button
- Card color animates when expanded; content size animates in and out
- Light and dark theme previews

## Built with

- Kotlin, Jetpack Compose, Material 3
- Custom Material theme: color scheme, shapes, and custom fonts (Abril Fatface, Montserrat)
- `animateColorAsState`, `animateContentSize`, Material Icons Extended
- Min SDK 24, target/compile SDK 35

## Run it

1. Open the project folder in Android Studio and let Gradle sync.
2. Run the `app` configuration on an emulator or device (Android 7.0 / API 24 or newer).

Or, with a device or emulator connected:

```sh
./gradlew installDebug
```
