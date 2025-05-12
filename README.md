# 📋 RecyclerView Sample Android App

This Android app demonstrates how to use **RecyclerView** to display a scrollable list of items using Java. The app shows a list of fruits using a custom adapter and layout.

---

## What is RecyclerView?

**RecyclerView** is a flexible and efficient widget in Android used to display large sets of data in a scrollable list or grid. Unlike the older `ListView`, RecyclerView:

- Reuses ("recycles") item views for better performance.
- Supports different layout managers (vertical, horizontal, grid, staggered).
- Allows animations and custom decorations.
- Separates layout (`ViewHolder`) from logic (`Adapter`), improving modularity.

RecyclerView is part of the Android Jetpack `androidx` library and is widely used in modern Android development.

---

## Features

- Simple vertical list using RecyclerView
- Custom Adapter and ViewHolder implementation
- Scrollable and efficient list
- Clean UI with XML layout

---

## Requirements

- Android Studio
- Java SDK 8 or higher
- Gradle 7+
- Android SDK 21+

---

## Dependencies

In `build.gradle (Module: app)`:

```groovy
dependencies {
    implementation 'androidx.recyclerview:recyclerview:1.3.2'
}
